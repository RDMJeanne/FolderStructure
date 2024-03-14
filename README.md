# PhD Project Folder Template for the Life Sciences

This repository contains 

1. A template folder structure for a PhD project in the life sciences, a one-stop-shop for an organised approach.
2. A collection of all the lower-level templates (zipped folder structures and READMEs)

## Aim

This folder structure is intended to support individual research data management related to your PhD. Your PhD may comprise multiple projects, experiments, and / or methods, which is mirrored in the structure. 
Additionally, we attempted to include as much best practice and advice implicitly and explicitly to help you stay organised during your journey. If you would like to read more about research data management best practices, please have a look at section Ref-RDM.

* comprehensive
* self-explanatory
* supporting best practices with templates and guidance
* modular & flexible

Each folder in the structure contains a guide README that explains what this folder is about and the recommended use. Additionally, each folder holds a README that is ready to be filled with your own metadata, as appropriate for the respective folder.

Naturally, you will not need all of the provided parts and maybe need something else in addition. Feel free to modify the structure to your needs, once you copied it to your working station (see section X).

## Structure

Most folders are labelled with the following scheme:
    ##_CONTENT, where ## is a left-padded index used to sort the folders according to importance / work flow, and CONTENT is a single word indicating the content.
Few folders are either named with the scheme
    YYYY_Year#, where the Y's are supposed to be resolved to an actual year, with the # as the year count relative to starting the PhD.
Another scheme is this:
    YYYY-MM-DD_CONTENT, where YYYY-MM-DD is supposed to be resolved to the relevant date in ISO 8601 format.

Experiment can also mean method for you.

The "FolderStructure.zip" file is structured into 5 parts:
| Part         | Purpose / Content   |
|--------------|-----------|
| 1. Documents | Where all the documents go that you collect or need at this high level.      |
| 2. Projects  | Where the research happens (apart from reviewing literature) |
| 3. Presentations | Presentations of slides and posters are prepared here |
| 4. Manuscripts | Paper writing and figure composition |
| 5. Thesis | Thesis writing and figure composition |	
		

Imagine to flip open the folder tree, this is the structure you will find within:

```
PhD/
   ├── README.txt			<- 	

   ├── 01_Documents/			<- 
   │   └── 01_Personal/			<- 
   │   └── 02_Administrative/		<- 
   │   │   └── 01_DMP/			<- 
   │   │   │   └── 01_Policies/ 	<- 
   │   │   │   └── 02_Examples/ 	<- 
   │   │   │   └── DMP_README.txt 	<- 
   │   │   └── 02_Grants/ 		<- 
   │   └── 03_Literature/ 		<- 
   │   │   └── ReadPaperTemplate.pdf	<-   ------------------------------------------ new
   │   │   └── ReadPaper_README.txt	<-   ------------------------------------------ new
   │   └── 04_Courses/ 			<- 
   │   │   └── YYY1/ 			<- 
   │   │   └── YYY2/ 			<- 
   │   └── Documents_README.txt 	<- 

   ├── 02_Projects/			<- 
   │   ├── 01_Protocols/ 		<- 
   │   └── Collaborations/ 		<- 
   │   │   └── zzz_from-joe/ 		<- 
   │   └── ProjextX/			<- 
   │   │   └── YYYYMMDD_ExperimentX/ 	<- 
   │   │   │   └── 01_Protocols/ 	<- 
   │   │   │   └── 02_Data/ 		<- 
   │   │   │   │   └── 01_Raw/ 		<- 
   │   │   │   │   └── 02_Processed/ 	<- 
   │   │   │   │   └── Data_README.txt 	<- ------------------------------------------ new
   │   │   │   └── 03_Code/ 		<- add best practice cheat sheet? Like, how to comment...
   │   │   │   └── 04_Results/ 		<- 
   │   │   │   └── ExperimentX_README.txt <- 
   │   │   └── ExperimentX.zip 		<-  ------------------------------------------ new
   │   │   └── ProjextX_README/ 	<- 
   │   └── ProjextX.zip  		<-  ------------------------------------------ new
   │   └── Project_README.txt 		<- 

   ├── 03_Presentations/		<- 
   │   ├── 01_LabMeetings/  		<-  
   │   │   └── YYYY-MM-DD_Presentation/ <- 
   │   │   │   └── 01_Figures/ 		<- 
   │   │   │   └── 02_OtherResources/ 	<- 
   │   │   │   └── zzz/ 		<- 
   │   │   │   └── Presentation_Metadata.txt <- -------------------------------------- Zenodo template
   │   └── 02_Conferences/ 		<- 
   │   │   └── YYYY-MM-DD_Poster/ 	<- 
   │   │   │   └── 01_Figures/ 		<- 
   │   │   │   └── 02_OtherResources/ 	<- 
   │   │   │   └── zzz/ 		<- 
   │   │   │   └── Presentation_Metadata.txt <- -------------------------------------- Zenodo template
   │   └── 03_Retreats/    		<-
   │   └── 04_Illustrations/   		<- 
   │   │   └── 01_Foreign/ 		<- 
   │   │   └── 02_Own/ 			<- 
   │   └── YYYY-MM-DD_Presentation.zip 	<-    ------------------------------------------ new
   │   └── Presentations_README.txt	<- 

   ├── 04_Manuscripts/			<- 
   │   ├── ManuscriptX/			<- 
   │   │   └──01_Figures/ 		<- 
   │   │   │   └── 01_Main/ 		<- 
   │   │   │   └── 02_Supplementary/ 	<- 
   │   │   └──02_Drafts/		<- 
   │   │   │   └── zzz/  		<- 
   │   │   └──03_Final/ 		<- 
   │   ├── ManuscriptX.zip 		<-  ------------------------------------------ new
   │   ├── HowToWriteNatureAbstracts.pdf <-   ------------------------------------------ new
   │   ├── Manuscript_README.txt 	<- 

   ├── 05_Thesis/			<- 
   │   ├── 01_Figures/			<- 
   │   ├── 02_Drafts/			<- 
   │   │   └──zzz/ 			<- 
   │   ├── 03_Final/			<- 
   │   └── 04_Defense/			<- 
   │   └── zzz/				<- 
   └── misc				<-             miscellaneous files that don't fit elsewhere ??
```

## Using the PhD.zip template

### Download

### Unzip

### Edit READMEs

### Adjust to your needs

### Add your files


## Using other templates

### Download

### Unzip

### Edit READMEs

### Adjust to your needs



















## References

### For this structure
https://github.com/HeidiSeibold/research-project-template

### Research Data Management (RDM) Starters and Best Practices


## This Project

Git address

### Contributers

#### Yasmin

#### Jeanne







