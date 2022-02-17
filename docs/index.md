
# API Card


Welcome to API card collection!

We have created a collection of API cards to explore and integrate Bioinformatics databases. It is prepared together with students in **BioInfo 201-Winter, 2022, UCLA** class, conducted by **Pinglab UCLA**, as their class project. The main aim of this collection is to let students be familiar with available bioinformatics resources and learn to implement their APIs to interact and integrate multiple resources to design a data accessing pipeline to assist a research studies in multi-omics integration.

Each API card document is prepared by a group of students which includes:

- Title
- Description
- Use Cases
- Tutorials

## A Sample API Card

Following is a sample API card prepared by us on Uniprot API. We encourage students to follow the similar pattern and add more information (e.g., cheat sheet, citations, supporting papers) if needed and available.

-----------

### Title: UniProt Web API

#### Description: 

UniProt is a protein knowledge base which provides information on proteins, including their sequences, their biological function, and other properties, curated from their references in the biomedical literature. Uniprot can be accessed directly at
[uniprot.org](https://www.uniprot.org/) and instructions to the API are detailed at [online API document](https://www.uniprot.org/help/programmatic_access).



#### Use cases:

- Retrieve individual or batch entries of proteins of interest (e.g., the text representation of a protein entry, parsable by a custom script, given at [a text file](https://uniprot.org/uniprot/P12345.txt)

- Convert database identifiers (e.g., If a collaborator gave you protein IDs from another
knowledgebase such as STRING DB but your software uses UniProt IDs. You want your
software to convert these to UniProt so you can run your analysis properly. You can use
UniProt’s web API described here to convert these IDs.)


#### Tutorial: 

We encourage students to create a Google Colab jupyter notebook as a tutorial with necessary code to illustrate the use of API with some tasks. Here we provide a smaple tutorial for Uniprot API.

[Tutorial on Uniprot API in Goole Colab is available here](colab.research.google.com/drive/1gblX7Sv-z54VcuIPQ88pQ0OT9DgRkQu_?usp=sharing)


---------

Brought to you by **Ping Lab Utils (GitHub), UCLA, 2022**