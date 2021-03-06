
##### Rationale

[Cellosaurus](http://web.expasy.org/cellosaurus/) is a knowledge resource on cell lines. It attempts to describe all cell lines used in biomedical research.

![Cellosaurus](data/projects/images/cellosaurus.jpg)

Cellosaurus is available on ExPASy at [http://web.expasy.org/cellosaurus/](http://web.expasy.org/cellosaurus/).
Textual description of its content: [http://web.expasy.org/cellosaurus/description.html](http://web.expasy.org/cellosaurus/description.html)

##### Approach

Two enhancements should be carried out concerning [Cellosaurus](http://web.expasy.org/cellosaurus/):

-	Development of a Web-based tool to compare a user entered short tandem repeart (STR) Marker profile for a cell line with all the STR marker data stored in the Cellosaurus. The program would run an algorithm similar to that described in [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3772516/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3772516/)

-	 Development of a Wikidata [bot](https://www.wikidata.org/wiki/Wikidata:Bots) to enter some of the data stored in the Cellosaurus into [Wikidata](wikidata.org). The exact specification of the mapping of Cellosaurus data into Wikidata properties/clains and statements is being finalized. The bot would be run at every release of the Cellosaurus to update the existing Wikidata cell line concepts and create new ones for cell lines newly entered at each release.

##### Challenges

- The content and structure of the Cellosaurus: both projects can be carried out using as a source file the XML version of the Cellosaurus   described in the XSD file: ftp://ftp.expasy.org/databases/cellosaurus/cellosaurus.xsd 


##### Requirements

- The student must have read the publication and understood the algorithm.
- Basic knowledge of Wikidata
