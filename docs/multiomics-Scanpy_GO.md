## Proposal: Determining functional differences in aging on a single cell level

#### Explored by: 

```FLORES, MARIA V```, ```HAMILTON, TIMOTHY```, ```MAH, JONATHAN CHARLES```- ```(Bioinfo 201 - Winter 2022)```



### Description: 

#### Task and Requirements:
1. Determine how cells of particular types in a particular tissue change
their functional phenotype during the aging process

2. Required to Integrate Data from Multiple patients and multiple time
points to identify cell types

3. Requires a database of Genes and Functional Analyses

#### Background and Goal:
1. Given scRNA-seq data, downloaded and integrated using Scanpy
2. We want to find a list of informative genes for functional differences by
cell type and age
3. Cells are known to undergo changes in size shape and number due
to aging

4. Once we have a list of informative genes, we can consult a gene
annotation database or gene product database for functional differences
across cell type or age.

Our goal is to determine the potential functional changes and potential
phenotypic changes that occur due to aging in a particular tissue or set of
tissues.

#### Method:
1. Use Scanpy to download and integrate publicly available ScRNA datasets
from NCBI for multiple patients across the same tissue types.
2. Label data sets by cell type.
3. Separate datasets out by time points, e.g., by age.
4. Build a tree-based classifier to classify each cell type.
5. Search for most informative genes derived from the tree-based classifier
at each time point.
6. Given this list of most informative genes, search in Gene Ontology or
UniProt to search for functional differences that have been conserved or
changed over time.

#### Expected Outcome:
1. Cell types should roughly be the same during the aging process ( with
some exceptions)
	a. Aging affects internal cellular functions but not the composition of
cells (Tissue dependent)

2. Certain Functional phenotypes will be overexpressed in older patients
	b.  E.g Inflammation
3. Certain Functional Phenotypes will be underexpressed in older patients
	c.  E.g quiescent stem cells related pathways