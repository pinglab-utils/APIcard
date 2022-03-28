## Project: Using Multiple Omics Databases to Find Novel Gene Targets in Mendelian
Diseases

#### Explored by: 

```HU, RAN```,```NGO, KATHIE J```,```WANG, YE```-```(Bioinformatics 201, Winter-2022, UCLA)```


### Description: 

#### Task: 

Given a mendelian disease (i.e. hemophilia), find known genes associated with
the disease (i.e. OMIM, Online Mendelian Inheritance in Man). Use the gene list to
find sequence information (i.e. UCSC Genome Browser) or determine relevant
biological pathways through Gene Ontology (GO) enrichment analysis or find protein
complexes (i.e. UniProt) that could be potential drug targets. Find a list of drugs that
target these genes/proteins (i.e. DrugBank) and verify they are treatments for the
disease of interest.

#### Background:

Starting with a genetic/mendelian disease of interest, we use OMIM to
find a list of known genes or genes associated with the disease of interest. We want
to see which genes are existing drug targets for the disease of interest. By looking at
sequence data, enriched pathways, and protein complexes, we want to find novel
gene candidates for therapeutic drug targets.

#### Goal:

Find candidate genes associated with disease that are currently not drug
targets.

#### Methods:

1. Genetic Disease/Phenotype Interest: Use the OMIM API to perform a
disease/phenotypic keyword search (i.e. hemophilia) to obtain a list of known
genes associated with disease or phenotype of interest. 
2. DNA/cDNA sequence: Use the gene list as input for the UCSC Genome
Browser API to get the DNA/cDNA sequences that can be drug targets.
3. Biological Pathway/Protein Domain: Use the gene list as input for the GO
Resource API to find enriched biological processes associated with disease.
Use the gene list as input into the Uniprot API to find protein complexes that
can be drug targets.
4. Drugs: Use the DrugBank API to find a list of drugs and their gene targets for
the disease of interest. This will identify existing drugs for treatment and
genes that are targets of such drugs.
5. Novel Candidate Genes: Using the information from the previous steps, we
can find potential gene candidates that are associated with the disease of
interest and can be future drug targets of interest for disease treatment.

#### Expected outcome:

A list of genes/proteins that are associated with disease and
currently not targeted for treatment. These genes/proteins can be used for future
therapeutic research. Future directions include looking at protein-protein interactions
as additional candidates for targeted gene therapy.