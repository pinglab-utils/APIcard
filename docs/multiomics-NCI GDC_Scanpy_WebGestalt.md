## Integration of NCI Genomic Data Commons - (GDC) API, Scanpy and WebGestalt APIs


#### Explored by: 

```HUANG, HUILING```,```FU, JINGYUAN```-```(Bioinformatics 201, Winter-2022, UCLA)```


### Description: 

#### Task: 
Functional pathway enrichment analysis of disease marker genes identified from
RNA-sequencing datasets.

#### Background:
Given RNA-seq data from normal and disease cells (such as cancer cells) from
the same tissue of an individual, identify marker genes and study the genetic pathway
enrichment of the disease.

#### Goal:
Identify the enriched terms from different functional databases (including pathway,
network, disease, etc.) from cancer marker genes. The terms are expected to be related to
underlying molecular mechanisms and the development process of the chosen disease.

#### Method:
1. RNA-seq retrieval: RNA-seq data could be obtained experimentally, or downloaded
from public repositories such as NCI Genomic Data Commons - (GDC) API for a specific
disease of interest.
2. Marker gene identification: We can analyze the RNA-seq dataset using Scanpy API,
that involves filtering, clustering, and identifying marker genes. This step will output a list
of marker genes specific to this disease.
3. Enrichment analysis: Eventually, we can input the list of marker genes to WebGestalt
API and retrieve functional pathway enrichment analysis results.

#### Expected Outcome:
A list of functional enriched terms that would potentially involve in the
disease mechanism, with statistics and figures indicating the significance of each term.