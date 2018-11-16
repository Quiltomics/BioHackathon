# CWL support in Galaxy

### Representative: Hervé Ménager

## Community
---

ELIXIR Implementation Study: Enabling the reuse, extension, scaling, and reproducibility of scientific workflows

## Leads
---
- Hervé Ménager
- Michael R. Crusoe
- John Chilton 

## Background information
---
The field of bioinformatics has seen increasing use of the Common Workflow Language (CWL) to describe systematically the entirety of an informatics pipeline. Within the context of ELIXIR's Marine Metagenomics Use Case, various annotation pipelines are already described in CWL.  

The ongoing Workflow Implementation Study aims to demonstrate how such CWL tool descriptions can be reused, together with additional tool descriptions, to produce extended and new analysis workflows, namely the assembly and functional annotation of transcriptomes from isolated marine eukaryotes.  

Part of this implementation study is to contribute to the ongoing effort for the native support for CWL execution within Galaxy, using a experimental branch of Galaxy created by @jmchilton.

## Expected outcomes
---

Improved support for CWL in Galaxy, building on the initial work by the CWL Community and John Chilton for the Galaxy community. We will work on the current outstanding issues, which are listed in the following repositories:
* https://github.com/common-workflow-language/galaxy/issues
* https://github.com/hmenager/workflow-is-cwl/issues

## Expected audience
---

Software developers with either Python or Frontend development skills (especially Javascript), with or without an initial experience of development in Galaxy and/or CWL.
**Expected hacking days**: 4 days

## Related works and references
---

- [CWL website](http://commonwl.org)
- [Enabling the reuse, extension, scaling, and reproducibility of scientific workflows ELIXIR IS](https://www.elixir-europe.org/about-us/implementation-studies/cwl-2018)

## GitHub or any other public repositories of your FOSS products (if any)
---

- [CWL repository](http://github.com/common-workflow-language/common-workflow-language)
- [Galaxy project main repository](http://github.com/galaxyproject/galaxy)
- [Galaxy project CWL support repository](http://github.com/common-workflow-language/galaxy)

## Hackers
---

- [Nicola Soranzo](https://github.com/nsoranzo)
