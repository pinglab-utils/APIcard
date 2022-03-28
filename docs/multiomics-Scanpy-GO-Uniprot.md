## API Integration Proposal:

### Title: Determining functional differences in aging on a single cell level

####  Explored by: 

```HUANG, HELEN```,```MATTHEWS, JAMIE EMOTO```,```PERRIE, JONATHAN VI```-```(Bioinformatics 201, Winter-2022, UCLA)```


### Description: 

#### Task:

Retrieve various single-cell RNA sequencing data from human patients from fat tissue,
annotate cell types (i.e FACS or marker gene analysis) and then build a tree-based classifier to
search for informative genes.

#### Background: 

Given single-cell RNA-sequencing data, downloaded and integrated using a
general purpose API, e.g., Scanpy, we may want to determine a list of informative genes by cell
type and time point before searching gene annotation databases such as Gene Ontology or
gene product databases such as UniProt for biologically interesting signals, e.g., functional
differences between cell types that have been conserved or that change over time.

#### Goal: 

Determine the potential function and potential phenotypic changes that occur due to
aging in a particular tissue or set of tissues.

#### Method:

1. Use Scanpy to download and integrate publicly available ScRNA datasets from NCBI for
multiple patients across the same tissue types.
2. Label data sets by cell type.
3. Separate datasets out by time points, e.g., by age.
4. Build a tree-based classifier to classify each cell type.
5. Search for most informative genes derived from the tree-based classifier at each time
point.
6. Given this list of most informative genes, search in Gene Ontology or UniProt to search
for functional differences that have been conserved or changed over time.

#### Expected Outcome:

There will be genes that constantly remain informative of cell type across age. However
some genes might become more important in some cell datasets from older patients. These
may include genes relating to inflammation, while those related to cell growth may become less
important.