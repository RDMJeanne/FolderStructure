2024-12-11


# Guide README of 'Publications' folder

## Structure and Scheme

In here you find the following parts / folders:

```
04_Publications/
├── ManuscriptX/
│   ├── 01_Figures/
│   │   ├── Fig1A/
│   │   │   ├── Code/
│   │   │   ├── Data/
│   │   │   ├── Fig1A_Caption.txt
│   │   │   └── M_Fig1A_README.md
│   │   ├── SFigX/
│   │   │   ├── Code/
│   │   │   ├── Data/
│   │   │   ├── SFigX_Caption.txt
│   │   │   └── M_SFigX_README.md
│   │   ├── zzz/
│   │   ├── FigX.zip
│   │   └── G_ManuscriptFigures_README.md
│   ├── 02_Drafts/
│   │   └── zzz/
│   ├── 03_Submitted/
│   ├── 04_Revision/
│   ├── 05_Published/
│   └── ManuscriptX_DataOverview.xlsx
├── G_Publications_README.md
└── ManuscriptX.zip

```


| Part           | Purpose / Content                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. ManuscriptX | For each manuscript, make a new folder. You can use the ManuscriptX.zip template for it, it contains the same empty folder structure you see here.                                                                                                                                                                                                                                                                                                                                                                                                             |
| 1.1. Figures   | The place for the figures you (maybe) want to use in your manuscript. For each figure, is is a good idea to provide how and from which data it was generated, ideally not only as a note / link in the README, but directly in the figure folder. This way, recreating figures for specific manuscripts is much easier. Storing the intended caption extern to the figure also helps to stay organized. More information can be found in the guidance [G_ManuscriptFigures_README](/PhD/04_Publications/ManuscriptX/01_Figures/G_ManuscriptFigures_README.md). |
| 1.2. Drafts    | The place for the many versions of your manuscript draft. Keeping older versions helps to roll back to previous formulations and to prove who has written what at which point in time. To not clutter your work space too much, move obsolete versions to the *zzz* folder.                                                                                                                                                                                                                                                                                    |
| 1.3. Submitted | For each journal you submit to (if it is more than one), create a folder with exactly those files you are uploading. Adjust the file names to match the order of upload so it is less likely you overlook a file.                                                                                                                                                                                                                                                                                                                                              |
| 1.4. Revision  | Usually, revision is necessary, so here you can store the according correspondence and the updated manuscript. You will receive feedback from the editor and peer reviewers and most likely you will need to write a rebuttal letter. For a resubmission, consider to create a folder with the to-be-submitted files as in the prior step.                                                                                                                                                                                                                     |
| 1.5. Published | This is the place to store the published version in case it is not available online for some reason. Some publishers grant you only limited / timed access to your publication.                                                                                                                                                                                                                                                                                                                                                                                |

Feel free to adapt this structure to your specific needs and workflow.


## Best Practice Recommendations

### Authorship and Acknowledgements
Lack of transparency and unclear **communication** about who is doing what for a manuscript and for which kind of credit is often a problem leading to frustration and authorship disputes. Ideally, all contributing persons should talk as early as possible about authorship. This also helps to manage expectations on which work packages, actions, and how much effort is expected of the contributors. Authorship also comes with duties and **responsibilities** for the product and can also be declined.

When a contribution does not qualify for authorship, it is good practice to **acknowledge** it in the acknowledgement section of the manuscript. Note, however, that you should obtain written **consent** from people mentioned there first / before submission!

There are clear definitions on which **contributions justify authorship**. So-called honorary authorships infringe Good Research Practice.
* **CRediT** (Contributor Roles Taxonomy) (Website). Last accessed: 2024-03-19. [https://credit.niso.org/](https://credit.niso.org/)
* Harvard University **Guidelines on Authorship and Acknowledgement** (Website). Last accessed: 2024-03-19. https://research.fas.harvard.edu/links/guidelines-authorship-and-acknowledgement
* International Committee of Medical Journal Editors (ICMJE): **Defining the Role of Authors and Contributors** (Website). Last accessed: 2024-03-19. https://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html
* Albert and Wager (2003). **How to handle authorship disputes: a guide for new researchers.** The COPE Report 2003. [https://publicationethics.org/files/u2/2003pdf12.pdf](https://publicationethics.org/files/u2/2003pdf12.pdf)


### Open Access Publication
Publishing results and data under open access helps you to comply with increasingly stringent **funding requirements** and to contribute to more **collaborative and transparent science**. 
We recommend to prioritize open access publishing of as FAIR (see below) and open as possible data. This can involve pre-publishing with, e.g., BioRxiv; utilizing open licenses; and archiving of data in open access repositories. 
Note that you need to inform yourself on current policies and costs.

#### Recommended Reads and Resources
* European University Association asbl. (2022). **The EUA Open Science Agenda 2025**. [https://www.eua.eu/images/eua_os_agenda.pdf](https://www.eua.eu/images/eua_os_agenda.pdf)
* Corti, L., et al. (2014). **Managing and Sharing Research Data: A Guide to Good Practice**. Sage Publishing. [https://doi.org/10.25607/OBP-1540](https://doi.org/10.25607/OBP-1540)
* Dijkers, M. P. (2019). **A beginner’s guide to data stewardship and data sharing**. _Spinal Cord_, 57(3). [https://doi.org/10.1038/s41393-018-0232-6](https://doi.org/10.1038/s41393-018-0232-6)
* Markowetz, F. (2015). **Five selfish reasons to work reproducibly**. _Genome Biology_, 16(1), 274. [https://doi.org/10/gf8cjc](https://doi.org/10/gf8cjc)
* Quintana, D. (2020). **Five things about open and reproducible science that every early career researcher should know**. [https://doi.org/10.17605/OSF.IO/DZTVQ](https://doi.org/10.17605/OSF.IO/DZTVQ)
* **Open Science Best Practices for Data Science and AI** - NFDI4DS: [https://nfdi4ds.github.io/ds-best-practices/](https://nfdi4ds.github.io/ds-best-practices/)


### Publishing Data
Data as basis of scientific results and conclusions needs to be made available to provide replicability, reproducibility, transparency. To allow others to understand and work with your data, it needs to be findable, accessible, interoperable, and reusable (= FAIR).
- Wilkinson, et al. (2016). **The FAIR Guiding Principles for scientific data management and stewardship**. _Scientific Data_, 3(1). [https://doi.org/10/bdd4](https://doi.org/10/bdd4)

The earlier you consider and plan for publishing your data, the easier it is to adhere to standards and best practices, like described in, for example:
- Engler, J. B. (2024). **Tidyplots empowers life scientists with easy code-based data visualization** (p. 2024.11.08.621836). bioRxiv. [https://doi.org/10.1101/2024.11.08.621836](https://doi.org/10.1101/2024.11.08.621836)
- Wickham, H. (2014). **Tidy Data**. _Journal of Statistical Software_, 59, 1–23. [https://doi.org/10.18637/jss.v059.i10](https://doi.org/10.18637/jss.v059.i10)
- Wickham, H., Cetinkaya-Rundel, M., & Grolemund, G. (2023). **R for Data Science: Import, Tidy, Transform, Visualize, and Model Data** (2nd ed.). O’Reilly Media. [https://r4ds.hadley.nz/](https://r4ds.hadley.nz/)
- Wilson, G., et al. (2017). **Good enough practices in scientific computing**. _PLOS Computational Biology_, 13(6), e1005510. [https://doi.org/10.1371/journal.pcbi.1005510](https://doi.org/10.1371/journal.pcbi.1005510)

Depending on your research field, expect that there are standards for data and metadata reporting, file formats, and other aspects of communicating data. For example:
- Brazma, A., et al. (2001). **Minimum information about a microarray experiment (MIAME)—Toward standards for microarray data**. _Nature Genetics_, 29(4), 365–371. [https://doi.org/10.1038/ng1201-365](https://doi.org/10.1038/ng1201-365)
- Hammer, M., et al. (2021). **Towards community-driven metadata standards for light microscopy: Tiered specifications extending the OME model**. _Nature Methods_, 18(12), 1427–1440. [https://doi.org/10.1038/s41592-021-01327-9](https://doi.org/10.1038/s41592-021-01327-9)
- Orchard, S., et al. (2007). **The minimum information required for reporting a molecular interaction experiment (MIMIx)**. _Nature Biotechnology_, 25(8), 894–898. [https://doi.org/10.1038/nbt1324](https://doi.org/10.1038/nbt1324)
- Ropelewski, A. J., et al. (2022). **Standard metadata for 3D microscopy**. _Scientific Data_, 9(1), 449. [https://doi.org/10.1038/s41597-022-01562-5](https://doi.org/10.1038/s41597-022-01562-5)
- Sarkans, U., et al. (2021). **REMBI: Recommended Metadata for Biological Images—enabling reuse of microscopy data in biology**. _Nature Methods_, 18(12), 1418–1422. [https://doi.org/10.1038/s41592-021-01166-8](https://doi.org/10.1038/s41592-021-01166-8)
- Schapiro, D., et al. (2022). **MITI minimum information guidelines for highly multiplexed tissue images**. _Nature Methods_, 19(3), 262–267. [https://doi.org/10.1038/s41592-022-01415-4](https://doi.org/10.1038/s41592-022-01415-4)
- Sugimoto, S., Baker, T., & Weibel, S. L. (2002). **Dublin Core: Process and Principles**. In _Digital Libraries: People, Knowledge, and Technology_ (pp. 25–35). Springer. [https://doi.org/10.1007/3-540-36227-4_3](https://doi.org/10.1007/3-540-36227-4_3)
- Taylor, C. F., et al. (2007). **The minimum information about a proteomics experiment (MIAPE)**. _Nature Biotechnology_, 25(8), 887–893. [https://doi.org/10.1038/nbt1329](https://doi.org/10.1038/nbt1329)
- Wieczorek, J., et al. (2012). **Darwin Core: An Evolving Community-Developed Biodiversity Data Standard**. _PLOS ONE_, 7(1), e29715. [https://doi.org/10.1371/journal.pone.0029715](https://doi.org/10.1371/journal.pone.0029715)
- Yilmaz, P., et al. (2011). **Minimum information about a marker gene sequence (MIMARKS) and minimum information about any (x) sequence (MIxS) specifications**. _Nature Biotechnology_, 29(5), 415–420. [https://doi.org/10.1038/nbt.1823](https://doi.org/10.1038/nbt.1823)

The FAIRsharing database ([https://fairsharing.org/](https://fairsharing.org/)) is a valuable resource to identify relevant standards, databases, and policies.

Publishing data often requires its deposition in an accessible database, i.e, a repository. Finding suitable repositories is facilitated by the Registry of Research Data Repositories ([https://www.re3data.org/](https://www.re3data.org/)). 

How to choose a repository is detailed in this guide: Whyte, A.. (2015). **Where to keep research data: DCC checklist for evaluating data repositories**. V1.1. _Edinburgh: Digital Curation Centre_. [https://www.dcc.ac.uk/guidance/how-guides/where-keep-research-data](https://www.dcc.ac.uk/guidance/how-guides/where-keep-research-data)

Published data can and should be cited, thereby enhancing the visibility and impact of the publishing researchers: Silvello (2018). **Theory and practice of data citation**. Journal of the Association for Information Science and Technology, 69: 6-20. [https://doi.org/10.1002/asi.23917](https://doi.org/10.1002/asi.23917)


## Further Reading

### On Writing
* Turabian, M. L. (2018). **A Manual for Writers of Research Papers, Theses, and Dissertations** 9th Edition. [http://archive.org/details/turbanian-9edition-textbook_202301](http://archive.org/details/turbanian-9edition-textbook_202301)
* Strunk, W. Jr., White, E. B. (1999) **The Elements Of Style** 4th Edition. Pearson. [http://archive.org/details/TheElementsOfStyle4thEdition](http://archive.org/details/TheElementsOfStyle4thEdition)

### On science communication and visualization
* Publications Office of the European Union (2022). **A practical guide to user-friendly data in publications**. [https://data.europa.eu/apps/data-in-publications-guide/2022-data-in-publications-guide-extended.pdf](https://data.europa.eu/apps/data-in-publications-guide/2022-data-in-publications-guide-extended.pdf) 
* Nature Reviews **Artwork Guide to Scientific Figures**. [https://www.nature.com/documents/natrev-artworkguide.pdf](https://www.nature.com/documents/natrev-artworkguide.pdf)
* **How to Make Good Figures for Scientific Papers**. [https://www.simplifiedsciencepublishing.com/resources/how-to-make-good-figures-for-scientific-papers](https://www.simplifiedsciencepublishing.com/resources/how-to-make-good-figures-for-scientific-papers)

See also more information in the [G_ManuscriptFigures_README](/PhD/04_Publications/ManuscriptX/01_Figures/G_ManuscriptFigures_README.md).

_____

This file is part of the PhD Folder Structure project by Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>) & Jeanne  Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>)

* git: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)
* DOI: 

