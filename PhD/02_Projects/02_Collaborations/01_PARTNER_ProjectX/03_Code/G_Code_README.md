2025-05-12

# Guide README of 'Code' folder

## Structure and Scheme

In here you find the following parts / folders:

```
03_Code/
├── G_Code_README.md
└── M_Code_README.md

```

Feel free to adapt this structure to your specific needs and workflow.

## Best Practice Recommendations

Informatics and Bioinformatics workflows and the associated scripts and tools require dedicated care and documentation. For these tasks, many resources are available and we suggest to use the here provdied (non-exhaustive) best practices and reading recommendations as a **starting pad** for you to inform yourself. Asking your peers and experts is part of these best practices.

### Code Structure and Organization

- Use a **consistent directory structure** for storing code, data, and documentation with a descriptive naming convention of code snippets in separate files
- Use community-established **coding standards** and guidelines
- "**Keep Raw Data Raw!**" - consider your raw data as immutable; never change raw data by code execution
- Use **version control** systems (e.g., [Git](https://git-scm.com/)) to track changes and a web-interface (e.g. [github](https://github.com/) or [gitlab](https://about.gitlab.com/)) collaborate with others
- Consider **containerization** (e.g., [Docker](https://www.docker.com/)) engaging reproducibility and consistency
- Consider **web-based interactive computing platforms** (e.g., [Jupyter Notebooks](https://jupyter.org/)) for documenting, coding, visualization and public sharing on [Binder](https://jupyter.org/binder)

### Code Documentation and Comments

- Use **comments** to explain code functionality, logic, and purpose
- Provide **ReadMe** files for installation, requirements, and usage
- Use **metadata** [M_Code_README.md](/PhD/02_Projects/03_ProjectX/YYYY-MM-DD_ExperimentX/03_Code/M_Code_README.md) to describe code, such as title, author, and license.
- Lee BD (2018) **Ten simple rules for documenting scientific software**. PLoS Comput Biol 14(12): e1006561. [https://doi.org/10.1371/journal.pcbi.1006561](https://doi.org/10.1371/journal.pcbi.1006561)


### Code Sharing and Licensing

- Consider **sharing** code through public platforms like [github](https://github.com/) or [gitlab](https://about.gitlab.com/)
- Choose an open-source **license** that allows others to use, modify, and distribute the code, see [Choose-A-License](https://choosealicense.com)
- Consider assigning a **persistent identifier** to the code e.g. DOI on a public repository like [Zenodo](https://zenodo.org/)

## Further Reading

* Wilson G, Bryan J, Cranston K, Kitzes J, Nederbragt L, Teal TK (2017). **Good enough practices in scientific computing.** PLoS Comput Biol 13(6): e1005510. DOI [10.1371/journal.pcbi.1005510](https://doi.org/10.1371/journal.pcbi.1005510)
* The Turing Way Community. (2024). [**The Turing Way: A handbook for reproducible, ethical and collaborative research**.](https://book.the-turing-way.org/reproducible-research/reproducible-research); DOI: [10.5281/zenodo.7625728](https://doi.org/10.5281/zenodo.7625728)


_____

This file is part of the PhD Folder Structure project by Yasmin Demerdash (<a href="https://orcid.org/0000-0002-3246-7604"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-3246-7604</a>) & Jeanne  Wilbrandt (<a href="https://orcid.org/0000-0002-0363-3837"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-0363-3837</a>) & Ron Dockhorn (<a href="https://orcid.org/0000-0002-5268-5430"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-5268-5430</a>).

* git: [https://github.com/RDMJeanne/FolderStructure](https://github.com/RDMJeanne/FolderStructure)

