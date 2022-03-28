### Integration of Scanpy-PyBio Mart

#### Explored by:

```HUANG, ELAINE```,```XUE, ALBERT```,```Wei, Angela```-```(Bioinfo 201 - Winter 2022)```


### Description: 
#### Task:
Given a list of marker genes for specific cell types, convert the format of the gene name
from hgnc_symbol to their ENSEMBL IDs.

#### Background: 
Single-cell RNA-seq is revolutionary given that it can allow scientists to study cell-
type specific expression rather than bulk tissue. In order to identify specific cell types, the
expression of marker genes for those cells must be identified. However, gene quantification
tools often rely on the gene names to be a specific format, i.e. ENSEMBL IDs. Therefore, an
easy way to convert gene names is necessary.

#### Goal: 
Convert single-cell marker genes (identified from the scanpy API) from hgnc_symbol to
ENSEMBL.

#### Method:
1. Use the scanpy API to pull lists of marker genes for specific cell types.
2. We will then use the PyBio Mart method for querying biomart databases using Python to
easily convert the gene names into ENSEMBL format.

#### Expected outcome: 
A dataframe with more detailed annotation of cell marker genes