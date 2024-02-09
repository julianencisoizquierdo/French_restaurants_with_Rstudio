# Visualisations with ggplot - Analysis of French restaurants

## Outline of the project
The aim of this project is to analyse datasets containing information about French restaurants and their locations. An important personal goal was to develop a good understanding of different features of ggplot. Additionally, working on this project helped me getting better performing common dataset transformations (group_by, summarise, select, join_left, etc.). 


## Instructions
Three files needed for running the code are:
- `df_france.rds`: this dataset contains information about more 33,584 French restaurants. The attributes include the location, the price level, the features, the type of cuisine, amongst others.
- `df_paris_arrond.rds`: it contains information about certain geometric features of the different arrondissements
- `df_paris_regions.rds`: it cointains geometric information about the departments (i.e: the elements of the arrondissements)
- `df_paris_regions_centroid.rds`: it contains some geometric information about the departments as well. In this case, the unique identifier of the departments are contained in the column l_qu. 
- `df_regions_arrond.rds`: this maps the departments to the arrondissements
- `df_restaurant_regions.rds`: this table contains information about Parisian restaurants


## Content overview
The following are the main transformations performed in the dataset:
- Scatterplot with geographic data (the location of the restaurants)
- Map of Paris, with a border for the arrondissements and another for the departments
- The same map with two different fillings. Firstly with the absolute review counts, and then with a ratio of the review count to the population of the department
- A frequency polygon that shows the distribution of reviews across different cities
- Density plots for the distribution of reviews across cities and across price levels
- A heat map of the cities and the different price levels


## Usage

To run the analysis, open the `French_restaurants_analysis.Rmd` notebook and execute each cell sequentially. Ensure that the required datasets are in the correct file paths.


## Dependencies

The following libraries are used in different parts of the project:
- tidyverse
- ggplot2

Proceed to their installation with the following code:

```
library(tidyverse)
library(ggplot2)
```

## Installation
Ensure that you have RStudio installed on your system. If not, you can download it from https://posit.co/downloads/. 


## Usage
You are allowed to view and fork the repository for personal use. If you have any questions or would like to discuss potential collaborations, feel free to reach out.


## Contributing
Although this project is not open-source, I welcome feedback, bug reports, and suggestions. If you encounter any issues or have ideas for improvements, feel free to send me an email to julian.enciso.izquierdo@gmail.com.


## License
This project is not open-source, and it does not come with a specific open-source license. All rights are reserved, and usage, modification, or distribution of the code is not permitted without explicit permission.

If you are interested in using or collaborating on this project, please send me an email to julian.enciso.izquierdo@gmail.com.

## Acknowledgments
Special thanks to Mostafa Rezaei for his instructions and guidance.
