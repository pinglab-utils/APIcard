## DisGeNET

Explored by:


### Description: 
DisGeNET is a aggregative database of gene-disease, variant-disease, and disease-disease associations originally motivated by a desire for a comprehensive dataset for gene-disease modularity analyses. The primary advantage of DisGeNET over other similar association databases is its comprehensiveness and well-defined evidence scores. The developers collect associations from a variety of existing sources and with varying levels of certainty. These sources range from carefully validated databases such as UNIPROT and ClinGen to orthologous animal model databases such as MGD and automated text mining databases such as LHDGN and Clinvar. The collected associations are then integrated with an ad hoc type ontology, and their strengths are quantified with a series of metrics inherited from similar database efforts. When querying DisGeNET, one filters based on these organizational features and receives annotated lists of associations in TSV, JSON, or XML format. Python and R interfaces are available as well. 

[API documentation is available here](https://www.disgenet.org/api/). 

### Use Cases: 

Identify genetic correlations between diseases in user-specified gene/variant sets ● Recover common biological modules across a large number of diseases ● Validate disease-specific eQTLs by checking paired gene-disease and variant-disease associations (from universal sources) 

### Tutorial: 

https://colab.research.google.com/drive/1IeYpwigmcDQi7SPFjPcYiuzabc3rSnJf?usp=sharing
