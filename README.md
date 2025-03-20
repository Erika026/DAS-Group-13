# DAS-Group-13
## Introduction 
Given the coffee dataset with the features of coffee and overall quality scores from the Coffee Quality Institute, aiming to provide key information to the local coffee farmers and help them improve coffee production with higher quality.
 
The Generalized Linear Model (GLM) was applied to explore the most influential factors affecting the quality class of the coffee batch.
## About the Repository
The repository contains files needed for the DAS project, including the main file `Group_13_Analysis.qmd` and the dataset `dataset13.csv`.  
The output result could be checked visually through `Group_13_Analysis.html`and `Group_13_Analysis.pdf`.
## The dataset
`dataset13.csv` contains the binary response variable `Qualityclass` with the result either *Poor* or *Good* and the potential explanatory variables `aroma`, `flavor`, `acidity`, `altitude_mean_meters`, `category_two_defects`, `harvested` and `country_of_origin`.

The variables `aroma`, `flavor`, `acidity`, `altitude_mean_meters`, and `category_two_defects` are all continuous variables while `country_of_origin` is categorical.
Notice that the `harvested` year was treated as the continuous variable in this study (the same insignificant result is produced for the harvested year, regardless of whether it is treated as a continuous variable or a categorical variable.) 
## Built-in Package
```
library(tidyverse)
library(moderndive)
library(gapminder)
library(sjPlot)
library(stats)
library(jtools)
library(gt)
library(MASS)
library(knitr)
library(broom)
library(GGally)
library(ggplot2)
library(dplyr)
library(broom)
```
## Contributers
Yiming Guo, Shuyi Hu, Qihao Su, Guanxu Wang, Shiqi Wang
