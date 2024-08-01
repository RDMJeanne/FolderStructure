2024-05-07


# Guide README of 'Projects' folder

## Structure and Scheme

In here you find the following parts / folders:

```
02_Projects/
├── 01_Protocols/
├── 02_Collaborations/
│   ├── Collab_Overview.md
│   ├── 01_PARTNER_project/
│   │   ├── 01_Protocols/
│   │   ├── 02_Data/
│   │   │   ├── 01_Raw/
│   │   │   ├── 02_Processed/
│   │   │   └── M_Data_README.md
│   │   ├── 03_Code/
│   │   ├── 04_Results/
│   │   └── M_PARTNER_project_README.md
│   ├── 00_PARTNER_project.zip
│   └── zzz_from-joe/
├── 03_ProjectX/
│   ├── M_ProjextX_README.md
│   ├── YYYY-MM-DD_ExperimentX/
│   │   ├── 01_Protocols/
│   │   ├── 02_Data/
│   │   │   ├── 01_Raw/
│   │   │   ├── 02_Processed/
│   │   │   └── M_Data_README.md
│   │   ├── 03_Code/
│   │   ├── 04_Results/
│   │   └── M_ExperimentX_README.md
│   └── YYYY-MM-DD_ExperimentX.zip
├── G_Project_README.md
└── 00_ProjectX.zip

```


| Part         		| Purpose / Content   |
|--------------		|-----------|
| 1. Protocols 		| Standard operating procedures (SOPs) of your working group / lab, recipes of ingredients, handling guidelines, and other documented directions on experimental procedures that apply to more than one project. |
| 2. Collaborations  		| Not all projects will be carried out by you alone, either you work with other people's data or others work with your's. Next to a collaboration overview file, you can store sfilies in a similar order as in the following projectX folder |
| 3. ProjectX 	| Following the "one project, one folder" idea, this folder can be created anew for every new project. It contains a metadata template for background information and subfolders for specific protocols, for raw and processed data accompanied by another READMe template, for code, and for results. |

Feel free to adapt this structure to your specific needs and workflow.


## Best Practice Recommendations

### Documentation & Metadata

Metadata (data on data) is required to understand and (re)use data. Collecting this metadata in an easily retirevable form by suitable documentation methods is crucial for research.

Minimum metadata as suggested by the **Dublin Core** standard ([https://www.dublincore.org/specifications/dublin-core/dcmi-terms/](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/)) can be created with this editor: [https://nsteffel.github.io/dublin_core_generator/generator_nq.html#publisher](https://nsteffel.github.io/dublin_core_generator/generator_nq.html#publisher)

Two documentation levels can be distinguished (taken from and detailed in [https://dmeg.cessda.eu/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata](https://dmeg.cessda.eu/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata)):
* **Project-level documentation** deals with:
	* Purpose of data creation (project background information)
	* Dataset content
	* Collection / creation method and further information
	* Data processing method(s)
	* Data modifications
	* Quality assurance methods
	* Access
* **Data-level documentation** covers:
	* Data file information
	* Information on variables in the files

There are several documentation **methods** that can be suitable to use depending on the to-be-recorded metadata, discipline-/lab-specific standards, and personal preference.
The most common are (more information: [https://datamanagement.hms.harvard.edu/collect-analyze/documentation-metadata](https://datamanagement.hms.harvard.edu/collect-analyze/documentation-metadata)):
* READMEs (How-to: [https://zenodo.org/doi/10.5281/zenodo.10648863](https://zenodo.org/doi/10.5281/zenodo.10648863))
* Codebooks / Data Dictionaries (How-to: [https://ddialliance.org/training/getting-started-new-content/create-a-codebook](https://ddialliance.org/training/getting-started-new-content/create-a-codebook))
* Electronic Lab Notebooks (ELNs)

When working with code / software, log files can help with automated documentation.

Although often seen as pure formalitiy for grant proposals, **Data Management Plans** (DMPs)can also serve as a central documentation hub. Further information: [https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Adapt-your-DMP-Part-1](https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Adapt-your-DMP-Part-1) 

It is recommended to use established **metadata standards** / schemas whereever possible. More information: [https://fairsharing.org/](https://fairsharing.org/). This ensures that all (minimally) relevant metadata is captured.

Additionally, to ensure seamless communication / reduce potential confusion, it is recommneded to write metadata with standardized terms. Collections of these are called **terminologies**, or **ontologies** if they also hold relationships between terms. A comprehensive database is here: [https://terminology.tib.eu/ts](https://terminology.tib.eu/ts)
 When using such terms, it is good practice to also give its ID and the source terminology
- Title: Term
- TermID: id123
- TermSource: Terminology URL


### Tidy Data in Spreadsheets

2-dimensional tabular data is best represented in spreadsheets. Making such data available also for the future (in term of long-term archiving) can require conversion to a text-based format like .csv or .tsv.
Together with demands of processing and understandability, this calls for making the data rectangular and applying of the tidy data principles:
* One column for one variable
* One row for one observation
* One cell per value

More information:
* Broman KW & Woo KH (2018) Data Organization in Spreadsheets, The American Statistician, 72:1, 2-10 [https://doi.org/10.1080/00031305.2017.1375989](https://doi.org/10.1080/00031305.2017.1375989)
* Grolemund G & Wickham H. 2017. R for Data Science. O’Reilly Media. [https://r4ds.had.co.nz](https://r4ds.had.co.nz)

### Protocols and Research Resource Identifiers

When describing **experimental procedures** it may be helpful to check whether an appropriate protocol is already publicly avilable - or if not, it is a good idea to publish your own (receiving a DOI and a citable research output). The most relevant **repository** for protocols, checklists, workflows, and similar in the life science is [https://www.protocols.io/](https://www.protocols.io/). Some ELNs provide an interface for quick implementation and adaption of published protocols.

When describing used **ingredients**, or when listing used **resources**, **cell lines**, **plasmids**, or **antibodies**, researchers often resort to naming the supplier and the provider-internal ID. This can be inaccurate and not helpful in identifying the exact reagent or mutation line. It is strongly recommended to use persistent unique identifiers also for these objects (like a DOI for publications), the most comprehensive **database** being the **Research Resource Identification Portal** [https://rrid.site/](https://rrid.site/). If a resource is not available there yet, acquiring an ID is straightforward and fast.


### Code on GitHub: Get a DOI from Zenodo

**Writing software** / code / scripts for research is a whole realm of best practices on its own. As a **first pointer** in this direction, please refer to this article: Wilson et al. (2014) Best Practices for Scientific Computing. PLoS Biol 12(1): e1001745. [https://doi.org/10.1371/journal.pbio.1001745](https://doi.org/10.1371/journal.pbio.1001745)

When you have written your code and published a narrative paper describing or using it, it is strongly recommended to **provide** not only a URL link to the code repository (e.g., a simple github link), but to acquire and transmit a **permanent identifier, i.e. a DOI**. The generalistic repository Zenodo ([https://zenodo.org/](https://zenodo.org/)) allows to receive DOIs for github repositories: [https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content
](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)

## Further Reading

### Project Management
* Levin & Levin (2019) Managing Ideas, People, and Projects: Organizational Tools and Strategies for Researchers. iScience. 20:278-291. [https://doi.org/10.1016%2Fj.isci.2019.09.017](https://doi.org/10.1016%2Fj.isci.2019.09.017).
* Commonwealth Scholarship Commission in the UK (CSC)(2021) Research Project Management: Project management principles and practical tips. PDF [https://cscuk.fcdo.gov.uk/wp-content/uploads/2021/09/Research-project-management-full-slides.pdf](https://cscuk.fcdo.gov.uk/wp-content/uploads/2021/09/Research-project-management-full-slides.pdf)

_____

This file is part of the PhD Folder Structure project by Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>) & Jeanne  Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>)

* git: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)
* DOI: 

