
# Cox Proportional Hazard + EDA

This repository contains a Jupyter notebook for data preprocessing and analysis using the Cox Proportional Hazard model. The analysis is based on a dataset from the Mayo Clinic.

## Table of Contents
- [Cox Proportional Hazard + EDA](#cox-proportional-hazard--eda)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Data Preprocessing](#data-preprocessing)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Cox Proportional Hazard Model](#cox-proportional-hazard-model)
  - [Results](#results)
  - [Conclusion](#conclusion)
  - [Usage](#usage)
  - [References](#references)

## Introduction
This notebook demonstrates data preprocessing and exploratory data analysis (EDA) on a medical dataset, followed by the application of the Cox Proportional Hazard model to analyze survival data.

## Data Preprocessing
The initial step involves loading and preprocessing the data to prepare it for analysis. This includes handling missing values, encoding categorical variables, and normalizing numerical features.

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is performed to understand the underlying patterns and distributions within the dataset. Various visualizations are used to summarize the data and identify any potential relationships between variables.

## Cox Proportional Hazard Model
The Cox Proportional Hazard model is applied to the dataset to analyze the survival times of patients. The model is trained using the `lifelines` library, and the concordance index is used to evaluate the model's performance.

## Results
The results section includes the output of the Cox Proportional Hazard model, including the estimated coefficients for each covariate and the concordance index.

## Conclusion
A summary of the findings from the analysis, including any significant relationships identified between the covariates and the survival times.

## Usage
To run the notebook, you need to have the following Python libraries installed:
- numpy
- pandas
- sklearn
- matplotlib
- lifelines


## References
- [Mayo Clinic Dataset](https://www.mayo.edu/research/documents/pbchtml/doc-10027635)
