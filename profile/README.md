<!-- mixOmics-org/.github/profile/README.md -->

[<img src="https://raw.githubusercontent.com/mixOmics-org/.github/main/profile/assets/mixomics-logo.svg" alt="mixOmics" height="120">](https://mixomics.org)

## mixOmics

**mixOmics** is an R toolkit for integrating and interpreting single-omics and multi-omics data — nineteen multivariate methods built for input where the variables far outnumber the samples and the signal is found across several molecular layers rather than in any one of them. The methods include internal variable selection, so a result lists the important genes, proteins or taxa that covary. 

This organisation holds the package, its methods, and the material taught around them. The package itself, with installation instructions and full documentation, is at [mixOmics-org/mixOmics](https://github.com/mixOmics-org/mixOmics).

[![in Bioconductor](https://bioconductor.org/shields/years-in-bioc/mixOmics.svg)](https://bioconductor.org/packages/mixOmics)
[![Downloads](https://bioconductor.org/shields/downloads/release/mixOmics.svg)](https://bioconductor.org/packages/stats/bioc/mixOmics/)
[![Build](https://bioconductor.org/shields/build/release/bioc/mixOmics.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/mixOmics/)

mixOmics has been in continuous development since 2009, led throughout by Professor Kim-Anh Lê Cao, funded by one competitive grant to the next. It is trusted by more than 50,000 researchers a year spanning over 130 countries<sup>[1](#references)</sup>, is cited in more than 9,000 peer-reviewed papers<sup>[2](#references)</sup>, and appears in over 160 patents<sup>[3](#references)</sup> and at least 20 Government Policies. Our methods consistently work in someone else’s hands, on data we have never seen<sup>[4,5](#references)</sup>.

mixOmics has been used to map the planktonic microbiome of the Great Barrier Reef<sup>[6,7,8](#references)</sup>, to show that microbial gene content predicts reef water chemistry better than taxonomy does<sup>[9](#references)</sup>, to trace picoplankton across the world’s oceans<sup>[10](#references)</sup>, to find biomarkers in cancer, Alzheimer’s disease and diabetes<sup>[11,12,13](#references)</sup>, in vaccine research<sup>[14,15](#references)</sup>, nutrition and advancements in understanding the human gut biome<sup>[16,17](#references)</sup>, and in crop and livestock genomics<sup>[18,19](#references)</sup>. Approaches general enough to cross ecology, agriculture and human health, not tuned to any single dataset.

### Our methods

| | | |
|---|---|---|
| **(s)PCA** | (sparse) Principal Component Analysis | |
| **(s)IPCA** | (sparse) Independent Principal Component Analysis | [Yao et al. 2012](https://doi.org/10.1186/1471-2105-13-24) |
| **(r)CCA** | (regularised) Canonical Correlation Analysis | [González et al. 2008](https://doi.org/10.18637/jss.v023.i12) |
| **(s)PLS** | (sparse) Partial Least Squares, regression and canonical | [Lê Cao et al. 2008](https://doi.org/10.2202/1544-6115.1390) |
| **(s)PLS-DA** | (sparse) Partial Least Squares Discriminant Analysis | [Lê Cao et al. 2011](https://doi.org/10.1186/1471-2105-12-253) |
| **Multilevel** | decomposition for repeated measurements | [Liquet et al. 2012](https://doi.org/10.1186/1471-2105-13-325) |
| **mixMC** | multivariate analysis of 16S microbiome data | [Lê Cao et al. 2016](https://doi.org/10.1371/journal.pone.0160169) |
| **MINT** | P-integration across independent studies | [Rohart et al. 2017](https://doi.org/10.1186/s12859-017-1553-8) |
| **DIABLO** | N-integration across data types on the same samples | [Singh et al. 2019](https://doi.org/10.1093/bioinformatics/bty1054) |

[Select your method](https://mixomics.org/getting-started/selecting-your-method/) covers which suits which kind of data; [mixomics.org/methods](https://mixomics.org/methods/) has worked examples for each.

### Our history

mixOmics was written by Professor Kim-Anh Lê Cao, with early version co-development from Dr. Ignacio González and input from Dr. Sébastien Déjean. It appeared in 2009 as integrOmics<sup>[20](#references)</sup>, was renamed to mixOmics on CRAN in February 2010, and moved to Bioconductor in 2017. It is developed at the [Lê Cao Lab](https://github.com/lecaolab).

### Citing mixOmics

Run `citation("mixOmics")` in R for the current canonical citation, or see [CITATION](https://github.com/mixOmics-org/mixOmics/blob/master/inst/CITATION) in the package. The software paper is:

> Rohart F, Gautier B, Singh A, Lê Cao K-A (2017). mixOmics: An R package for 'omics feature selection and multiple data integration. *PLOS Computational Biology* 13(11): e1005752. [doi.org/10.1371/journal.pcbi.1005752](https://doi.org/10.1371/journal.pcbi.1005752)

Individual methods have their own papers — see the table above.

### Our pages

| | &nbsp;&nbsp;&nbsp;&nbsp;Web&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;LinkedIn&nbsp; | &nbsp;&nbsp;GitHub&nbsp;&nbsp; |
|---|:---:|:---:|:---:|
| **[mixOmics](https://mixomics.org)** <br><small>The package and its community</small> | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/octicon:globe-24.svg?color=white"><img src="https://api.iconify.design/octicon:globe-24.svg?color=black" alt="mixOmics web" title="mixOmics web" height="18"></picture>](https://mixomics.org) | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/simple-icons:linkedin.svg?color=white"><img src="https://api.iconify.design/simple-icons:linkedin.svg?color=black" alt="mixOmics linkedin" title="mixOmics linkedin" height="18"></picture>](https://www.linkedin.com/company/mixomics) | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/simple-icons:github.svg?color=white"><img src="https://api.iconify.design/simple-icons:github.svg?color=black" alt="mixOmics github" title="mixOmics github" height="18"></picture>](https://github.com/mixOmics-org) |
| **[Lê Cao Lab](https://lecao-lab.science.unimelb.edu.au/)** <br><small>Where mixOmics is developed</small> | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/octicon:globe-24.svg?color=white"><img src="https://api.iconify.design/octicon:globe-24.svg?color=black" alt="Lê Cao Lab web" title="Lê Cao Lab web" height="18"></picture>](https://lecao-lab.science.unimelb.edu.au/) | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/simple-icons:linkedin.svg?color=white"><img src="https://api.iconify.design/simple-icons:linkedin.svg?color=black" alt="Lê Cao Lab linkedin" title="Lê Cao Lab linkedin" height="18"></picture>](https://www.linkedin.com/company/lecao-lab) | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/simple-icons:github.svg?color=white"><img src="https://api.iconify.design/simple-icons:github.svg?color=black" alt="Lê Cao Lab github" title="Lê Cao Lab github" height="18"></picture>](https://github.com/lecaolab) |
| **[Kim-Anh Lê Cao](https://github.com/kimanh-lecao)** <br><small>Creator and lead maintainer</small> | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/octicon:globe-24.svg?color=white"><img src="https://api.iconify.design/octicon:globe-24.svg?color=black" alt="Kim-Anh Lê Cao web" title="Kim-Anh Lê Cao web" height="18"></picture>](https://lecao-lab.science.unimelb.edu.au/) | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/simple-icons:linkedin.svg?color=white"><img src="https://api.iconify.design/simple-icons:linkedin.svg?color=black" alt="Kim-Anh Lê Cao linkedin" title="Kim-Anh Lê Cao linkedin" height="18"></picture>](https://www.linkedin.com/in/kimanh-l%C3%AAcao) | [<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/simple-icons:github.svg?color=white"><img src="https://api.iconify.design/simple-icons:github.svg?color=black" alt="Kim-Anh Lê Cao github" title="Kim-Anh Lê Cao github" height="18"></picture>](https://github.com/kimanh-lecao) |

<br>

| &nbsp; | &nbsp; |
|---|---|
| Documentation and tutorials | [mixomics.org](https://mixomics.org) |
| Guides and vignettes | [guides.mixomics.org](https://guides.mixomics.org) |
| Questions about using mixOmics | [mixomics-users.discourse.group](https://mixomics-users.discourse.group) |
| Bugs and pull requests | [Issues](https://github.com/mixOmics-org/mixOmics/issues) |

The forum is for questions about using the package; the issue tracker is for bugs and feature requests.

<br>


Commercial training and support are available from [mixOmics Pro](https://mixomics.pro).


<br>

### References

| &nbsp; | &nbsp; |
|---|---|
| | **Reach and usage** |
| 1 | Bioconductor download statistics for mixOmics — distinct IP addresses and total downloads, by month and year. [bioconductor.org](https://bioconductor.org/packages/stats/bioc/mixOmics/) |
| 2 | Google Scholar citation record, Kim-Anh Lê Cao. [scholar.google.com.au](https://scholar.google.com.au/citations?user=amghzwsAAAAJ) |
| 3 | Google Patents full-text search for “mixOmics”. [patents.google.com](https://patents.google.com/?q=%22mixOmics%22) |
| 4 | Australian BioCommons — Multi-omics Analysis. National NCRIS-funded research infrastructure; the page header reproduces a mixOmics PLS-DA figure under CC-BY 4.0, credited to Rohart, Gautier, Singh & Lê Cao (2017). [biocommons.org.au](https://www.biocommons.org.au/multiomics) |
| 5 | Australian BioCommons webinar — *Multivariate integration of multi-omics data with mixOmics*, 6 March 2024. [biocommons.org.au](https://www.biocommons.org.au/events/mixomics) |
| | **Oceans and environment** |
| 6 | Robbins S, Terzin M, Dougan K, … Lê Cao K-A, et al. The planktonic microbiome of the Great Barrier Reef. *Nature* (2026). [doi.org](https://doi.org/10.1038/s41586-026-10778-z) |
| 7 | Australian Institute of Marine Science. *The Great Barrier Reef has a microbiome too.* 23 July 2026. [aims.gov.au](https://www.aims.gov.au/information-centre/news-and-stories/great-barrier-reef-has-microbiome-too) |
| 8 | *The Guardian.* Great Barrier Reef microbiome mapped as researchers discover 500 bacterial species previously unknown to science. 23 July 2026. [theguardian.com](https://www.theguardian.com/environment/2026/jul/23/great-barrier-reef-microbiome-mapped-as-researchers-discover-500-bacterial-species-previously-unknown-to-science) |
| 9 | Terzin M, et al. Gene content of seawater microbes is a strong predictor of water chemistry across the Great Barrier Reef. *Microbiome* (2025). [ncbi.nlm.nih.gov](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11737092/) |
| 10 | Salazar VW, Verbruggen H, Marcelino VR, Lê Cao K-A. Global picoplankton biogeography revealed by metagenomic and climatic data integration. *bioRxiv* (2024). 1,454 metagenomes — the largest integrated surface-ocean metagenome analysis to date. [doi.org](https://doi.org/10.1101/2024.11.23.624595) |
| | **Human health and disease** |
| 11 | Multi-omics integration predicts 17 disease incidences in the UK Biobank. *medRxiv* (2025). Uses the mixOmics `block.spls` model for outcome prediction under nested cross-validation. [doi.org](https://doi.org/10.1101/2025.08.01.25332841) |
| 12 | Liu C-H, Lai Y-L, Shen P-C, Liu H-C, et al. DriverDBv4: a multi-omics integration database for cancer driver gene research. *Nucleic Acids Research* 52(D1) (2024). Uses DIABLO. [doi.org](https://doi.org/10.1093/nar/gkad1060) |
| 13 | US Patent 12,226,460 — *Enzymatic methods for treating neurodegenerative disorders.* Specifies DIABLO in mixOmics for integrating metagenomic, metabolomic and transcriptomic data in an Alzheimer’s disease model. [patents.google.com](https://patents.google.com/patent/US12226460B2/en) |
| | **Vaccines and immunity** |
| 14 | Lee AH, Shannon CP, Amenyogbe N, … Lê Cao K-A, … Kollmann TR. Dynamic molecular changes during the first week of human life follow a robust developmental trajectory. *Nature Communications* 10:1092 (2019). DIABLO is the integration method; EPIC Consortium cohorts in The Gambia and Papua New Guinea. [doi.org](https://doi.org/10.1038/s41467-019-08794-x) |
| 15 | The omics strategy: the use of systems vaccinology to characterize immune responses to childhood immunization. *Expert Review of Vaccines* (2022). Names DIABLO among the tools applied to systems vaccinology datasets. [doi.org](https://doi.org/10.1080/14760584.2022.2093193) |
| | **Microbiome and nutrition** |
| 16 | Lê Cao K-A, Costello ME, Lakis VA, Bartolo F, Chua XY, Brazeilles R, Rondeau P. MixMC: a multivariate statistical framework to gain insight into microbial communities. *PLOS ONE* 11(8):e0160169 (2016). [doi.org](https://doi.org/10.1371/journal.pone.0160169) |
| 17 | Bodein A, Scott-Boyer M-P, Perin O, Lê Cao K-A, Droit A. timeOmics: an R package for longitudinal multi-omics data integration. *Bioinformatics* (2022). [doi.org](https://doi.org/10.1093/bioinformatics/btab782) |
| | **Agriculture and livestock** |
| 18 | Unveiling long-term prenatal nutrition biomarkers in beef cattle via multi-tissue and multi-OMICs analysis. *Metabolomics* (2025). 126 cows, 63 offspring, seven tissue types; data analysed via DIABLO in mixOmics. [doi.org](https://doi.org/10.1007/s11306-025-02384-3) |
| 19 | Decoding plant physiology through systems biology: integrative multi-omics and computational perspectives for next-generation crop design (2025). Identifies mixOmics/DIABLO among the frameworks on which true multi-omics integration relies. [sciencedirect.com](https://www.sciencedirect.com/science/article/pii/S2590346225004304) |
| | **Origins** |
| 20 | Lê Cao K-A, González I, Déjean S. integrOmics: an R package to unravel relationships between two omics datasets. *Bioinformatics* 25(21):2855–2856 (2009). [doi.org](https://doi.org/10.1093/bioinformatics/btp515) |
