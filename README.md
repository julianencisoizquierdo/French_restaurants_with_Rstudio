# Visualisations with ggplot - Analysis of French restaurants

## Content of the project
The aim of this project is to analyse a dataset containing. For the most part, it makes use of different features of ggplot, as well as of basic transormations of the dataset (group_by, summarise, select, join_left, etc.). 


## Instructions
Three files needed for running the code are:
- `df_france.rds`: .
- `df_paris_arrond.rds`:
- `df_paris_regions`:
- `df_paris_regions_centroid`:
- `df_regions_arrond`:
- `df_restaurant_regions`:




## Methodology
The following are the main transformations performed in the dataset:
- Delete the Fare column. The reason is that it is very correlated with the Class column




### Machine Learning Methodology


### Results and Discussion



## Usage

To run the analysis, open the `titanic_julian_enciso.ipynb` notebook and execute each cell sequentially. Ensure that the required datasets are in the correct file paths.


## Dependencies

The following libraries are used in different parts of the project:
- Pandas
- Numpy
- Matplotlib.pyplot
- Seaborn
- Os
- Xgboost
- Lightgbm
- Sklearn.ensemble
- Sklearn.linear_model
- Sklearn.svc
- Sklearn.neighbors
- Sklearn.naive_bayes
- Sklearn.tree
- Sklearn.model_selection
- Sklearn.preprocessing
- Sklearn.metrics


Proceed to their installation with the following code:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import os
import xgboost as xgb
import lightgbm as lgb
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn.neighbors import KNeighborsClassifier
from sklearn.naive_bayes import GaussianNB
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
```

## Installation
Ensure that you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).


## Usage
You are allowed to view and fork the repository for personal use. If you have any questions or would like to discuss potential collaborations, feel free to reach out.


## Contributing
Although this project is not open-source, I welcome feedback, bug reports, and suggestions. If you encounter any issues or have ideas for improvements, feel free to send me an email to julian.enciso.izquierdo@gmail.com.


## License
This project is not open-source, and it does not come with a specific open-source license. All rights are reserved, and usage, modification, or distribution of the code is not permitted without explicit permission.

If you are interested in using or collaborating on this project, please send me an email to julian.enciso.izquierdo@gmail.com.

## Acknowledgments
The project uses data from Startup_Dataset.xlsx, which was kindly shared by Professor Howard Zhong. Special thanks to him for his valuable feedback.
