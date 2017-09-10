## Collection of scripts
List of scripts created in our group, so that it's possible to see if someone has already made the code you need.

The scripts can be finished, half-finished or in production. Provide as much detail as possible, including links to the scripts if possible. If these are not currently sharable, just include a short description and provide contact information.
<br><br>

### Genie

A wrapper for a large number of functionalities, mostly for running on summary stat files.
Currently including:
- GWAS analysis using plink (can use both dosage and binary plink files)
- MAGMA gene set analysis*
- Polygenic risk score calculation using PRSice software
- Association analysis with precomputed PRS scores.
- Annotate variants in summary file to dbsnp ids 
- Predixcan analysis 
- Metaxcan analysis
- FUSION transcriptome wide association analysis
- LDscore calculcation, partition heritability, cell type specific analysis, partition continuous annotation*
- Runs of homozygosity

Location: https://github.com/drveera/genie

*See also makedly different offerings for these programs below from Mads

Contact: Veera (veera@biomed.au.dk) or Jonatan (jonatan.smp@gmail.com)
<br><br>

### GCTA - bivar-REML
Split cases and controls to perform bivariate GCTA

Contact: Thomas Als tda@biomed.au.dk 
<br><br>

### PCA - Eigensoft Rij projection
Calculate PCA, including precise calculations of related individuals. (This is not the case in the standard Ricopili pipeline.)

Contact: Thomas Als tda@biomed.au.dk 
<br><br>

### OR_snp permutation
Calculate a distribution of ORs when removing subsets of individuals of a specific size.

Contact: Thomas Als tda@biomed.au.dk 
<br><br>

### Munge sumstats
Takes an unprocessed GWAS sumstat file, performs QC and changes it to a standard format.

Location: https://github.com/ymer/ldsc   

Contact: Jonatan (jonatan.smp@gmail.com)  
<br><br>

### GATK
Pipeline that runs GATK variant calling

Contact: Jinjie (jjduan@biomed.au.dk)
<br><br>

### Merge waves
Merges waves of multi-wave ricopili data, keeping the structure.

Contact: Jonatan (jonatan.smp@gmail.com) 
<br><br>

### Filter waves
Filters out any number of individuals, and any number of SNPs from multi-wave ricopili data, keeping the structure.

Contact: Jonatan (jonatan.smp@gmail.com) 
<br><br>

### Scripts for running a ricopili association analysis on iPsych data
Including:  
find_outliers.py - Based on PCA, identify individuals outside an ellipsoid centered on ethnic Danes  
msl_merge.sh - Creates the folder structure and files needed to run an association using merged waves  
msl_meta.sh - Creates the folder structure and files needed to run an association using a meta analysis of waves

Link: jail - IGdata/faststorage/userdata/ijpal/rico

Contact: Jonatan (jonatan.smp@gmail.com) 
<br><br>


### MAGMA
This is a plug and play solution with:
- Proper handling of differences in variant naming btw. Ricopili and MAGMA reference panels
- Filtering by MAF and INFO score
- Exclusion of the broad MHC region
- Optional padding of genes to include nearby regulatory elements
- A broad and up to date collection of gene set definitions
- Jaccard indices between gene sets (a metric for the overlap of two sets)

In alternative set-up I've prepared ~23 mostly neuropsychiatric traits that can be assayed for a gene set of interest. This is done off-site, so just ask me to do so.

Link: /faststorage/jail/project/DBS1to10/Wave1-10_2015_03/userdata/haub/scripts

Contact: Mads Engel Hauberg - mads{d0t}hauberg{åt}gmail{d0t}com
<br><br>

### LDSC partitioned heritability
This is a plug-and-play solution with:
- Custom annotations for very broad scope of the epigenomic annotations of the Roadmap Epigenomics mapping consortium
- The standard LDSC partitioned heritability annotations
- Exclusion of the broad MHC region

In alternative set-up we have various not yet publicly available epigenomic annotations and the ability to run additional genomic annotation of interest in ~23 mostly neuropsychiatric traits. This is done off-site, so just ask me to do so.

Link: /faststorage/jail/project/DBS1to10/Wave1-10_2015_03/userdata/haub/scripts

Contact: Mads Engel Hauberg - mads{d0t}hauberg{åt}gmail{d0t}com
<br><br>

### Annotation of GWAS Genomic regions
Annotates the daner regions with a broad range of genetic information.

Link: /faststorage/jail/project/DBS1to10/Wave1-10_2015_03/userdata/haub/scripts

Contact: Mads Engel Hauberg - mads{d0t}hauberg{åt}gmail{d0t}com
<br><br>

### Wrapper for the three previously mentioned script sets.
Changing just three lines of code one can run all of these scripts for a daner sumstat.

Link: /faststorage/jail/project/DBS1to10/Wave1-10_2015_03/userdata/haub/scripts

Contact: Mads Engel Hauberg - mads{d0t}hauberg{åt}gmail{d0t}com
<br><br>
