2025-03-17


# Guide README of 'Thesis/Figures' folder

## Structure and Scheme

In here you find the following parts / folders:

```
01_Figures/
├── FigX/
│   ├── Code/
│   ├── Data/
│   ├── FigX_Caption.md
│   └── M_FigX_README.md/
├── zzz/
├── FigX.zip
└── G_ThesisFigures_README.md

```

Note that **figure** is used here, for conciseness, also as a synonym for **table**, **graph**, and other forms of **data visualization**.


| Part         		| Purpose / Content   |
|--------------		|-----------|
| 1. FigX 		| Contains figure panel 1A (for example) as well as the code and data used to produce exactly this panel. The corresponding M_Fig1A_README supports according metadata collection, while Fig1A_Caption.md invites to immediately record the figure's caption. |
| 2. FigX.zip  		| Contains zipped folder structure identical to FigX as a template.|

Feel free to adapt this structure to your specific needs and workflow.

#### Metadata READMEs

Metadata READMEs are denoted with a "M_" starting the file name. They are used to provide mostly descriptive, administrative and legal information.

| Metadata README                                                                          | Purpose / Content                                                                             |
| ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [M_FigX_README.md](/PhD/05_Thesis/01_Figures/FigX/M_FigX_README.md) | Copy and fill in information on figures used in publications          |


## Best Practice Recommendations

### Code and Data of Figures
We imagine that you work with your data in the 02_Projects/ folder, keeping yor raw data raw, and extracts of datasets for visualization in the processed folder. To generate figures, we assume that you document your steps in code or at least as a "recipe". As your work evolves, you will decide which data should be represented in which form in an emerging manuscript. Often, this is follows by many changes to the figure itself, e.g., by changing the range of data or the color scheme. 
By providing a Data/ and Code/ folder here, at the manuscript level, we invite you to copy the relevant parts from the project folder and store them closer to the manuscript with a relevant label attached (Fig1A), ideally also with a documentation of provenance, i.e., a reference to the original location in your system (somewhere in 02_Projects/). This way, you can avoid confusion of "Which version of the dataset did I use with which code snippet to generate this color-version?" - a common occurence if you do not implement a systematic approach to keeping track.

### Data Visualization
Efficient data visualization is essential for communicating your findings. There is a lot of guidance available what constitutes good and efficient data visualization, see below (Further Reading). 
We strongly advocate for conscious selection of type (e.g., bar chart vs box plot), color, layout, and labelling.

### Figure Captions
Captions are a helpful tool to support your figure. Some key tips are:
- **Standalone**: captions shall provide enough context to understand the figure without referring to the main text. Thus, a caption should contain details like the purpose of the figure, key findings, and other necessary explanations.
- **Declarative** Title: Start the caption with a concise, descriptive title that summarizes the main finding or purpose of the figure.
- Essential **details**: 
	- Describe interpretation-relevant methods briefly.
	- Provide statistical information such as sample sizes (n), error bars, and significance levels (e.g., p-values and the tests that produced them).
	- Define used abbreviations or symbols.
- **Avoid redundancy**: Instead of repeating information already given in the figure, aid understanding with additional context or explanations.

### Thesis-specific Tips
- **Format** and **place** figures **consistently** throughout your thesis:
	- Use a consistent format for labels (abbreviation with or without ., bold font, etc.).
	- Use a consistent format for captions and indications (e.g., bold label, left aligned, single spaced, smaller font size).
	- Place figures consistently either closest to their first mentioning in the main text or bundled at the end of a chapter / before the references.
 - **Number** figures **consistently**:
	- Either label everything consecutively (e.g., Fig. 1, Tab. 15).
 	- Or label everything by chapter (e.g., Fig. 1.1, Tab. 12.15).
	- Appendix figures may follow a different style.
 - **Include** all tables and figures in the respective **lists** in the front matter of the thesis.


## Further Reading
#### Good Overviews on Data Visualization:
- Franconeri, S. L., Padilla, L. M., Shah, P., Zacks, J. M., & Hullman, J. (2021). **The Science of Visual Data Communication: What Works**. _Psychological Science in the Public Interest_, 22(3), 110–161. [https://doi.org/10.1177/15291006211051956](https://doi.org/10.1177/15291006211051956)
- Wilke, C. O. (2019). **Fundamentals of Data Visualization: A Primer on Making Informative and Compelling Figures**. O’Reilly Media, Inc.
  
#### More on Data Visualization:
- Divecha, C., Tullu, M., & Karande, S. (2023). **Utilizing tables, figures, charts and graphs to enhance the readability of a research paper**. _Journal of Postgraduate Medicine_, 69(3), 125–131. [https://doi.org/10.4103/jpgm.jpgm_387_23](https://doi.org/10.4103/jpgm.jpgm_387_23)
- Franzblau, L. E., & Chung, K. C. (2012). **Graphs, Tables, and Figures in Scientific Publications: The Good, the Bad, and How Not to Be the Latter**. _The Journal of Hand Surgery_, 37(3), 591–596. [https://doi.org/10.1016/j.jhsa.2011.12.041](https://doi.org/10.1016/j.jhsa.2011.12.041)
- Hehman, E., & Xie, S. Y. (2021). **Doing Better Data Visualization**. _Advances in Methods and Practices in Psychological Science_, 4(4), 25152459211045334. [https://doi.org/10.1177/25152459211045334](https://doi.org/10.1177/25152459211045334)
- Nguyen, V. T., Jung, K., & Gupta, V. (2021). **Examining data visualization pitfalls in scientific publications**. V_isual Computing for Industry, Biomedicine, and Art_, 4, 27. [https://doi.org/10.1186/s42492-021-00092-y](https://doi.org/10.1186/s42492-021-00092-y)
- Rougier, N. P., Droettboom, M., & Bourne, P. E. (2014). Ten Simple Rules for Better Figures. PLOS Computational Biology, 10(9), e1003833. https://doi.org/10.1371/journal.pcbi.1003833
- **Seeing Is Believing: Why Including Tables and Figures Matters to the Effectiveness of Your Publications**. (2015). _Advances in Neonatal Care_, 15(2), 77. [https://doi.org/10.1097/ANC.0000000000000173](https://doi.org/10.1097/ANC.0000000000000173)

#### On Figure Captions
- Biegel, C. M., & Kamat, P. V. (2019). **Ten Tips for Capturing Figures with Captions**. _ACS Energy Letters_, 4(3), 637–638. [https://doi.org/10.1021/acsenergylett.9b00253](https://doi.org/10.1021/acsenergylett.9b00253)
- **Captions for Figures in Documents | CHEC: Cornell Help for Engineering Communication**. (n.d.). Retrieved March 17, 2025, from [https://chec.engineering.cornell.edu/visuals/captions-for-figures-in-documents/](https://chec.engineering.cornell.edu/visuals/captions-for-figures-in-documents/)
- Clancy, L. (2020). **How to write a figure caption**. _International Science Editing_. [https://www.internationalscienceediting.com/how-to-write-a-figure-caption/](https://www.internationalscienceediting.com/how-to-write-a-figure-caption/)
- Huang, C.-Y., et al. (2023). **Summaries as Captions: Generating Figure Captions for Scientific Documents with Automated Text Summarization**. _Proceedings of the - 16th International Natural Language Generation Conference_, 80–92. [https://doi.org/10.18653/v1/2023.inlg-main.6](https://doi.org/10.18653/v1/2023.inlg-main.6)




_____

This file is part of the PhD Folder Structure project by Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>) & Jeanne  Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>) & Ron Dockhorn (<a href="https://orcid.org/0000-0002-5268-5430"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-5268-5430</a>).

* git: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)

