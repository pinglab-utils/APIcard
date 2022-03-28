## Integration of PyBiomart-Scanpy-GO-Scanpy-UniProt APIs
### Project II

####  Explored by: 

```HUANG, HELEN```,```MATTHEWS, JAMIE EMOTO```,```PERRIE, JONATHAN VI```-```(Bioinformatics 201, Winter-2022, UCLA)```


### Description: 

#### Task:

Given a scRNA-seq data set containing a mixture of cell types, annotate with gene names
(e.g. PyBiomart), identify the marker genes corresponding to each cell type and construct a
trajectory mapping (e.g. Scanpy). Additionally, identify enriched Gene Ontology (GO) terms
within marker genes to understand key functions of each cell type (e.g. Gene Ontology API).
Based on the gene markers, a subsequent proteomics study can be followed up on the newly
classified cell types. Finally we can find the names of the differentially expressed proteins and
functionally annotate them (e.g. UniProt API).

#### Background: 

Cells are specialized for different functions. To better understand rare cell types,
we need to identify genes that are distinct in their gene expression profile and look at enriched
biological processes within these cells to understand some key functions of these different cell
types. We can further look at their ontological frame with respect to other cell types mapped in
some embedding space.

#### Goal: 

Reclassify cell types in the human blood and append newly identified cell types to the
lineage tree of known cell types. Understand the specialized functions of these newly identified
cells compared to known cell types.

#### Method:

1. Gene name annotation: Use PyBiomart and the list of gene IDs to get gene name
annotations
2. Marker gene identification: Use Scanpy pipeline (with some downsampling to balance
class sizes) to filter and cluster cells. Then from these clusterings, compute marker
genes
3. Gene Ontology: Use the list of identified marker genes for each cell type to get enriched
GO terms from Gene Ontology API
4. Pseudotime analysis: Use Scanpy pipeline with a separate projection of rare cell types
to embedding after initial trajectory construction
5. Proteins: Use the protein list and UniProt API to get protein information (e.g., protein
name) from UniProt and use functional annotating software (e.g. PIGNON) to detect
enriched biological processes to understand the function of the cells.

#### Expected Outcome: 

Marker genes for new cell types, cell type trajectory, and functional
annotations for them.

#### Reference:

This project is modeled after “Single-cell RNA-seq reveals new types of human blood dendritic
cells, monocytes, and progenitors” (https://www.science.org/doi/10.1126/science.aah4573)