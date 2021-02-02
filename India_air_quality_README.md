# Machine Learning CA01
Ziyao Cui

## Name of project
India Air Quality

## Project Overview 
This project use dataset related to India air quality in the past 25 years, purpose of this project is to understand air pollution level in India. There are different factors that can cause air pollution in India.

## Instruction
Please download the India_Air_Quality_CA01.ipynb file and upload into Google Colab to run the code.

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
This first step I did is to improt all packages that I will use later. And I import the 'data_csv' to cloab and name the raw data 'df'.
Next step is initial data investigation section, in this part I summarized basic information about the raw data df.
```python
df.describe  #output will be statistical description of the data.
df.shape  #output is the total number of rows and columns of the data which is 435742 rows and 13 columns.
df.count()  #output shows how many non-null numbers each column.
df.isnull().sum()  ##output shows how many null numbers each column.

```






