# Variable_Length_Amplicon_Sequencing
R scripts for processing and analyzing variable-length amplicons (ITS, 18S) with DADA2.

This repository contains scripts and workflows for processing 16S amplicon sequencing data using DADA2 in R, with downstream analysis in phyloseq. 
There are separate scripts for handling data from a single sequencing run vs analyzing data from multiple sequencing runs. 
Each sequencing run has distinct error patterns, so combining results runs for the whole workflow results in error correction profiles that introduce more errors than originally existed.

For 16S amplicon sequencing, see repository at https://github.com/kiragoff/16S_Amplicon_Sequencing
