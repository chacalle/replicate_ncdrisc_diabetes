# NCD Risk Factor Collaboration (NCD-RisC) Code and Data Sharing

This repository contains code and data for generating estimates of diabetes prevalence and treatment coverage amongst adults, in 200 countries and territories from 1990 to 2022, as reported in the publication "Worldwide trends in diabetes prevalence and treatment from 1990 to 2022: a pooled analysis of 1108 population-representative studies with 141 million participants." [1].

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

## Contents Guide

-   `data/` The list of data sources used in the study, together with input data used in the model from publicly available sources and contact information for other data sources.
-   `model/` R code for the Bayesian hierarchical model used to analyse the data to estimate diabetes prevalence and treatment coverage by country, year, and age for adults. See methods section and online appendix of publication [1] for details of the statistical methods. These codes were tested in R version 4.3.1, and details of the R environment used for modelling can be found here: <https://hub.docker.com/r/ncdrisc/ncdrisc_hpc_docker/tags?name=0.2>
-   `utils/` Essential covariate files.

## Contact

-   For more information about the paper or the NCD Risk Factor Collaboration, please see www.ncdrisc.org or contact [ncdrisc\@imperial.ac.uk](mailto:ncdrisc@imperial.ac.uk).

## Other Materials

-   Most users will prefer to access and use the complete NCD-RisC estimates of diabetes prevalence and treatment coverage, which are available here: www.ncdrisc.org/data-downloads.html.

## Acknowledgements

-   Population data used in this analysis were obtained from the 2024 revision to the United Nations' World Population Prospects [2].
-   Data on percent national population living in urban areas were obtained from the 2018 revision to the United Nations' World Urbanization Prospects [3].

## References

1.  NCD Risk Factor Collaboration (NCD-RisC). Worldwide trends in diabetes prevalence and treatment from 1990 to 2022: a pooled analysis of 1,108 population-representative studies with 141 million participants. *Lancet*, 2024.

2.  United Nations, Department of Economic and Social Affairs, Population Division (2024). World Population Prospects 2024, Online Edition.

3.  United Nations, Department of Economic and Social Affairs, Population Division (2018). World Urbanization Prospects: The 2018 Revision, Online Edition.
