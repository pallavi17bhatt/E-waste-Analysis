# E-Waste Management Data Analysis

This repository contains Jupyter notebooks and datasets related to the analysis of E-waste management in India and globally over the past 20 years.

## Overview

This project aims to explore and analyze the current state and historical trends in E-waste management. The analysis is conducted in two parts:

1. **E-Waste Management in India:** A survey-based study that examines the awareness, practices, and challenges of E-waste management in India.
2. **Global E-Waste Management (2000-2020):** A comprehensive analysis of global E-waste data over the past 20 years, focusing on trends, regional differences, and the impact of policies.

## Repository Structure

- Contains the Jupyter notebooks used for data analysis.
  - `ewaste_survey_data_analysis.ipynb`: Analysis of the E-waste management survey conducted in India.
  - `ewaste_global_data_analysis.ipynb`: Analysis of the global E-waste management dataset.

- Contains the datasets used for analysis.
  - `E-Waste Management Survey_response_latest.csv`: Raw dataset from the survey conducted in India.
  - `GlobalData.csv`: Global E-waste data  [source](https://data-explorer.oecd.org/vis?tenant=archive&df[ds]=DisseminateArchiveDMZ&df[id]=DF_EWASTE&df[ag]=OECD&dq=...&lom=LASTNPERIODS&lo=5&to[TIME_PERIOD]=false&ly[cl]=TIME_PERIOD&ly[rs]=WASTE%2CWST_OPER%2CUNIT&ly[rw]=COU&vw=tb).

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/pallavi17bhatt/E-waste-Analysis.git
    ```
2. Open the desired notebook using Jupyter:
    ```bash
    cd e-waste-management-analysis/notebooks
    jupyter notebook
    ```
3. Run the cells in the notebook to reproduce the analysis.

## Dependencies

The notebooks require the following Python packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these packages using `pip`:
```bash
pip install pandas numpy matplotlib seaborn
