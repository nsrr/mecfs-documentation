## About

In 2016, the National Institutes of Health (NIH) launched an [initiative to study Myalgic Encephalomyelitis/Chronic Fatigue Syndrome (ME/CFS)](https://www.mapmecfs.org/group/post-infectious-mecfs-at-the-nih). The NIH Division of Intramural Research developed an exploratory clinical research program to perform deep phenotyping on a cohort of PI-ME/CFS volunteers and healthy volunteers (HV) as controls. Prior to the SARS-CoV-2 pandemic, this study recruited a cohort of well-characterized PI-ME/CFS patients and applied modern broad and deep scientific measures to describe their biophenotype compared to HVs. The aim was to identify relevant group differences that could generate new hypotheses about the pathogenesis of PI-ME/CFS and provide direction for future research. Over 75 scientists and clinicians across 15 of the 27 institutes that comprise the NIH contributed to this multi-disciplinary work. Importantly, we developed rigorous inclusion criteria which comprised detailed medical and psychological evaluations to minimize diagnostic misattribution. A relatively homogenous population was recruited in whom symptoms were initiated after infection. This study aimed to investigate the underlying pathophysiological mechanisms. The volunteers underwent a multi-dimensional evaluation that included a wide range of physiological measures, physical and cognitive performance testing, and biochemical, microbiological, and immunological assays of blood, cerebrospinal fluid, muscle, and stool. Novel measurement techniques were developed to query issues such as physical capacity, effort preference, and deconditioning that may confound the results. Multi-omic measurements of gene expression, proteins, metabolites, and lipids were performed in parallel on collected samples.

The NSRR ME/CFS dataset includes covariates/phenotypes from 17 PI-ME/CFS subjects and 21 matched controls. Raw polysomnography data (EDF) are available for 15 PI-ME/CFS subjects.

## Methods

The NIH ME/CFS initiative, procedures, and findings are described in [Wallitt et al. 2024](https://pubmed.ncbi.nlm.nih.gov/38383456/).

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team.

## Data overview

### Covariate/phenotype datasets (CSV)

The [covariate dataset files](:files_path:/datasets) (**mecfs-dataset-0.1.0.csv** and **mecfs-harmonized-dataset-0.1.0.csv**) contain 38 rows respectively. Use the [edf_filename](:variables_path:/edf_filename) column to link participants to raw polysomnography data.

The dataset columns are described in the accompanying data dictionary files. The variables data dictionary file includes column names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated "domain" (e.g., 1=Male, 2=Female), which are described in the domains data dictionary file. 

The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/mecfs-data-dictionary). 

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team. Key variables include:

  <table>
    <tr><td><b>Variable</b></td><td><b>Label</b></td></tr>
    <tr><td><a href=":variables_path:/nsrr_age">nsrr_age</a></td><td>Subject age</td></tr>
    <tr><td><a href=":variables_path:/nsrr_sex">nsrr_sex</a></td><td>Subject sex</td></tr> 
    <tr><td><a href=":variables_path:/nsrr_race">nsrr_race</a></td><td>Subject race</td></tr> 
    <tr><td><a href=":variables_path:/nsrr_bmi">nsrr_bmi</a></td><td>Body mass index (BMI)</td></tr> 
  </table>

### Raw polysomnography data

[Raw signal data](:files_path:/original/EDFs) are available as European Data Format (EDF) files. Polysomnography data were collected using a Natus Embla NDx system.

### Original covariate dataset and documentation

The ME/CFS contributor [provided original documentation and data](:files_path:/original) from their covariate data collection system.

## Access and usage restrictions

The ME/CFS dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
>
> [Walitt B, Singh K, LaMunion SR, Hallett M, Jacobson S, Chen K, Enose-Akahata Y, Apps R, Barb JJ, Bedard P, Brychta RJ, Buckley AW, Burbelo PD, Calco B, Cathay B, Chen L, Chigurupati S, Chen J, Cheung F, Chin LMK, Coleman BW, Courville AB, Deming MS, Drinkard B, Feng LR, Ferrucci L, Gabel SA, Gavin A, Goldstein DS, Hassanzadeh S, Horan SC, Horovitz SG, Johnson KR, Govan AJ, Knutson KM, Kreskow JD, Levin M, Lyons JJ, Madian N, Malik N, Mammen AL, McCulloch JA, McGurrin PM, Milner JD, Moaddel R, Mueller GA, Mukherjee A, Muñoz-Braceras S, Norato G, Pak K, Pinal-Fernandez I, Popa T, Reoma LB, Sack MN, Safavi F, Saligan LN, Sellers BA, Sinclair S, Smith B, Snow J, Solin S, Stussman BJ, Trinchieri G, Turner SA, Vetter CS, Vial F, Vizioli C, Williams A, Yang SB; Center for Human Immunology, Autoimmunity, and Inflammation (CHI) Consortium; Nath A. Deep phenotyping of post-infectious myalgic encephalomyelitis/chronic fatigue syndrome. Nat Commun. 2024 Feb 21;15(1):907. doi: 10.1038/s41467-024-45107-3. PMID: 38383456; PMCID: PMC10881493.](https://pubmed.ncbi.nlm.nih.gov/38383456/)

Users must include the following text in any Acknowledgements:

> The Myalgic Encephalomyelitis/Chronic Fatigue Syndrome at the National Institutes of Health study was supported by the Intramural Research Program of the NIH. The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002). 

## Changelog

*June 2025*

- Make ME/CFS dataset available for data requests

## References

- ME/CFS at the NIH: https://www.mapmecfs.org/group/post-infectious-mecfs-at-the-nih
- ME/CFS GitHub Data Dictionary: http://github.com/nsrr/mecfs-data-dictionary
- ME/CFS GitHub Documentation: https://github.com/nsrr/mecfs-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
