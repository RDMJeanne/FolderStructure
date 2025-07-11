2025-07-08

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15835125.svg)](https://doi.org/10.5281/zenodo.15835125)

# PhD Project Folder Template for the Life Sciences

This repository contains 

1. A template folder structure for PhD work in the life/natural sciences, a one-stop-shop for an organised approach.
2. A collection of all the lower-level templates (zipped folder structures and READMEs)
3. A collection of all lower-level guidance READMEs
4. Illustrative figures (folder map and the four steps to create a folder structure)

## TL;DR

This folder structure helps to stay organized during thesis and research. It contains many tips and recommendations.

* **Download the "PhD.zip"** file and unzip it to your desired location. 
* **Review the guidance** (G\_\*\_READMEs) to understand the purpose and best practices for each folder. (For quick access, find the [collection of Guidance_READMEs](https://github.com/RDMJeanne/FolderStructure/tree/main/Guidance_READMEs))
* **Add your files** to the structure (adjust to your needs if necessary) 
* **Edit the metadata templates** (M\_\*\_READMEs) to document your metadata as you progress.


## Aim

This folder structure is intended to support individual **research data management practices** related to your PhD. Your PhD may comprise multiple projects, experiments, and / or methods, which is mirrored in the structure. Researchers from other disciplines and stages are also very welcome to use and adapt the template according to their needs.
Additionally, we attempted to include as much **best practice and advice** as possible **implicitly and explicitly** to help you stay organised during your journey. If you would like to read more about research data management best practices, please have a look at the section **[References for RDM](#references)**. For easy-to-read and easy-to-write experience we use [Markdown](https://daringfireball.net/projects/markdown/) (\*.md) files enriching plain text documents with some formatting syntax. 

The folder structure aims to be:

* comprehensive
* self-explanatory
* supporting best practices with templates and guidance
* modular & flexible

Each folder in the structure contains a **guide G\_\*\_README.md** that explains what this folder is about and the recommended use. Additionally, folders can hold a **metadata M\_\*\_README.md** that is ready to be filled with your **own metadata**, as appropriate for the respective folder. 

You will probably not need all of the provided parts and maybe need something else in addition. Feel **free to modify** the structure to your needs, once you copied it to your working station. Accordingly, we intend this folder structure to be a working example.


## Features

1. Template folder **structure** for a PhD project in the life sciences (**PhD.zip**)
	* Folder and file **naming schemes** following best practices
	* **Guide G\_\*\_READMEs** with explanations and tips, how the structure is intended to be used and how to implement best practices at the respective level
	* **Metadata M\_\*\_READMEs** ready for your input of metadata. These try to capture as many options as possible, thus working as a reminder on which metadata to collect where. Additionally, you can use them as templates for more folders or in other contexts (e.g., in an ELN).
	* **zzz folders**: The suggested place for files that are older version, but not ready to be deleted. When the project ends, you can delete these folders, since you probably did not look into them again.
	* **zzz-ext folder**: For incoming files from collaborators that do not fit your naming conventions. When you use an incoming file, make a copy, change the name, and document that you did this.

2. Collection of all the lower-level **templates** (zipped subfolder structures and metadata templates)
	* Allows to quickly set up a standardised folder for your next project / experiment / presentation, etc.
	* Can be used outside of our large folder structure
	* Prompts the collection of relevant metadata

3. Collection of best practice **recommendations**
	* The recommendations are distributed onto guidance READMEs embedded in the structure. 


## Structure

### Schemes 

Most folders are labelled with the following scheme:
* ##\_\<CONTENT\>, 
	* where ## is a left-padded index used to sort the folders according to importance / work flow, 
	* and \<CONTENT\> is a single word indicating the content.

The READMEs follow this scheme:
* \<TYPE\>\_\<CONTENT\>\_README.md,
	* where \<TYPE\> is either resolved to G for Guidance or M for Metadata, 
	* and \<CONTENT\> is a single word indicating the content of the folder it resides in.

Few folders are either named with the scheme
* \<YYYY\>_TITLE, 
	* where the \<YYYY\> is supposed to be resolved to an actual year, 
	* and \<TITLE\> designates the course content.

Another scheme is this:
* \<YYYY-MM-DD\>\_\<CONTENT\>, 
	* where \<YYYY-MM-DD\> is supposed to be resolved to the relevant date in [ISO 8601](https://www.iso.org/obp/ui/en/#iso:std:iso:8601:-1:ed-1:v1:en:term:3.1.3.1) format with YYYY as year, MM as month, and DD as day.

Experiment can also mean method / test / hypthesis / small work package for you.

### Parts

The "PhD.zip" file / the folder structure is structured into 5 parts:

| Part         		| Purpose / Content   |
|--------------		|-----------|
| 1. Documents 		| Where all the documents go that you collect or need at this high level.      |
| 2. Projects  		| Where the research happens (apart from reviewing literature) |
| 3. Presentations 	| Presentations of slides and posters are prepared here |
| 4. Publications 	| Paper writing and figure composition |
| 5. Thesis 		| Thesis writing and figure composition |

#### Folder templates and READMEs

* **Zipped folder templates** are provided for substructures that we anticipate to be recreated frequently.
* **Guidance G\_\<CONTENT\>\_README.md**  will provide some advice what to do and how to organize yourself of the appropriate content \<CONTENT\>
* **Metadata M\_\<CONTENT\>\_README.md** are descriptive files written also in Markdown, but structured similar to the [15 Dublin Core elements](https://www.dublincore.org/resources/metadata-basics/) providing minimal information about your project/folder/files and will allow further machine-processing for linked data, see [Section Parsing M_README.md to M_README.json](#parsing-m_readmemd-to-m_readmejson).

### Templates

Embedded in this folder structure, at the appropriate places, you can find **zipped template folders** and **metadata M\_\*\_READMEs** for you to adapt, adopt, and fill in. 

Most relevant:

| Zipped Template Folder                                                           | Purpose / Content                                                                                               | Where (short)                                                                        |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [YYYY-MM-DD_ExperimentX.zip](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX.zip) | Folder structure for a new experiment / method. Incl. folders for protocols, data, code, results.               | [PhD/02_Projects/03_ProjectX/](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX.zip) |
| [00_ProjectX.zip](PhD/02_Projects/00_ProjectX.zip)                               | Folder structure for a new project. Incl. ExperimentX subfolder.                                                | [PhD/02_Projects/](PhD/02_Projects/00_ProjectX.zip)                                  |
| [YYYY-MM-DD_PresentationPosterTalk.zip](PhD/03_Presentations/YYYY-MM-DD_PresentationPosterTalk.zip)  | Folder structure for a new presentation / poster. Incl. figures, other resources, and archive (zzz) subfolders. | [PhD/03_Presentations](PhD/03_Presentations/YYYY-MM-DD_PresentationPosterTalk.zip)             |
| [ManuscriptX.zip](PhD/04_Publications/ManuscriptX.zip)                                                               | Folder structure for a new manuscript. Incl. figures, drafts, final subfolders                                  | [PhD/04_Publications/](PhD/04_Publications/ManuscriptX.zip)                                                                 |

For quick access, you can also locate them on this project page in the [Templates folder](https://github.com/RDMJeanne/FolderStructure/tree/main/Templates).


#### Guidance READMEs

Guidance READMEs are denoted with a "G_" starting the file name. They provide and overview of their respective folder, best practices, further information, and references on the topic.

| Guidance README                                                                                         | Purpose / Content                                                    |
| ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [G_PhD_README](/PhD/G_PhD_README.md)                                                                    | The **main** guidance README of your project as entry point, including general best practices.         |
| [G_Documents_README](/PhD/01_Documents/G_Documents_README.md)                                           | Explains the administrative documents folder.                               |
| [G_DMP_README](/PhD/01_Documents/02_Administrative/01_DMP/G_DMP_README.md)                               | Information on Data Management Plans.                        |
| [G_Projects_README](/PhD/02_Projects/G_Projects_README.md)                                              | Tips on projects, documentation, and tidy data.                           |
| [G_Protocols_README](/PhD/02_Projects/01_Protocols/G_Protocols_README.md)                               | Pointers about the documentation of lab work, including ontologies, resource IDs and ELNs.                  |
| [G_Code_README](/PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/03_Code/G_Code_README.md)        | Recommendations on source code development.                    |
| [G_Presentations_README](/PhD/03_Presentations/G_Presentations_README.md)                               | Considerations about talk/posters and credit.                     |
| [G_Publications_README](/PhD/04_Publications/G_Publications_README.md)                                  | Recommendations on publishing papers, authorship, and licensing.                |
| [G_ManuscriptFigures_README](/PhD/04_Publications/ManuscriptX/01_Figures/G_ManuscriptFigures_README.md) | Pointers regarding creating and publishing figures in manuscripts, incl. captions. |
| [G_Thesis_README](/PhD/05_Thesis/G_Thesis_README.md)                                                    | Considerations about writing the thesis.                             |
| [G_Thesis_Figures_README](/PhD/05_Thesis/01_Figures/G_Thesis_Figures_README.md)                           | Similar to ManuscriptFigures but with thesis specific tips.      |

For quick access, you can also locate them on this project page in the [Guidance_READMEs folder](https://github.com/RDMJeanne/FolderStructure/tree/main/Guidance_READMEs).


#### Metadata READMEs

Metadata READMEs are denoted with a "M_" starting the file name. They are used to provide mostly descriptive, administrative and legal information.

| Metadata README                                                                                                                                                                                  | Purpose / Content                                                                                       | Where (short)                                                                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [M_ProjectX_README.md](PhD/02_Projects/03_ProjectX/M_ProjectX_README.md)                                                                                                                         | Copy and fill in information on individual projects.                                                    | [PhD/02_Projects/03_ProjectX](PhD/02_Projects/03_ProjectX/M_ProjectX_README.md)                                                                                                                                                                                                            |
| [M_ExperimentX_README.md](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/M_ExperimentX_README.md)                                                                                              | Copy and fill in information on individual experiments / methods.                                       | [PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/M_ExperimentX_README.md)                                                                                                                                                              |
| [M_Data_README.md](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/02_Data/M_Data_README.md) [M_Data_README.md](PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/02_Data/M_Data_README.md) | Copy and fill in information on individual data sets.                                                   | [PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/02_Data/](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/02_Data/M_Data_README.md) [PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/02_Data/](PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/02_Data/M_Data_README.md)    |
| [M_Code_README.md](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/03_Code/M_Code_README.md)<br>[M_Code_README.md](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/03_Code/M_Code_README.md)   | Copy and fill in information on individual source code.                                                 | [PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/03_Code/](PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/03_Code/M_Code_README.md)<br>[PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/03_Code/](PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/03_Code/M_Code_README.md) |
| [M_PARTNER_projectX_README.md](PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/M_PARTNER_project_README.md)                                                                                 | Copy and fill in information on projects by collaboration partners.                                     | [PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/](PhD/02_Projects/02_Collaborations/01_PARTNER_ProjectX/)                                                                                                                                                |
| [M_Presentation_Metadata.md](PhD/03_Presentations/M_Presentation-Metadata.md)                                                                                                                                                                       | Copy and fill in information on individual presentations (e.g., for upload on Zenodo)                   | [PhD/03_Presentations/](PhD/03_Presentations)                                                                                                                                                                                                                                                                       |
| [M_Fig1A_README.md](PhD/04_Publications/ManuscriptX/01_Figures/Fig1A/M_Fig1A_README.md)  [M_Fig1_README.md](PhD/05_Thesis/01_Figures/Fig1/M_Fig1_README.md)                                      | Copy and fill in information on figures used in publications (e.g. Manuscripts or Thesis)               | [PhD/04_Publications/ManuscriptX/01_Figures/Fig1A/](PhD/04_Publications/ManuscriptX/01_Figures/Fig1A/M_Fig1A_README.md)  [PhD/05_Thesis/01_Figures/Fig1/](PhD/05_Thesis/01_Figures/Fig1/M_Fig1_README.md)                                                                                  |
| [M_SFigX_README.md](PhD/04_Publications/ManuscriptX/01_Figures/SFigX/M_SFigX_README.md)                                                                                                          | Copy and fill in information on supplementary figures used in publications (e.g. Manuscripts or Thesis) | [PhD/04_Publications/ManuscriptX/01_Figures/SFigX/](PhD/04_Publications/ManuscriptX/01_Figures/SFigX/M_SFigX_README.md)  
| [M_PhD_README.md](PhD/M_PhD_README.md)																			| Fill in administrative metadata regarding your PhD.         						   | [PhD/](PhD/M_PhD_README.md)	
| [M_NamingSchemes.md](PhD/M_NamingSchemes.md)																			| Record the naming schemes you add to the ones we already noted here.					| [PhD/](PhD/M_NamingSchemes.md)	

For quick access, you can also locate them on this project page in the [Templates folder](https://github.com/RDMJeanne/FolderStructure/tree/main/Templates).

### Parsing M_README.md to M_README.json

We recommend to provide as much metadata information as possible to find and understand your data in your project tree. Therefore, this repository also contains dedicated M\_\<CONTENT\>\_README.md files based on the [Dublin Core keywords](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/). To enhance machine-interoperability along with a folder structure, we provide a simplistic parser to convert the Markdown to JSON files for further data processing, e.g., to create a database catalog for your files or to provide additional metadata in public repository. The parser and further documentation can be found on [Zenodo.org](https://doi.org/10.5281/zenodo.14942696) with the source code available on [github](https://github.com/Bondoki/ParsingMetadataMD2JSON). 

The following keywords will be parsed and converted:

| Keyword                                                                                                                      | Description                                                                                                                                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Title](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/title)             | Descriptive name the Paper/Project/Thesis/Dataset                                                                                                                                                                                       |
| [Creator](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/creator)         | A consecutive list of names, who created the resource and is primarily responsible.                                                                                                                                                     |
| [Creator.ORCID](https://support.orcid.org/hc/en-us/articles/360006897674-Structure-of-the-ORCID-Identifier)                  | Additional information: The ORCID identifier of the Creator.                                                                                                                                                                            |
| [Creator.Email](https://schema.org/email)                                                                                    | Additional information: The email identifier of the Creator.                                                                                                                                                                            |
| [Publisher](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/publisher)     | The department/institute responsible for making the resource available.                                                                                                                                                                 |
| [Contributor](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/contributor) | A consecutive list of names, contributed to the resource and is secondary to Creators.                                                                                                                                                  |
| [Contributor.ORCID](https://support.orcid.org/hc/en-us/articles/360006897674-Structure-of-the-ORCID-Identifier)              | Additional information: The ORCID identifier of the Contributor.                                                                                                                                                                        |
| [Contributor.Email](https://schema.org/email)                                                                                | Additional information: The email identifier of the Contributor.                                                                                                                                                                        |
| [Description](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/description) | A textual description of the content of the resource.                                                                                                                                                                                   |
| [Subject](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/subject)         | Phrase\Keywords describing the content of the resource.                                                                                                                                                                                 |
| [Date](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/date)               | A date associated with the creation or availability of the resource. Recommended format: YYYY-MM-DD.                                                                                                                                    |
| [Language](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/language)       | The language of the resource recommended as [BCP 47 language tag](https://doi.org/10.17487/RFC5646).                                                                                                                                    |
| [Format](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/format)           | The data format to identify the software and possibly hardware that might be needed to display or operate the resource. For a list of MIME types see [here](https://www.iana.org/assignments/media-types/media-types.xhtml).            |
| [Type](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/type)               | The category of the resource e.g. Collection, Dataset, Event, Image, Experiment, Simulation, Report, Text, Draft, Image. See also [DCMI Type Vocabulary](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#section-7/). |
| [Coverage](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/coverage)       | Temporal coverage is typically a period for acquiring the data.                                                                                                                                                                         |
| [Source](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/source)           | Information about a second resource from which the present resource is derived - if applicable.                                                                                                                                         |
| [Relation](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/relation)       | Provide a relationship from source to the present resource, e.g. IsVersionOf, IsReplacedBy, IsPartOf, IsReferencedBy, see [Qualified Dublin Core Terms](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/).             |
| [Identifier](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/identifier)   | An unique identifier of the resource, e.g. DOI, ISBN, Number                                                                                                                                                                            |
| [Method](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/MethodOfAccrual)         | Refer to your (post-)processing tools/methods, e.g. URL or git hash, as relation.                                                                                                                                                       |
| [Rights](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/elements/1.1/rights)           | A rights management statement of the resource, e.g. license for publishing and sharing.                                                                                                                                                 |


### Folder Structure Overview

Imagine to flip open the folder tree, this is the structure you will find within:

```
PhD/
├── G_PhD_README.md
├── 01_Documents/
│   ├── 01_Personal/
│   ├── 02_Administrative/
│   │   ├── 01_DMP/
│   │   │   ├── 01_Policies/
│   │   │   ├── 02_Examples/
│   │   │   └── G_DMP_README.md
│   │   └── 02_Grants/
│   ├── 03_Notes/
│   ├── 04_Literature/
│   ├── 05_Courses/
│   │   ├── YYYY_TITLE/
│   └── G_Documents_README.md
├── 02_Projects/
│   ├── 01_Protocols/
│   │   └── G_Protocols_README.md.md
│   ├── 02_Collaborations/
│   │   ├── Collab_Overview.md
│   │   ├── 01_PARTNER_project/
│   │   │   ├── 01_Protocols/
│   │   │   ├── 02_Data/
│   │   │   │   ├── 01_Raw/
│   │   │   │   ├── 02_Processed/
│   │   │   │   └── M_Data_README.md
│   │   │   ├── 03_Code/
│   │   │   │   ├── G_Code_README.md
|   |   |   |   └── M_Code_README.md
│   │   │   ├── 04_Results/
│   │   │   └── M_PARTNER_ProjectX_README.md
│   │   ├── 00_PARTNER_ProjectX.zip
│   │   └── zzz_from-joe/
│   ├── 03_ProjectX/
│   │   ├── YYYY-MM-DD_ExperimentX/
│   │   │   ├── 01_Protocols/
│   │   │   ├── 02_Data/
│   │   │   │   ├── 01_Raw/
│   │   │   │   ├── 02_Processed/
│   │   │   │   └── M_Data_README.md
│   │   │   ├── 03_Code/
│   │   │   │   ├── G_Code_README.md
|   |   |   |   └── M_Code_README.md
│   │   │   ├── 04_Results/
│   │   │   └── M_ExperimentX_README.md
│   │   ├── YYYY-MM-DD_ExperimentX.zip
│   │   └── M_ProjextX_README.md
│   ├── G_Projects_README.md
│   └── 00_ProjectX.zip
├── 03_Presentations/
│   ├── 01_LabMeetings/
│   │   └── YYYY-MM-DD_Presentation/
│   │       ├── 01_Figures/
│   │       ├── 02_OtherResources/
│   │       └── zzz/
│   ├── 02_Conferences/
│   │   ├── YYYY-MM-DD_Poster/
│   │   │   ├── 01_Figures/
│   │   │   ├── 02_OtherResources/
│   │   │   └── zzz/
│   │   └── YYYY-MM-DD_Talk/
│   │       ├── 01_Figures/
│   │       ├── 02_OtherResources/
│   │       └── zzz/
│   ├── 03_Retreats/
│   ├── 04_Illustrations/
│   │   ├── 01_ThirdParty/
│   │   └── 02_SelfCreated/
│   ├── G_Presentations_README.md
│   ├── M_Presentation_Metadata.md
│   └── YYYY-MM-DD_PresentationPosterTalk.zip
├── 04_Publications/
│   ├── ManuscriptX/
│   │   ├── 01_Figures/
│   │   │   ├── Fig1A/
│   │   │   │   ├── Code/
│   │   │   │   ├── Data/
│   │   │   │   ├── Fig1A_Caption.txt
│   │   │   │   └── M_Fig1A_README.md
│   │   │   ├── SFigX/
│   │   │   │   ├── Code/
│   │   │   │   ├── Data/
│   │   │   │   ├── SFigX_Caption.txt
│   │   │   │   └── M_SFigX_README.md
│   │   │   ├── zzz/
│   │   │   ├── FigX.zip
│   │   │   └── G_ManuscriptFigures_README.md
│   │   ├── 02_Drafts/
│   │   │   └── zzz/
│   │   ├── 03_Submitted/
│   │   ├── 04_Revision/
│   │   ├── 05_Published/
│   │   └── ManuscriptX_DataOverview.xlsx
│   ├── G_Publications_README.md
│   └── ManuscriptX.zip
├── 05_Thesis/
│   ├── 01_Figures/
│   │   ├── Fig1/
│   │   │   ├── Code/
│   │   │   ├── Data/
│   │   │   ├── Fig1_Caption.txt
│   │   │   └── M_Fig1_README.md
│   │   ├── zzz/
│   │   ├── G_ThesisFigures_README.md
│   │   └── FigX.zip
│   ├── 02_Drafts/
│   │   └── zzz/
│   ├── 03_Submitted/
│   ├── 04_Revised/
│   ├── 05_Published/
│   ├── 06_Defense/
│   └── G_Thesis_README.md
├── misc/
├── M_PhD_README.md
└── M_NamingSchemes.md
```

(Tree was generated with [https://www.text-tree-generator.com/](https://www.text-tree-generator.com/))

## Using the PhD.zip and other templates

Follow these steps to get started with the complete or parts of the provided folder structure for your PhD.

### 1. Download

To download an individual .zip file from GitHub, click the button `Download raw file` and allow your browser to do its thing (see also screenshot below).

<img width="150" alt="Download button" src="https://github.com/user-attachments/assets/32892431-92a5-4568-b92a-728baea945ef"/>


You can also download the whole repository by clicking `Code` and then `Download .zip`. This will pack all files in another container.

### 2. Unzip

Once you retrieved your desired .zip file from your download folder, move it to the place where you want to have your new folder. Unzip by doubleclicking, or selecting unzip/uncompress from the right-click menu.

### 3. Review structure and guides

We recommend that you familiarize yourself with the structure and guides.
The guidance READMEs (denoted with "G_") are there to inform you about the purpose and best practices regarding the respective folder. 

### 4. Adjust to your needs

Potentially you can already adjust the structure to your needs, for example renaming "Experiment" to "Test" in a more bioinformatical environment. 

### 5. Add your files

As you progress through your PhD, add files to your structure. Remember to document and collect all metadata you can, e.g., in the READMEs, and to adjust the structure if necessary.

### 6. Edit READMEs

All metadata READMEs (denoted with "M_") are there to capture your own metadata, and thus wait for you to fill them. One natural starting point is the [M_PhD_README](/PhD/M_PhD_README.md).

### 7. Cite

If you would like to acknowledge this project, you can cite it. See below (How to cite).




## References

### For this structure
* Seibold H (2022) Research Project Template. GitHub Repository. [https://github.com/HeidiSeibold/research-project-template](https://github.com/HeidiSeibold/research-project-template)
* Colomb J, Arendt T, Sehara K, and The Gin-Tonic team (2021) “Towards a Standardized Research Folder Structure.” Generation Research. [https://doi.org/10.25815/WCY6-M233](https://doi.org/10.25815/WCY6-M233). Project website: [https://gin-tonic.netlify.app/standard/](https://gin-tonic.netlify.app/standard/)

### Research Data Management (RDM) Starters and Best Practices
* The Research Data Management toolkit for Life Sciences: [https://rdmkit.elixir-europe.org/](https://rdmkit.elixir-europe.org/)
* The Research Data Management Workbook: [https://caltechlibrary.github.io/RDMworkbook/](https://caltechlibrary.github.io/RDMworkbook/)
* Data Management Expert Guide: [https://dmeg.cessda.eu/](https://dmeg.cessda.eu/ ) 
* Briney KA (2020) File Naming Convention Worksheet. [https://doi.org/10.7907/894Q-ZR22](https://doi.org/10.7907/894Q-ZR22).

Please refer to our other guidance READMEs for more resources and recommended reads.
  
____
## This Project

* Git address: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)
* Paper DOI

### Contributors

#### Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>)

#### Ron Dockhorn (<a href="https://orcid.org/0000-0002-5268-5430"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-5268-5430</a>)

#### Jeanne Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>)


### Feedback

* Is very welcome! Just create a new [issue](https://github.com/RDMJeanne/FolderStructure/issues)!
* As are use cases - show us how you use it!

### How to cite

This project is licensed under [CC0 v1.0 Universal](https://github.com/RDMJeanne/FolderStructure/blob/main/LICENSE) and made public available free of charge. The project can be distributed, used, or modified in any way without acknowledgement of the original authors. If you find the resource useful and need citation in academic context, please use the following:  
* Files / Project: Demerdash Y, Dockhorn R, Wilbrandt J (YEAR) **PhD Project Folder Template for the Life Sciences**. Zenodo, DOI:
* Paper: Demerdash Y, Dockhorn R, Wilbrandt J (YEAR) **Data Organization Made Easy: Comprehensive Folder Structure Template for Early Career Life/Natural Science Researchers**. *Journal*, DOI:



