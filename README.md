# VirologyByTheNumbers
**This is a series of code, input data, and output files that accompany the manuscript "Viral Genomes by the Numbers: A Comprehensive Quantitative Exploration of Thousands of Viruses" by Gita Mahmoudabadi and Rob Phillips. If using these scripts or data, please cite our manuscript.**

All code is written in Python (Jupyter notebooks). Below you can find a description of each notebook. These notebooks all share in common the very first block of code (and its slight variations), wherein rawdata is read from all_rpt, all_ptt, and all_faa directories, and relevant genomic parameters for each virus, such as genome length, number of protein-coding genes, among other parameters, are stored in lengthData. The list of Jupyter notebooks and their function is shown below: 

  * virusHostHistogramsFV.ipynb  (used to create Figure 2)
  * viromePieChartsFV.ipynb  (used to create Figure 2)
  * geneLengthsFV.ipynb	 (used to create Figure 4)
  * percentNoncodingFV.ipynb (used to create Figure 5)
  * genomeLengthsFV.ipynb (used to create Figure 3 and SI Figure 2)
  * geneOrderAndGeneAbundanceFV.ipynb (used to create Figures 6 and 7)
  * viralAttachmentSites.ipynb (used to create SI Figure 3) 
  * viralBacterialBlast.ipynb (used to create SI Figures 4 through 9) 

Most scripts will require the following dependencies (Note, using Anaconda, the installation can be as easy as running a command such as: "conda install seaborn"):
  * Python 3.4+
  * ete-toolkit (3.0) (pip install https://github.com/jhcepas/ete/archive/3.0.zip)
  * scipy 
  * pandas 
  * Bio
  * os
  * numpy
  * matplotlib
  * seaborn 
  * io
  * re
  * random
  * functools

The following should be in the working directory (i.e. the directory where the scripts are): 
 * all_rpt (provided as zipped directory, make sure to unzip the directory)
 * all_ptt (provided as zipped directory, make sure to unzip the directory)
 * all_faa (provided as zipped directory, make sure to unzip the directory)
 * folderToHostTaxid.txt
 * blastBacterialFinalv2
 * phageProteins
 * bactBlastOutputAnalyzedTopHitsV2.txt
 * terminaseLmatrix.txt
 * terminaseSmatrix.txt
 * attLeftNumIdenSeqsMatrix.csv		
 * attLeftSeqPercentIdentityMatrix.csv	
 * accPhages.txt	
 * attSitePosDetail1	

Output files that are included:
  * hypoBactProtCharacterized.txt 
  * hypoPhageProtCharacterized-v2.txt
  * textFile-1-allViruses.txt


			
			

		



