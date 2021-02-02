## Name of project
India Air Quality

## Project Overview 
This project use dataset related to India air quality in the past 25 years, purpose of this project is to understand air pollution level in India. 

SPM, RSPM, CO2, SO2 are important factors that can cause air pollution in India, using these variables to analyze different pollution level in each state in India.

## Instruction
Please download the India_Air_Quality_CA01.ipynb and data.csv (link below) file and upload into Google Colab to run the code.

## Installation instructions
Use the following packages:

```bash
pandas
numpy
sklearn.impute
matplotlib.pyplot
```
## Usage 
```python
import pandas as pd 
import numpy as np 
from sklearn.impute import SimpleImputer  #Imputation of missing values
import matplotlib.pyplot as plt  #Plotting
```

## Operating instructions
1. This first step I did is to improt all packages that I will use later. And I import the 'data_csv' to cloab and name the raw data 'df'.
2. Next step is initial data investigation section, in this part I summarized basic information about the raw data df.
3. Next clean the data by dropping less important columns and drop missing values. 
4. Plot important variables and compare them. 

## Colab access
https://drive.google.com/file/d/1IUaEthmXs5knNQPjq7qpSQNUZrE2Rb05/view?usp=sharing

## Data
https://www.kaggle.com/shrutibhargava94/india-air-quality-data

## Contact information
Name: Ziyao Cui


