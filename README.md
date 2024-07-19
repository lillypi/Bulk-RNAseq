# Bulk-RNAseq
Basic example of bulkRNAseq workflow (manual)

This workflow features:

- downloading GTF (annotation file), transcriptome (fastq file), geome (fastq file), 
- FastQC for Quality Control Metrics
- Salmon psuedo-aligner for quantifying reads (generate index as well)
- STAR aligner for generating mapped reads (generate index as well)
- featureCounts for transcript quantification
