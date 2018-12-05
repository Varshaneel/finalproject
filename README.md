# Final Project
TRGN510 Final Project 2018

# Proposed Scope of Work       Varsha Neelakantan


# General Description: 

Count-based differential expression analysis of sequencing data

One of the pathologies of Alzhiemer’s disease is dysfunctional/disrupted BBB. Pericytes are cells that belong to the Blood Brain Barrier and play an important role in maintaining the blood brain barrier integrity as well as in the functioning of the barrier. 

I want to identify differentially expressed genes in brain pericytes from sAD (Sporadic AD) patients compared to normal/WT pericytes. 

# Datasets used: 

RNA Sequence data in FASTQ format are available from 2 sAD patients and 1 WT in duplicates. 

# Proposed Analysis: 
## Pipeline:

Align (Input: fastq files and  Output: BAM file) the sequences using STAR and Gencode 
Use Featurecount (reads bam files) – to count reads 

## R/Rstudio:

Run differential analysis using DESeq (In R)
Heatmaps to Violin plots to visually represent these differentially expressed genes.

# Timeline and Milestones:

COMPLETED Milestone 1 (11/13/18): Read up on how to use STAR and Gencode for sequence alignment and use them for aligning atleast one subset of the files
COMPLETED Milestone 2 (11/20/18):  Aligned all the sequences and use featurecount to count the reads
Milestone 3 (11/27/18):  Final stages of analysing differentially expressed genes using R

## Progress as of 11_13_2018

Got the Fastq files and tried running STAR for alignment. There were issues running the software in my Mac because it required over 32 GM ram. Tried different approaches but didn't work

### Feedback: 

Run the program on teh HPC or trgn server. 

## Progress as of 11_20_2018

Used STAR To align the fastq files and the output was generated in BAM format.All this was done on the TRGN server as it had more memory. 
featurecounts (In R) was used to read the bam outputs and generate read counts.
DeSEQ2 was used to analyse the differential expression of genes in the samples.
Volcano plots and Heatmaps generated

### Feedback:

To document the progress so far and get shiny portal for the volcano plotes to make it interactive.
Make the rmd file a little more organised 
Make a powerpoint of how the pipeline goes from fastq files to the end result

## Progress as of 11_27_2018

Generated Volcano plots for different comparisons and PCA plots.
Attempting to make a Shiny R portal to make an interactive volcano plot
Trouble in kniting the R markdown and making the HTML file into a weblink that can be seen by people.

### Feedback:

Use Rpubs for publishing the R markdown file
Try using R shiny interactive platform

# Final project submitted : 12_04_2018

