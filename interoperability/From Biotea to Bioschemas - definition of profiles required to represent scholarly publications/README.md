# From Biotea to Bioschemas: definition of profiles required to represent scholarly publications

### Representative: Alexander Garcia

## Community
---

Bioschemas, BioHackathon Japan

## Leads
---
Alexander Garcia  
Olga Giraldo  
Federico Lopez  
Leyla Garcia  
Dietrich Rebholz-Schuhmann

## Background information
---
Biotea [1] provides a way to model biomedical scholarly publications in RDF, taking into account metadata, references, content and biomedical annotations. Bioschemas provides a simple way to add structured data to web pages. Mapping Biotea to Bioschemas represents an opportunity to easily add a semantic layer to publications, making them FAIRer and more machine-consumable. Having scholarly data in Bioschemas opens up possibilities for smarter recommendation systems and literature-based knowledge graphs and discovery.

## Expected outcomes
---

* Draft specification for scholarly publication Bioschemas profiles such as Journal, ScholarlyArticle and Author 
* Brainstorm on how to integrate the Biotea annotations model to Bioschemas 
* Story cases on how such data can be consumed and integrated to existing tools (e.g., [2])

## Expected audience
---

People interested in scholarly publications, Bioschemas, structured data, natural language processing.
**Expected hacking days**: 4 days

## Related works and references
---

1. [Biotea: semantics for PubMed central](https://peerj.com/articles/4201/) 
2. [Biotea model mapping to schema.org/Bioschemas](https://drive.google.com/drive/folders/1AYKXrowHpsF9cstn0FeJhpbgfi9T_MeC)
3. [Bioschemas](http://bioschemas.org/) 
4. [schema.org](https://schema.org/) 

## GitHub or any other public repositories of your FOSS products (if any)
---

[Biotea repository](https://github.com/biotea)

## Tasks
---
1. Revise publication repositories currently including schema.org markup to see what elements they are marking up
2. Find suitable types on schema.org (in addition to those already in use)
3. [Biotea model mapping to schema.org/Bioschemas](https://drive.google.com/drive/folders/1AYKXrowHpsF9cstn0FeJhpbgfi9T_MeC)
4. [Define draft profile specifications](./profiles/readme.md)
5. Get feedback on specifications (Please use the GitHub issues with the label biotea2bioschemas)

## Skills
---
* Knowledge/interest on structured metadata for scholarly publications
* Knowledge/interest on [Biotea](https://peerj.com/articles/4201/)
* Knowledge/interest on [Bioschemas](http://bioschemas.org/)

## How to participate
---
* Have a look to the [Biotea model and mapping to Bioschemas](https://drive.google.com/drive/folders/1AYKXrowHpsF9cstn0FeJhpbgfi9T_MeC)
* Go to the [profiles folder](./profiles/readme.md)
* Select the ones you want to contribute to
* download and fill the templates with your proposal for minimum, recommended and optional properties, cardinality and any controlled vocabulary
* Upload them to the corresponding profile folder named as name-lastName-profile.xlsx
* Any comments or so you want to share, please do so via GitHub issues using the label "project: biotea2bioschemas"

Thanks for your collaboration!
