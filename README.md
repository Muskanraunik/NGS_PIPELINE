# NGS_Pipeline: Snakemake workflow for RNA-seq analysis
# This Snakemake workflow streamlines the analysis of RNA-sequencing data. 
# It integrates essential tools like FastQC for quality control, HISAT2 for read alignment, Samtools for BAM file manipulation, and HTSeq-count for gene expression quantification.
# The output can be used for differential expression analysis with DESeq2.
# Installation: Ensure Snakemake is installed on your system.
# Snakefile Creation: Write the pipeline code within a file named "Snakefile."
# Dry Run: Test the pipeline's functionality using the command snakemake --dry-run.
# Execution: Launch the pipeline with snakemake, optionally specifying core usage (e.g., snakemake --cores 12) for parallel execution.
