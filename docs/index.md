
## API Card



API card to explore and integrate Bioinformatics databases. Prepared together with students in BioInfo 201-Winter, 2022, UCLA.

Each API card document includes 

- Title
- Description
- Use Cases
- Tutorials

## Sample API Card

### API: UniProt web API

#### Description: 

UniProt is a protein knowledge base which provides information on proteins, including their sequences, their biological function, and other properties, curated from their references in the biomedical literature. Uniprot can be accessed directly at
[uniprot.org](https://www.uniprot.org/) and instructions to the API are detailed at [online API document](https://www.uniprot.org/help/programmatic_access).



#### Use cases:

Retrieve individual or batch entries of proteins of interest (e.g., the text representation of a
protein entry, parsable by a custom script, given at [a text file](uniprot.org/uniprot/P12345.txt)

Convert database identifiers (e.g., If a collaborator gave you protein IDs from another
knowledgebase such as STRING DB but your software uses UniProt IDs. You want your
software to convert these to UniProt so you can run your analysis properly. You can use
UniProt’s web API described here to convert these IDs.)


#### Tutorial: 

[Tutorial on Uniprot API in Goole Colab is available here](colab.research.google.com/drive/1gblX7Sv-z54VcuIPQ88pQ0OT9DgRkQu_?usp=sharing)


---------

Brought to you by Ping Lab Utils (GitHub), UCLA, 2022