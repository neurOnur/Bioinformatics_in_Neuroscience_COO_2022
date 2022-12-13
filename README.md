## COO - single cell RNA sequencing data analysis
Bioinformatics in Neuroscience course, 2022
Single cell data analysis of the adult human brain

### About this tutorial

This is the single cell RNA sequencing (scRNAseq) data analysis tutorial, prepared for the scRNAseq days of the Bioinformatics in Neuroscience course, organised for the Neuroscience and Cognition master and other Utrecht University master programs. The script follows the well known vignette of the Seurat (v3) pipeline for pbmc, adapted to analyse the scRNAseq data of the adult human brain.

The data is a subset of the recent work from Siletti et al (Bioarxiv, 2022; https://www.biorxiv.org/content/10.1101/2022.10.12.511898v1), which you received for this course. In this study, ~4M nuclei from different parts of the human brain is sequenced. You will later here a talk by the first author of the study, which will be a natural continuation of this practice. A subset of the original atlas is provided for the purpose of this practical in the file "../rawdata/A46_10X176_8_count_data.rds" . An accompanying metadata file, "../rawdata/A46_10X176_8_metadata.rds", will give you additional information. The rawdata as well as analysis of the entire dataset can be reached at: https://github.com/linnarsson-lab/adult-human-brain

Participants will then learn how to use the ‘Seurat’ pipeline, the most popular ‘R’ package to process and analyze scRNAseq data. The instructor will guide the students step-by-step, where a prewritten code will take through the first steps of scRNAseq data analysis. These include shaping the raw data, preprocessing, dimensionality reduction, basic clustering and differential gene expression analysis.

----------

### Learning goals

1. Gain the capacity to run a standard scRNAseq data analysis pipeline independently

2. Have the ability to interpret the results of single cell data analysis

The course used the CoCalc server: https://cocalc7.science.uu.nl/

### During the tutorial, keep in mind

1. What are the major considerations during the preprocessing steps?

2. How does dimensionality reduction help us understand the data?

3. What is a molecular signature? How can marker genes help us undertand cellular (and brain) function?

----------

Correspondance, requests or questions can be addressed to: o.basak@umcutrecht.nl
***Onur Basak***
