---
name: "Europeanap-dbpedia-disambiguation"
nemoactivitytypes: "Named Entity Recognition"
developers: "KBNL Research"
projectwebsite: "https://github.com/KBNLresearch/europeananp-dbpedia-disambiguation"
coderepository: "https://github.com/KBNLresearch/europeananp-dbpedia-disambiguation"
qualityofdocumentation: 
easeofadaptation: 
codequality: 
license: 
examples: 
lastrelease: January 2015
lastactivity: 
categories: [Metadata Retrieval Services, Media Annotation/Tagging]
---
A simple Python library and webservice, that allows named entity disambiguation against a label database. The idea is to use a Solr query to filter possible candidates and use the more detailed analysis on string similarity, number of inlinks and entity type to select the "best" candidate. It contains code to handle (multi-lingual) DBpedia dumps and load them into a Solr backend. It also contains helper code for the annotation of ALTO 2.1 files that are used in the context of the Europeana Newspapers project.
