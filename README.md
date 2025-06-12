# 2009 Pandemic Influenza A(H1N1) Surveys in Hong Kong

## Contents

1.  [Study overview](#overview)

2.  [Raw data](#data)

3.  [Overview](#first)

4.  [Future work](#further)

[Authors and investigators](#authors)

[A comment on reproducible research](#comment)

[Publications](#references)

[Acknowledgements](#acknowledgements)

## 1. Study overview

There is a substantial literature examining psychosocial determinants of behavior change in relation to non-communicable disease, but much less research has been devoted to understanding how populations react and respond to communicable disease epidemics. Yet is it precisely these responses that can potentially determine the overall impact of an epidemic by influencing risk-taking and protective practices.

Our group has been conducting a series of population surveys in collaboration with the [School of Public Health at CUHK](https://www.sphpc.cuhk.edu.hk/), to study community responses before, during and after the first wave of 2009 pandemic influenza A(H1N1) locally, to determine disease attack rates and use of healthcare services, and to study the use of preventive measures, and how these might be affected by individuals’ attitudes towards influenza and their perception of the risks they faced.

## 2. Raw data 

Raw data from our surveys is available to download as a zip file here:

-   [HKU_surveys_v1.csv](data/HKU_surveys_v1.csv "Hong Kong H1N1 surveys dataset version 1")

-   [survey_data_dictionary.xls](data/survey_data_dictionary.xls "Hong Kong H1N1 surveys data dictionary version 1")

This version of the survey data contains all items included in our first paper. Data on additional items included in our surveys will be released at a later date.

We provide our data under the [Open Data Commons Public Domain Dedication and License](https://opendatacommons.org/licenses/pddl/1-0/), which is a version of open access for data. Under this licence we reserve no rights: there are no restrictions on use of our data, and no requirement to cite our work or this website. However we would anticipate that for academic purposes the standard practice of referencing sources would apply. We would like to hear from researchers who are using our data and we would be keen to work together on analyses.

## 3. Overview of survey findings 

Our first manuscript, published in the Journal of Infectious Diseases, describes the main results of 13 cross-sectional telephone surveys conducted between April and November 2009. Overall we identified no substantial changes in preventive measures through the first wave of H1N1, suggesting that community measures may not have played a substantial role in mitigating the epidemic impact. We also explored the factors associated with the adoption of hygiene behaviors, face mask use and social distancing.

Results presented in that manuscript are reproduced in the following scripts which can be run in the free statistical software package [R](http://www.r-project.org "R statistical software homepage"):

-   [scripts](H1N1_surveys_scripts/dataframe.r) to reformat the raw data (used in some of the other scripts here).

-   [Table 3](H1N1_surveys_scripts/Table_3.r) *(requires the R package 'MASS')*.

-   [Table 4](H1N1_surveys_scripts/Table_4.r) *(requires the R package 'MASS')*.

-   [Table 5](H1N1_surveys_scripts/Table_5.r) *(requires the R package 'MASS')*.

-   [Figure 2](H1N1_surveys_scripts/Figure_2.r) *(requires the R packages 'IDPmisc' and 'fields')*

## 4. Future work 

We are continuing to analyze our survey data and further work is in preparation. More details will follow later.

## Authors and investigators 

The principal investigators of this study are Richard Fielding and [Ben Cowling](https://sph.hku.hk/en/Biography/Cowling-Benjamin-John). The data were uploaded by [Ben Cowling](https://sph.hku.hk/en/Biography/Cowling-Benjamin-John), and the scripts were written by Diane Ng, Vicky Fang and [Ben Cowling](http://www.hku.hk/cmd/staff/bio/cowling.htm).

## A comment on reproducible research 

We fully support the [increasing calls](http://dx.doi.org/10.1097/EDE.0b013e318196784a) from the academic community for [epidemiologic analyses to be reproducible](http://dx.doi.org/10.1093/aje/kwj093 "Peng et al., 2006, AJE"), as part of the wider scientific endeavour to replicate results. Another example of this recommendation is in the [Good Practice Guide for Quantitative Veterinary Epidemiology](http://www.qve-goodpracticeguide.org.uk/guide#TOC-2.4-Inputs). Here we have published the raw *anonymised* data from our telephone surveys. We have also published scripts which allow the analyses in our published papers to be reproduced.

Thousands of local people have given their time to answer our questions, in the expectation that our research studies will add to public health knowledge and inform policy makers. Participants are likely to expect that we will make the best possible use of the information that we have collected about them in our studies. It would be difficult to argue that facilitating best use of the data by the research community need not involve releasing raw data.

Publication of anonymised raw data has been approved by our local IRB and funding sources.\
We anticipate that release of the raw data will:

-   Promote reproducibility of our results
-   Allow other investigators to conduct their own analyses on our data
-   Allow other investigators to compare our data with theirs, for example to explore similarities and differences between research findings
-   Allow other investigators to prepare and plan for their own studies

**The raw data sources and R scripts to regenerate results in the published paper can also be downloaded from DRYAD [[link]](http://doi.org/10.5061/dryad.1485f).**

## Publications 

1.  **Cowling BJ, Ng DMW, Ip DKM, Liao Q, Lam WWT, Wu JT, Lau JTF, Griffiths SM, Fielding R.**\
    Community psychological and behavioral responses through the first wave of 2009 influenza A(H1N1) pandemic in Hong Kong. *Journal of Infectious Diseases*, 2010; **202**(6):867-876. [[link]](https://doi.org/10.1086/655811) [[PubMed]](http://www.ncbi.nlm.nih.gov/pubmed/20677945)

#### Acknowledgements 

This study received funding from the Research Fund for the Control of Infectious Disease,\
Food and Health Bureau, Government of the Hong Kong SAR (grant no. PHE-1),\
and the Area of Excellence Scheme of the Hong Kong University Grants Committee (grant no. AoE/M-12/06).

Surveys were conducted by [HKU Public Opinion Program (HKUPOP)](http://hkupop.hku.hk/).

------------------------------------------------------------------------

[![Creative Commons License](https://i.creativecommons.org/l/by/3.0/80x15.png)](http://creativecommons.org/licenses/by/3.0/) This work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/). It was written by [Ben Cowling](http://www.hku.hk/cmd/staff/bio/cowling.htm) (email).
