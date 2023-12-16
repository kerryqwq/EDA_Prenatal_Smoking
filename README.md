# Exploratory Data Analysis of Prenatal Smoking and Environmental Tobacco Smoke Exposure on Children


## Abstract
In collaboration with Dr. Lauren Micalizzi, this project aims to conduct an Exploratory Data Analysis to investigate the impacts of smoking during pregnancy (SDP) and environmental tobacco smoke (ETS) exposure on children's substance use, externalizing behaviors, and self-regulation. Key aspects of the study include data preprocessing, addressing missing data, exploring demographic information and conducting extensive analysis to understand the relationship between prenatal/postnatal tobacco exposure and children's behavioral and self-regulation outcomes. The findings suggest a potential positive association between maternal smoking and children’s substance use and externalizing behaviors. However, limitations like small sample size and substantial data missingness call for more rigorous future analyses.

## Introduction
This project conducts an exploratory data analysis (EDA) to investigate the impacts of smoking during pregnancy (SDP) and environmental tobacco smoke (ETS) exposure on children's substance use, externalizing behaviors, and self-regulation.

The data originates from a smoke avoidance program for low-income pregnant women that aimed to reduce both SDP and ETS exposure. A subset of 49 adolescent-mother pairs were selected for further study, with baseline data and two longitudinal follow-ups at 6 and 12 months.

The dataset comprises 78 variables capturing demographics, prenatal smoking, postnatal smoke exposure, children's substance use, behavior problems, and emotion regulation.

## Data Preprocessing
* Corrected invalid entries in mom_numcig, income, and other variables
* Converted factors like "Yes/No" and empty values to 1/0 and NA
* Transformed character variables containing numbers to numeric type

## Key Findings
* Children of smoking mothers had higher rates of marijuana, e-cigarettes, alcohol use
* Prenatal smoking positively associated with externalizing behaviors
* No clear impact of postnatal smoke on substance use and behaviors
* Dataset limitations:
* Small sample size (49 pairs)
* High missingness (65 of 78 variables affected)

## Repository Files
* Project1.Rmd: R script containing data preprocessing, analysis, and visualization
* Project1.pdf: Full project report detailing methods and findings
