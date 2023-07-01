# GEO_Oral_Cancer_miRge3_Analysis
Analysis of miRNA expression between WT and FXR1 knockdown oral cancer cells using miRge3 in WSL environment.

# Getting started
Following are the tools used for the analysis.

Windows Subsystem of Linux-
Windows Subsystem for Linux is a feature of Windows that allows developers to run a Linux environment without the need for a separate virtual machine or dual booting.
https://learn.microsoft.com/en-us/windows/wsl/install

mirGe3-
An update to the Python package to perform a comprehensive analysis of small RNA sequencing data, including miRNA annotation, A-to-I editing, novel miRNA detection, isomiR analysis, visualization through IGV, processing Unique Molecular Identifiers (UMI), tRF detection and producing interactive graphical output.
https://mirge3.readthedocs.io/en/latest/installation.html

# Data mining

GEO- 
Gene Expression Omnibus is a public functional genomics data repository supporting MIAME-compliant data submissions. Array- and sequence-based data are accepted.

ENA-
The European Nucleotide Archive provides a comprehensive record of the world’s nucleotide sequencing information, covering raw sequencing data, sequence assembly information, and functional annotation.

Downloading the fastq sequences-
Searched for the data available in the geo database that can be processed with the system currently available to me. The study was on examination of miRNA expression between WT and FXR1 knockdown oral cancer cells with geo accession GSE117031. Collected the SRA id from there and searched using the ENA browser. There were four fastq files there, downloaded the script. The link to download the fastq files directly is given below.
https://drive.google.com/file/d/1oR0rlCz2pf020BG1HIhgvwi9jPagZFwz/view?usp=drive_link

Reference genome-
Here the study is on human. So we used the human genome as a reference. A human genome reference sequence is an accepted representation of the human genome sequence that is used by researchers as a standard for comparison to DNA sequences generated in their studies. It can be downloaded directly from the genome browsers like UCSC, NCBI, Ensembl etc. The link to directly download the human reference genome is given below.

