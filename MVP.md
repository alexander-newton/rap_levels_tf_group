# This page will no longer be updated, please see the [RAP Maturity Guidance](https://github.com/best-practice-and-impact/rap_mvp_maturity_guidance/blob/master/Reproducible-Analytical-Pipelines-MVP.md).

# RAP Benefits

A RAP should:
- Improve the quality of the analysis.
- Increase trust in the analysis by producers, their managers and users.
- Create a more efficient process.
- Improve business continuity and knowledge management.

# RAP MVP

In order to achieve these benefits, at a minimum a RAP must:
- Augment extant technical and quality assurance processes with **peer review** to ensure that the process is reproducible and that the below requirements have been met.
- **Minimise manual steps**, for example copy-paste, point-click or drag-drop steps. Where it is absolutely necessary to include a manual step in the process this must be documented as described below. 
- Be built using **open source software** which is available to anyone, preferably R or python.
- Guarantee an **audit trail** using version control software, preferably Git.
- Be **open to anyone**. This can be facilitated most easily through the use of file and code sharing platforms.
- Follow **existing good practice for quality assurance** - guidance set by departments or organisations, and by the Good Practice Team for the Government Statistical Service.
- Contain **well-commented** code and have **documentation embedded** within the product, rather than saved elsewhere.


Notes:
- There may be restrictions, such as access to databases, which stop analysis producers building a RAP for their full end-to-end process. In this case, the above requirements apply to the selected part of the process.
- There may be restrictions, such as sensitive or confidential content, which stop analysis producers from sharing their RAP publicly. In this case, it may be possible to share the RAP within a department or organisation instead.
- It is recommended that when possible a RAP should be built collaboratively - this will improve the quality of the final product and helps to facilitate knowledge sharing.
- There is not a specific tool that is required to build a RAP, but both R and Python provide the power and flexibility to carry out end-to-end analytical processes, from data source to final presentation.

# Further RAP developments
- Functions/code modularity
- Unit testing of functions
- Error handling for functions
- Documentation of functions
- Package
- Code style
- Input data validation
- Logging of data
- Continuous integration
- Dependency management
- Containerisation
