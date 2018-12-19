---
name: "LoCloud_bglink"
nemoactivitytypes: "enriching"
developers: "LoCloud"
projectwebsite: "http://www.locloud.eu/"
coderepository: "https://github.com/ixa-ehu/locloud_bglink"
qualityofdocumentation: 
easeofadaptation: 
codequality: 
license: "Apache v 2.0"
examples: 
lastrelease: 
lastactivity: 11/26/2014
categories: [Contextualisation, Linked Open Data]
---
Background link service for LoCloud

This repository contains the background link service module developed
within the LoCloud project. The module consists of a PHP script that
implements a REST service, calls DBpedia
Spotlight
for the actual processing, and wraps the answer into a suitable
format.

The background link service uses DBpedia Spotlight as a backbone for
performing the linking. In principle, the service can be used in any
language, the only requirement being that a DBpedia spotlight instance for
this particular language is running.
