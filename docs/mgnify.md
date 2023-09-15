

## MGnify

Explored by: Mira Abrecht 
 
![img](img/mgnify.png)

### Description. 
MGnify is a database aggregating information from microbial metagenomic studies  of environmental and biological samples. It contains study metadata, metagenomes,  metatranscriptomes, and metabarcodes, as well as the individual genomes and contigs of  identified species. The MGnify homepage can be accessed via this [link](https://www.ebi.ac.uk/metagenomics). 

MGnify has both general documentation of API functions, as well as further documentation about the API’s resource types and schema. MGnify also has an [API browser](https://www.ebi.ac.uk/metagenomics/api/v1/) that allows users to  physically click through API parameters and generate queries via an internet browser. 

### Tutorial. 
[MGnify_API_tutorial](https://colab.research.google.com/drive/1x8wq6u4SNAM9llRLkj-t36UOay8tnLUP?usp=sharing)

Use cases. 

1. Retrieve a list of taxa found in a particular biome 
2. Retrieve a genome of a particular taxa  

Task 2. Integrating Multiple Omics Databases 
Task. Determine which bacterial species found in the human gut 
microbiome are resistant to  antibiotics. 

### Background. 

The human gut contains a diverse community of commensal bacteria that helps  maintain both intestinal and general health. Antibiotics taken to resolve pathogenic bacterial  infections may unintentionally disrupt this system by killing beneficial bacteria. Given this, you  want to know which species in the human gut are resistant, rather than susceptible, to antibiotics.  This can be done by checking which species found in the human gut microbiome (MGnify)  contain specialty genes coding for antibiotic resistance (BV-BRC). 

#### Goal. 

Identify bacterial species found in the human gut microbiome that contain genes coding  for antibiotic resistance. 

### Method. 

1. Species list. Use MGnify API to return a list of bacterial species identified from the  metagenome of the human gut.  
2. Resistant bacteria. Query BV-BRC API for bacteria from the MGnify list that contain  specialty genes with the property “Antibiotic Resistance.” 

#### Expected outcome:

 A list of bacteria found in the human gut microbiome that contain specialty  genes with the property “Antibiotic Resistance.”
