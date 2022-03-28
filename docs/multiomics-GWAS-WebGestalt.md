## PubTator Central (PTC) API

#### Explored by: 

```CHEN, JESSICA```, ```DODSON, JACK PATRICK```, ```FLYNN-CARROLL, ALEXANDER OWEN```-```(Bioinformatics 201, Winter-2022, UCLA)```


### Description: 

#### Task:

Multi-omics integration to determine the biological pathways that are over-represented in
a set of genes associated with Parkinson’s provided via GWAS.

#### Background:

The GWAS Catalog API can provide a list of genes that are significantly
associated with Parkinson’s disease. WebGestalt Web API takes as input the list of genes and
performs an over-representation analysis (ORA). These two APIs can be integrated to find
statistics relating to a holistic set of genes related to Parkinson’s disease.

#### Goal:

Identify the enrichment of Parkinson’s-associated genes with respect to a panel of
phenotypes provided by WebGestalt. This can give more genetic information regarding
Parkinson's disease.

#### Method:

1. GWAS query for associated genes: Find the list of genes associated with Parkinson’s
from the GWAS catalog.
2. Gene list to statistics: Input the list of related genes into the WebGestalt Web API to
conduct an over-representation analysis on the gene set relative to phenotypes such as
KEGG pathways or GO terms.

#### Expected Outcome:

Produce a list of over-represented biological pathways relative to a large
set of genes related to Parkinson’s.