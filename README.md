# Bulk_RNA_Deseq_Pipeline_Draft
Draft version of Bulk RNA DESeq Pipeline for Gaulton Lab

This pipeline is intended for use with Salmon quantification files.

Notebook #1: 
1. read Salmon quantification files
2. merge files to DESeqDataSet object
3. annotate genes with GENECODE v41 gene symbols
4. calculate TPMs
5. merge sample replicates per donor by sum
6. calculate TPMs again

Notebook #2: 
1. run DESeq2
2. create DESeq results table

Notebook #3: 
1. process results table
2. plot results
