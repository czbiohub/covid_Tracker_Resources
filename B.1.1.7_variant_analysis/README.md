# B 1.1.7 varaint analysis using sc2-illumina-pipeline.

## purpose : the goal of this analysis was to verify if biohub sc2-illumina-pipeline can detect the qaulifying SNPs and deletions seen in the B 1.1.7 variant. 

### approach : 

1. Download publically available data (SRA reads) and run this data through the sc2-illumina-pipeline.
    + selected easily available sample on the 20I clade. 

2. Look at the coverage plots and combined.stats.tsv for the summary.

3. Download the original uploaded consensus from GISAID and compare it to the consensus generated from the sc2-illumina-pipeline.
    + upload the combined.fasta on nextclade and look at the tree placement 
    + study and compare the gaps and SNPs seen in both consensus