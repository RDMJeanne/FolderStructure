2024-12-10


# Guide README of 'Protocols' folder

## Structure and Scheme

In here you find the following parts / folders:

```
01_Protocols/
└── G_Protocols_README.md

```

Feel free to adapt this structure to your specific needs and workflow.


## Best Practice Recommendations

### Documentation with ELN and templates

An Electronic Lab Notebook (ELN) is software tool that aims to replace traditional lab notebooks on paper. ELNs offer space to note hypotheses, experiment setups, observations, and everything else required to **document your wetlab work**.

Using an ELN has several advantages over a paperwise lab notebook, e.g.,
* no handwriting illegibility issues
* full text search
* linking to data, files, and images, as well as external resources is possible withouzt media break
* data security through backups
* complete audit trail
* collaboration

At its basis, an ELN provides you a **blank page** that you can edit as you see fit. For notes that are always taken in a similar way (e.g., repeating an experiment with changed parameters; crafting a standard buffer) it is recommended to create / use **templates and/or forms**. Often, these are provided by the ELN, shared by your colleagues, or can be found online (see below).

**More information:**
- Adam & Lindstädt (2021). **ELN Guide: Electronic laboratory notebooks in the context of research data management and good research practice – a guide for the life sciences**. ZBMed. [https://doi.org/10.4126/FRL01-006425772](https://doi.org/10.4126/FRL01-006425772)
* How to keep a lab notebook, best practices: [https://research.columbia.edu/sites/default/files/content/RCT%20content/ReaDI%20Program/tutorial_LabNotebook_V9.pdf](https://research.columbia.edu/sites/default/files/content/RCT%20content/ReaDI%20Program/tutorial_LabNotebook_V9.pdf), [https://oir.nih.gov/system/files/media/file/2021-08/presentation-scientific_recordkeeping-april2014.pdf](https://oir.nih.gov/system/files/media/file/2021-08/presentation-scientific_recordkeeping-april2014.pdf) 
* Web-service comparing ELNs: [https://eln-finder.ulb.tu-darmstadt.de/home](https://eln-finder.ulb.tu-darmstadt.de/home)


### Terminology, ontologies, and tags

Whenever you use words to identify an organism, a disease, a chemical, or whatever else requires description, it is a good idea to use a standard term. This helps to increase findability (everyone looks for the same word instead of 5 different versions) and reusability (everyone knows what the topic is and can decide accordingly whether to use your data).

Standard terms are collected in **terminologies**, and if the resource also records the relationships between the terms, it is called an **ontology**. There are several ontologies in use within the life sciences. They encompass different areas of terms and share more or less overlap with each other. 

Here are some examples:
* Chemical Entities of Biological Interest (ChEBI) [https://www.ebi.ac.uk/chebi/aboutChebiForward.do](https://www.ebi.ac.uk/chebi/aboutChebiForward.do) 
* Cell Ontology (CL) [https://cell-ontology.github.io/](https://cell-ontology.github.io/) 
* Disease Ontology (DO) [https://disease-ontology.org/ ](https://disease-ontology.org/ )
* Protein Ontology (PRO) [https://obofoundry.org/ontology/pr.html ](https://obofoundry.org/ontology/pr.html)
* Gene Ontology (GO) [https://www.geneontology.org/ ](https://www.geneontology.org/ )
* Biological Imaging Methods Ontology (FBbi) [https://bioportal.bioontology.org/ontologies/FBbi ](https://bioportal.bioontology.org/ontologies/FBbi )
* Open Microscopy Environment Ontology (OME-OWL) [https://biokeanos.com/source/Open%20Microscopy%20Environment%20Ontology](https://biokeanos.com/source/Open%20Microscopy%20Environment%20Ontology) 
:
More ontologies: EMBL-EBI Ontology Lookup Service [https://www.ebi.ac.uk/ols4](https://www.ebi.ac.uk/ols4)

When **tagging** your protocols, notes, and data, it is a good idea to use standardized vocabulary. Ideally, you log in your metadata the ID of the used term as well as the ID of the resource (ontology / etc) it stems from to allow unambiguous identification and automatic mapping.


**More information:** 
- [https://rdmkit.elixir-europe.org/metadata_management#how-do-you-find-appropriate-vocabularies-or-ontologies](https://rdmkit.elixir-europe.org/metadata_management#how-do-you-find-appropriate-vocabularies-or-ontologies)
- https://terminology.tib.eu/ts/


### Publishing and reusing protocols

Since writing, testing, and revising protocols for wetlab work is scientific work, it makes sense to publish the result to make the effort visible. Conversely, one can save time by using an already existing protocol, if it is published and well enough documented.

One **platform** that allows publication including a permanent globally unique identifier (a DOI, in this case), is [protocols.io](https://www.protocols.io/). Depending on your ELN, there might an interface that allows direct import and export of protocols. 

**More information:** 
* Complete, interactive, citable protocols. [https://becker.wustl.edu/news/how-to-make-your-protocols-complete-interactive-and-citable/](https://becker.wustl.edu/news/how-to-make-your-protocols-complete-interactive-and-citable/)
* How to write a protocol. [https://www.theneuron.ai/write/work-document/protocol](https://www.theneuron.ai/write/work-document/protocol)
* Weissgerber (2023). **Structuring a step-by-step, reusable protocol**. [https://osf.io/dyu5f](https://osf.io/dyu5f)

### Identifying resources

Material and methods sections as well as ELN entries / protocols usually **name the resources and chemicals**, but it happens often enough that the information is not / no longer sufficient to unambiguously identify the resource. This is especially relevant in study replications.

Similar to using standard terms with IDs to tag ELN entries and much more, using a resource **identifier** that links with a permanent ID to a database with ample information is a good idea. One such database is the Resource Identification Portal ([https://rrid.site/](https://rrid.site/)), which harbours identifiers and corresponding information (e.g., supplier) for plasmids, cells, organisms, tools and other resources, biosamples, and antibodies.

**More information:** 
- Bandrowski & Martone (2016). **RRIDs: A Simple Step toward Improving Reproducibility through Rigor and Transparency of Experimental Methods**. NeuroView 90(3). [https://doi.org/10.1016/j.neuron.2016.04.030](https://doi.org/10.1016/j.neuron.2016.04.030)


## Further Reading

* McMurry et al. (2017). **Identifiers for the 21st century: How to design, provision, and reuse persistent identifiers to maximize utility and impact of life science data.** PLoS Biol 15(6): e2001414. [https://doi.org/10.1371/journal.pbio.2001414](https://doi.org/10.1371/journal.pbio.2001414)
* Macleod et al. (2021). **The MDAR (Materials Design Analysis Reporting) Framework for transparent reporting in the life sciences**. PNAS 118 (17)e2103238118. [https://doi.org/10.1073/pnas.2103238118](https://doi.org/10.1073/pnas.2103238118)

_____

This file is part of the PhD Folder Structure project by Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>) & Jeanne  Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>) & Ron Dockhorn (<a href="https://orcid.org/0000-0002-5268-5430"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-5268-5430</a>).

* git: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)

