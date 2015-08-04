---
title: NCBI Hackathon #2: RNA-seq Read Mapping Tutorial
layout: post
---

Useful links:

- NCBI [Assembly page](http://www.ncbi.nlm.nih.gov/assembly/GCF_000001405.30) for GRCh38.p4
- GRCh38 [annotation](ftp://ftp.ncbi.nlm.nih.gov/genomes/all/GCF_000001405.30_GRCh38.p4/GCF_000001405.30_GRCh38.p4_genomic.gff.gz)
- GRCh38 [sequence](ftp://ftp.ncbi.nlm.nih.gov/genomes/all/GCF_000001405.30_GRCh38.p4/GCF_000001405.30_GRCh38.p4_genomic.fna.gz)

# Alignment
```BASH
STAR --genomeDir ~/afdennis/GRC28_star  --runThreadN 24 --readFilesIn ~/tan/rawdata/SRR1153470_1.fastq ~/tan/rawdata/SRR1153470_2.fastq --outFileNamePrefix STAR
```
## Title 2
### Title 3

- List 1
- List 2
- List 3

1. Item 1
1. Item 2
1. Item 3

