# Sloane Lab BM Parser

This repository contains the parser that is used to import data from the [British Museum](https://www.britishmuseum.org/collection) into the [Sloane Lab](http://sloanelab.org/) knowledge base.

The main code of the parser is in the Jupyter notebook [BM_CSV_to_RDF](https://github.com/sloanelab-org/bm-parser/blob/main/BM_CSV_to_RDF.ipynb). The following libraries are required:

* [Pandas](https://pandas.pydata.org/), to manipulate and analyse the data
* [RDFlib](http://rdflib.readthedocs.io), to create the RDF graph

The original data from the British Museum is stored in the [data/bm](https://github.com/sloanelab-org/bm-parser/tree/main/data/bm) directory, and includes a single datasets with 15,000+ records that have been ingested into the Sloane Lab Knowledge Base.
