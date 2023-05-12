GWAS experiment

165 Lotus genotypes
107 bacterial isolates
3 independent replicates

### Data between DS3 and DS4 can be linked by bacterial taxa and plant genotype but not through ASVs or Isolate names and potentially more ###

Growth conditions :
16/8 for the day-night cycle, 75% Rh and 22°C/18°C in temperature (Day-night). 
After 22 days of growth, the root rhizosphere is harvested and the shoot weighted.

Data :
Amplicon sequencing targeting the 16S v5-v7 region (NovaSeq 2x250)
Count tables created with QIIME2

Files :
ASV-Isolate-mapping.csv :
contains the output table from VSEARCH giving the treshold 97% (correspondance between the Feature_ID and the reference)

isolatesXPlantGeno.csv :
contains the raw count table created with DADA2

metadata.csv :
contains information about the samples

taxonomy.csv :
contains the taxonomy information of the isolates from the D1 level (Domain) to the D6 level (genus) from QIIME2

OrthoFinderMatrix_Raw.tsv :
Matrix absence/presence of Orgthogroups (OG) from OrthoFinder (created by Adrian Gomez)

OrthoFinderMatrix_GeneCount.tsv :
Gene count in the different orthogroups

lotus_snps.csv :
Snp matrix for lotus genotypes
	0 = homozygous non-reference
	1 = heterozygous 
	2 = homozygous reference

PhenotypicMeasurments.csv :
Shoot fresh weights (g) of lotus genotypes at time of measurement

syncom_seqs.fa :
16s v5-v7 sequences associated with isolates/isolate groups










