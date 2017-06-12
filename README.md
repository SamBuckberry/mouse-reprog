
This repository contains summarised data and analysis files for MEF cell reprogramming experiments.

### Data files 

#### ATAC-seq

Folder containing all ATAC-seq peak call files.  
[/ATACseq/processed_data/ATAC_peaks/merged_replicate_peaks](/ATACseq/processed_data/ATAC_peaks/merged_replicate_peaks)

File containing the read counts for ATAC-seq libraries in the union ATAC-seq peak set.  
[/ATACseq/processed_data/ATAC_peaks/atac_all_peaks_union_counts.txt](/ATACseq/processed_data/ATAC_peaks/atac_all_peaks_union_counts.txt)

File containing the read counts for ChIP-seq libraries in the union ATAC-seq peak set.  
[/ATACseq/processed_data/ATAC_peaks/atac_all_peaks_union_os_chip_counts.txt](/ATACseq/processed_data/ATAC_peaks/atac_all_peaks_union_os_chip_counts.txt)

Folder containing BED files for ATAC-seq c-means clusters. Also contains folders for Homer2 motif enrichment results for each c-means cluster.  
[/ATACseq/processed_data/atac_cluster_peaks/c_means_peaks](/ATACseq/processed_data/atac_cluster_peaks/c_means_peaks)

**Please note that the cluster numbers for the BED files are different to the cluster numbers indicated in the manuscript. Cluster number != Manuscript number. 1=2, 2=6, 3=4, 4=7, 5=1, 6=3, 7=5, 8=8.

#### ChIP-seq

Folder containing the ChIP-seq peak call files generated by MACS2.  
[/ChIPseq/processed_data/macs_output/merged_replicate_peak_calls]


#### RNA-seq

File containing the raw read counts for each gene.  
[/RNAseq/processed_data/polo_mm_iPSC_RNAseq_mm10_UCSC_gene_counts.txt]

File containing the TPM normalised expression data.  
[/RNAseq/processed_data/polo_mm_iPSC_RNAseq_mm10_UCSC_TPM.txt]

File containing sample id mapping for the above files.  
[/RNAseq/processed_data/sample_ids.txt]





