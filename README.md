# finalproject
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

Milestone 1 (11/13/18): Read up on how to use STAR and Gencode for sequence alignment and use them for aligning atleast one subset of the files
Milestone 2 (11/20/18):  Align all the sequences and use featurecount to count the reads
Milestone 3 (11/27/18):  Final stages of analysing differentially expressed genes using R



