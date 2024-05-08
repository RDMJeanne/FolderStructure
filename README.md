2024-05-07

# PhD Project Folder Template for the Life Sciences

This repository contains 

1. A template folder structure for a PhD project in the life sciences, a one-stop-shop for an organised approach.
2. A collection of all the lower-level templates (zipped folder structures and READMEs)

## Aim

This folder structure is intended to support individual **research data management related** to your PhD. Your PhD may comprise multiple projects, experiments, and / or methods, which is mirrored in the structure. 
Additionally, we attempted to include as much **best practice and advice** as possible **implicitly and explicitly** to help you stay organised during your journey. If you would like to read more about research data management best practices, please have a look at section **Ref-RDM**.

The folder structure aims to be:

* comprehensive
* self-explanatory
* supporting best practices with templates and guidance
* modular & flexible

Each folder in the structure contains a **guide README** that explains what this folder is about and the recommended use. Additionally, folders can hold a **README** that is ready to be filled with your **own metadata**, as appropriate for the respective folder.

Naturally, you will not need all of the provided parts and maybe need something else in addition. Feel **free to modify** the structure to your needs, once you copied it to your working station (see section X). Accordingly, we intend this folder structure to be a working example.


## Features

1. Template folder **structure** for a PhD project in the life sciences (**PhD.zip**)
	* Folder and file **naming schemes** following best practices
	* **Guide READMEs** with explanations and tips, how the structure is intended to be used and how to implement best practices at the respective level
	* **Metadata READMEs** ready for your input of metadata. These try to capture as many options as possible, thus working as a reminder on which metadata to collect where. Additionally, you can use them as templates for more folders or in other contexts (e.g., in an ELN).
	* **HowTos** as a starting point for your scientific reading and writing journey.
	* **zzz folders**: The suggested place for files that are older version, but are not ready to be deleted. When the project ends, you can delete these folders, since you probably did not look into them again.
	* **zzz-from-joe folder**: For incoming files from collaborators that do not fit your naming conventions. When you use an incoming file, make a copy, change the name, and document that you did this.

2. Collection of all the lower-level **templates**
	* Allows to quickly set up a standardised folder for your next project / experiment / presentation, etc.
	* Can be used outside of our large folder structure

3. Collection of Best Practice **Recommendations**
	* The recommendations are distributed onto guide READMEs embedded in the structure. 
	* Additionally, a collection file serves as overview for quick reference.


## Structure

### Schemes 

Most folders are labelled with the following scheme:
* ##_\<CONTENT\>, 
	* where ## is a left-padded index used to sort the folders according to importance / work flow, 
	* and \<CONTENT\> is a single word indicating the content.

The READMEs follow this scheme:
* \<TYPE\>_\<CONTENT\>_README,
	* where \<TYPE\> is either resolved to G for Guidance or M for Metadata, 
	* and \<CONTENT\> is a single word indicating the content of the folder it resides in.

Few folders are either named with the scheme
* \<YYYY\>_Year#, 
	* where the \<YYYY\> is supposed to be resolved to an actual year, 
	* with the # as the year count relative to starting the PhD.

Another scheme is this:
* \<YYYY-MM-DD\>_\<CONTENT\>, 
	* where \<YYYY-MM-DD\> is supposed to be resolved to the relevant date in ISO 8601 format.

Experiment can also mean method for you.

### Parts

The "PhD.zip" file is structured into 5 parts:

| Part         		| Purpose / Content   |
|--------------		|-----------|
| 1. Documents 		| Where all the documents go that you collect or need at this high level.      |
| 2. Projects  		| Where the research happens (apart from reviewing literature) |
| 3. Presentations 	| Presentations of slides and posters are prepared here |
| 4. Manuscripts 	| Paper writing and figure composition |
| 5. Thesis 		| Thesis writing and figure composition |	

### Templates

Embedded in this folder structure, at the appropriate places, you can find **zipped template folders**; **metadata READMEs** for you to adapt, adopt, and fill in; and **How-Tos**. 

| Zipped Template Folder    			| Purpose / Content 	| Where (short) |
| -------- 			| ------- 			| ------- |
| ExperimentX.zip 		| Folder structure for a new experiment / method. Incl. folders for protocols, data, code, results.| PhD/02/ProjectX/  |
| ProjextX.zip    		| Folder structure for a new project. Incl. ExperimentX subfolder.			| PhD/02/  |
| YYYY-MM-DD_Presentation.zip 	| Folder structure for a new presentation / poster. Incl. figures, other resources, and archive (zzz) subfolders.  | PhD/03/ |
| ManuscriptX.zip  		| Folder structure for a new manuscript. Incl. figures, drafts, final subfolders  |  PhD/04/ |

Metadata READMEs are denoted with an "M_" starting the file name (guide REAMDEs start with "G_").

| Metadata README 			| Purpose / Content 	| Where (short) |
| -------- 			| ------- 			| ------- |
| M_ProjextX_README.md  	| Copy and fill in information on individual projects. | PhD/02/ProjextX/  |
| M_ExperimentX_README.md  	| Copy and fill in information on individual experiments / methods. | PhD/02/ProjextX/DATE/  |
| M_Data_README.md  	| Copy and fill in information on individual data sets. | PhD/02/ProjextX/DATE/02/  |
| M_Presentation_Metadata.md  	| Copy and fill in information on individual presentations (e.g., for upload on Zenodo) | PhD/03/  |

Three essential HowTos are provided. For the references, check the according section below.

| How-to   			| Purpose / Content 	| Where (short) |
| -------- 			| ------- 			| ------- |
| ReadPaperTemplate.pdf  	| Structured paper reading. | PhD/01/03/  |
| HowToWriteNatureAbstracts.pdf	| Illustrates components and advice on writing a paper abstract.  | PhD/04/ |
| HowToWriteFigureCaptions.pdf	| Some best practice tips and examples on scientific figure caption writing.  | PhD/04/ |


These files are also provided **separately** from the large structure in the **Templates folder** of this git repository.

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
│   │   ├── ReadPaperTemplate.pdf
│   │   └── ReadPaper_README.md
│   ├── 05_Courses/
│   │   ├── YYYY_Year1/
│   │   └── YYYY_Year2/
│   └── G_Documents_README.md
├── 02_Projects/
│   ├── 01_Protocols/
│   │   └── G_Protocols_README.md
│   ├── Collaborations/
│   │   └── zzz_from-joe/
│   ├── ProjextX/
│   │   ├── YYYY-MM-DD_ExperimentX/
│   │   │   ├── 01_Protocols/
│   │   │   ├── 02_Data/
│   │   │   │   ├── 01_Raw/
│   │   │   │   ├── 02_Processed/
│   │   │   │   └── M_Data_README.md
│   │   │   ├── 03_Code/
│   │   │   │   └── G_Code_README.md
│   │   │   ├── 04_Results/
│   │   │   └── M_ExperimentX_README.md
│   │   └── ExperimentX.zip
│   ├── G_Project_README.md
│   ├── M_ProjextX_README.md
│   └── ProjextX.zip
├── 03_Presentations/
│   ├── 01_LabMeetings/
│   │   └── YYYY-MM-DD_Presentation/
│   │       ├── 01_Figures/
│   │       ├── 02_OtherResources/
│   │       └── zzz/
│   ├── 02_Conferences/
│   │   └── YYYY-MM-DD_Poster/
│   │       ├── 01_Figures/
│   │       ├── 02_OtherResources/
│   │       └── zzz/
│   ├── 03_Retreats/
│   ├── 04_Illustrations/
│   │   ├── 01_Foreign/
│   │   └── 02_Own/
│   ├── G_Presentations_README.md
│   ├── M_Presentation_Metadata.md
│   └── YYYY-MM-DD_Presentation.zip
├── 04_Manuscripts/
│   ├── ManuscriptX/
│   │   ├── 01_Figures/
│   │   │   ├── 01_Main/
│   │   │   └── 02_Supplementary/
│   │   ├── 02_Drafts/
│   │   │   └── zzz/
│   │   ├── 03_Final/
│   │   └── 04_Revision/
│   ├── G_Manuscript_README.md
│   ├── HowToWriteFigureCaptions.pdf
│   ├── HowToWriteNatureAbstracts.pdf
│   └── ManuscriptX.zip
├── 05_Thesis/
│   ├── 01_Figures/
│   ├── 02_Drafts/
│   │   └── zzz/
│   ├── 03_Final/
│   ├── 04_Defense/
│   └── G_Thesis_README.md
└── misc
```

(Tree was generated with [https://www.text-tree-generator.com/](https://www.text-tree-generator.com/))

## Using the PhD.zip and other templates

Follow these steps to get started with the complete or parts of the provided folder structure for your PhD.

### 1. Download

To download an individual .zip file from GitHub, click the button `BUTTON` and allow your browser to do its thing (see also screenshot below).

You can also download the whole repository by clicking `Code` and then `Download .zip`. This will pack all files in another container.

### 2. Unzip

Once you retrieved your desired .zip file from your download folder, move it to the place where you want to have your new folder. Unzip by doubleclicking, or selecting unzip/uncompress from the right-click menu.

### 3. Review structure and guides

We recommend that you familiarize yourself with the structure and guides.
The guide READMEs (denoted with "G_") are there to inform you about the purpose and best practices regarding the respective folder. 

### 4. Adjust to your needs

Potentially you can already adjust the structure to your needs, for example renaming "Experiment" to "Test" in a more bioinformatical environment. 

### 5. Edit READMEs

All metadata READMEs (denoted with "M_") are there to capture your own metadata, and thus wait for you to fill them. One natural starting point is the M_PhD_README.md.

### 6. Add your files

As you progress through your PhD, add files to your structure. Remember to document and collect all metadata you can, e.g., in the READMEs, and to adjust the structure if necessary.

### 7. Cite

If you would like to achknowledge this project, you can cite as follows:




## References

### For this structure
* Seibold, Heidi (2022) Research Project Template. GitHub Repository. [https://github.com/HeidiSeibold/research-project-template](https://github.com/HeidiSeibold/research-project-template)
* Colomb, Julien, Thorsten Arendt, Keisuke Sehara, and The Gin-Tonic team. 2021. “Towards a Standardized Research Folder Structure.” Generation Research. [https://doi.org/10.25815/WCY6-M233](https://doi.org/10.25815/WCY6-M233). Project website: [https://gin-tonic.netlify.app/standard/](https://gin-tonic.netlify.app/standard/)

### Research Data Management (RDM) Starters and Best Practices
* File Naming: https://www.herox.com/dataworks/round/2873/entry/48095?from=admin&sort=date&name=&status=all

### For the HowTos
* ReadPaperTemplate:
* HowToWriteNatureAbstracts:
* HowToWriteFigureCaptions:


____
## This Project

* Git address: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)
* Paper DOI

### Contributers

#### Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>)

#### Jeanne Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>)


### Feedback

* Is very welcome!
* As are use cases - show us how you use it!





