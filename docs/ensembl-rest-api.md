## API: Ensembl Rest API

#### Explored by: 

```DARCI-MAHER, NICHOLAS WAXTER```, ```RAZMA, CONNOR JOHN```- ```(Bioinfo 201 - Winter 2022)```

### Description

Ensembl is a genome browser that returns an Ensembl ID as part of its annotation program. The Ensembl Rest API provides
many additional functions that supplement this genome browser detailed in the use cases below. The Ensembl Rest API
accesses the software for each of these use cases that was developed by the software team at Ensembl. Ensembl can be accessed directly at [uswest.ensembl.org](https://uswest.ensembl.org/info/docs/tools/index.html). Instructions for the software are detailed [REST API document available here](https://rest.ensembl.org/).


### Use cases

- Input an Ensembl identifier for a genetic feature, and retrieve the Ensembl version of that ID. This would be useful at the
beginning of an analysis as a QC step to make sure all your IDs were from the same version.
- Input a gene and retrieve a tree showing the ancestry of that gene across different species.
- Input an Ensembl ID and retrieve a list of analyses that have been done using that gene, variant, or other feature.
- Input a genetic variant and retrieve LD for all variants in a window around that variant.
- Input a gene and retrieve a list of genes, variants, and other features that overlap that gene in the genome.
- Input a phenotype and retrieve a list of genes, variants, and other features that are known to be associated with that
phenotype. Optionally, the PubMed IDs of papers that made those associated can be added to the response.
- Input a genetic variant and retrieve information on its downstream consequences, including what type of variant it is, its
CADD deleteriousness score, its sequence ontology, and more.

### Tutorial
- [Ensemble REST API tutorial in Google Colab is available here](https://colab.research.google.com/drive/1vhnHo1KlYryD7bGO5oWc4UpaKk3rHMoS?usp=sharing)
