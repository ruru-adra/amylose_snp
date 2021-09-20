# amylose_snp
mining amylose SNPs from genome &amp; RNA-seq data using GATK4

datasets:

1. Whole genome sequencing of 6 Malaysian rice varieties.
2. RNA-seq of 6 Malaysian rice varieties

###Quality control
```r
fastp -i MRQ76_1.fastq -I MRQ76_2.fastq -o cleanMRQ76_1.fastq -O cleanMRQ76_2.fastq -w 4
```
