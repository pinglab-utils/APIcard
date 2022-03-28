## Integration of NCI Genomic Data Commons - (GDC) API and Gene Ontology API

#### Explored by: 

```CHENG, MICHAEL WEN-KAI```, ```OH, JIEUN```, ```YAMAMOTO,RYO```-```(Bioinformatics 201, Winter-2022, UCLA)```


### Description: 
#### Task: 
Given clinical features of interest, try to see how transcriptomic profiles
(eg. from NCI Genomic Data Commons) for samples with these features differ.
Input differentially expressed genes for GO enrichment analyses. Use Gene
Ontology API to explore the genes and GO terms that were enriched.

#### Background:
You have a clinical feature of interest and want to see how it affects the
transcriptional profile of a cancer type. You want to see which genes are
differentially expressed between samples with these features and see which GO
terms are associated with these genes.

#### Goal: 
Find differentially expressed genes and GO terms enriched for cancer
samples with that clinical feature. The result should give us clues to how
(depending on significant GO term) that clinical feature affects the cancer.

### Method:
1. Retrieve gene expression data:
Curate RNA-seq datasets for cancer datasets using provided NCI
Genomic Data Commons API, we can also retrieve metadata and clinical
features for the dataset to use for later analysis
2. Identify upregulated/downregulated genes in clinical features of
interest:
Using the curated dataset, run differential gene expression analysis to
obtain gene list that are either upregulated or downregulated for specific
clinical features
3. Functional analysis:
Using Gene Ontology API, analyze what pathways are enriched for these
clinical features. This process gives us insights into how clinical features
might be affected by specific pathways

### Expected Outcome:
List of pathways with statistics based on DE genes to specific clinical features