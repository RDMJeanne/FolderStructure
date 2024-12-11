2024-12-11

# Guide README of 'PhD' folder

## Structure and Scheme

In here you find the following parts / folders:

```
PhD/
├── 01_Documents/
├── 02_Projects/
├── 03_Presentations/
├── 04_Publications/
├── 05_Thesis/
├── G_PhD_README.md
├── M_NamingSchemes.md
└── M_PhD_README.md
```


| Part             | Purpose / Content                                                                                                                                 | README                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 1. Documents     | Where all the documents go that you collect or need at this high level. This includes administrative, notes, literature, and course-related docs. | [G_Documents_README](/PhD/01_Documents/G_Documents_README.md)             |
| 2. Projects      | Where the research happens (apart from reviewing literature), i.e., the place for data, analyses, code, protocols, etc.                           | [G_Projects_README](/PhD/02_Projects/G_Projects_README.md)                |
| 3. Presentations | Presentations of slides and posters are prepared here.                                                                                            | [G_Presentations_README](/PhD/03_Presentations/G_Presentations_README.md) |
| 4. Publications  | Paper writing and figure composition as well as preparation of all other to-be-published content.                                                 | [G_Publications_README](/PhD/04_Publications/G_Publications_README.md)    |
| 5. Thesis        | Thesis writing and figure composition.                                                                                                            | [G_Thesis_README](/PhD/05_Thesis/G_Thesis_README.md)                      |

A full overview of the contained folders and files can be found in the topmost [README](/README.md). 
For more detailed information on folder contents and according best practices, have a look at the respective guide G\_\<CONTENT\>\_README.md. Also, provide as much metadata as possible in the respective M\_\<CONTENT\>\_README.md starting with [M_PhD_README](/PhD/M_PhD_README.md).  

Feel free to adapt the suggested folder structure to your specific needs and workflow.


## Best Practice Recommendations

### File and Folder Naming

Make sure to label your files and folders with meaningful names. Names should be:
* short / concise
* descriptive
* specific
* consistently used
* human- & machine-readable
* consisting only of alphanumeric characters (no special characters like parentheses, umlauts, colons, spaces, whitespaces etc.)
* abbreviations should be documented in a dictionary

If you include a **date**, make sure to follow [ISO 8601](https://www.iso.org/obp/ui/en/#iso:std:iso:8601:-1:ed-1:v1:en:term:3.1.3.1), i.e., year first, then month, then day: YYYY-MM-DD or YYYYMMDD ensuring chronological sorting.

If you include any **numbers** (e.g., as an ID), consider left-padding / leading zeroes, i.e. start numbering with 001 if you expect up to 999 files.

As an alternative/complementary **approach** to file and folder naming, you can consider the "Johnny Decimal" system of structuring files in folders: [https://johnnydecimal.com/](https://johnnydecimal.com/)

**More information**:
* [https://dmeg.cessda.eu/Data-Management-Expert-Guide/2.-Organise-Document/File-naming-and-folder-structure](https://dmeg.cessda.eu/Data-Management-Expert-Guide/2.-Organise-Document/File-naming-and-folder-structure)


### Get an ORCID <img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png"/>

As a researcher, it is best practice (and increasingly demanded by publishers) to have an ORCID. This "Open Researcher and Contributor ID"  brings three main benefits: 
* The ID remains persistent if you change your affiliation, mail address, or even name.
* Your ORCID website lists your publications (automatically collected via DataCite) and you can add your CV and more information. 
* The ORCID login can be used for many research-related websites.

**More information**:
* [https://orcid.org/](https://orcid.org/)


### Backups

First, find out about the backup provisions of your employer. Often there is a server space for research with regular backups. Depending on the security level of data to be stored there, you need to worry less about backups.

A good backup strategy (also if you have to implement it yourself) follows the 3-2-1 rule:
* Have at least **3 copies** of each file
* Have at least **2** of your three copies **on different storage media** (e.g., an external drive and a server)
* Have at least **1** of your three copies **in a physically different location** / building (geo-redundancy).

**More information**:
* [https://dmeg.cessda.eu/Data-Management-Expert-Guide/4.-Store/Backup](https://dmeg.cessda.eu/Data-Management-Expert-Guide/4.-Store/Backup)

### Data Management Plan

The ideal project start also comes with the start of a data management plan (DMP). While you obviously cannot know all the details yet, it can be very helpful to find a suitable template and fill in as much information as possible. 
Note that a DMP can serve as one way of documenting your RDM measures, like file naming schemes, etc.
Throughout your progress, revisit the plan often for guidance and to update it when your data management strategies change.

**More information**:
* [https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Adapt-your-DMP-Part-1](https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Adapt-your-DMP-Part-1)
* Practical Guide to [...] RDM—Extended Ed. (incl. DMP criteria): [https://doi.org/10.5281/zenodo.4915861](https://doi.org/10.5281/zenodo.4915861) 



## Further Reading

For your PhD work, we recommend the following books:
* Turabian, Kate L. (2018), Booth, Wayne C.; Colomb, Gregory G.; Williams, Joseph M.; Bizup, Joseph; FitzGerald, William T.; University of Chicago Press Editorial Staff (eds.), **A Manual for Writers of Research Papers, Theses, and Dissertations** (9th ed.), Chicago: University of Chicago Press, ISBN 978-0226430577. Website: [https://www.chicagomanualofstyle.org/turabian.html](https://www.chicagomanualofstyle.org/turabian.html)
* Strunk, William Jr.; White, E. B. (2009). **The Elements of Style** (5th ed.). Boston: Allyn and Bacon. p. xiii. ISBN 978-0-205-31342-6. Website: [https://en.wikipedia.org/wiki/The_Elements_of_Style](https://en.wikipedia.org/wiki/The_Elements_of_Style)
* Bolker, Joan. (1998) **Writing Your Dissertation in Fifteen Minutes a Day: A Guide to Starting, Revising, and Finishing Your Doctoral Thesis**. First Edition. New York: Owl Books.

On scientific rigor:
*  Prager et al. **Improving transparency and scientific rigor in academic publishing**. J Neuro Res. 2019; 97: 377–390. [https://doi.org/10.1002/jnr.24340 ](https://doi.org/10.1002/jnr.24340 )


_____

This file is part of the PhD Folder Structure project by Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>) & Jeanne  Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>) & Ron Dockhorn (<a href="https://orcid.org/0000-0002-5268-5430"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-5268-5430</a>).

* git: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)

