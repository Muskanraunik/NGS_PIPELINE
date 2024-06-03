# NGS_Pipeline: Snakemake workflow for RNA-seq analysis
This Snakemake workflow streamlines the analysis of RNA-sequencing data.It integrates essential tools like FastQC for quality control, HISAT2 for read alignment, Samtools for BAM file manipulation, and HTSeq-count for gene expression quantification.
# Features
* Quality Control: Uses FastQC for initial quality assessment.
* Read Alignment: Employs HISAT2 for aligning RNA-seq reads to a reference genome.
* BAM File Manipulation: Uses Samtools for sorting, indexing, and manipulating BAM files.
* Gene Expression Quantification: Utilizes HTSeq-count for quantifying gene expression.
* Differential Expression Analysis: Outputs are compatible with DESeq2 for downstream analysis.
# Installation: 
* Ensure Snakemake is installed on your system.
# Excution
* Snakefile Creation: Write the pipeline code within a file named "Snakefile."
* Test the pipeline's functionality using the command snakemake --dry-run.
* Launch the pipeline with snakemake, optionally specifying core usage (e.g., snakemake --cores 12) for parallel execution.
