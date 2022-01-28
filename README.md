# Tanzanian Water Wells: Classification Analysis

![image](https://user-images.githubusercontent.com/84855671/151582831-80e1a279-22c3-4649-9be6-fdd8f660e8a0.png)

**Authors**: Olgert Hasko, Ross McKim, Hatice Erdogan, Madoria Thomas

## Overview

[Tanzania](https://www.britannica.com/place/Tanzania) is an East African country with about 59,678,000 in population (2021 est.), and located just south of the Equator. Tanzania is a developing country that has struggles with providing clean water to its entire population. There are many water points already established in the country, but some are in great need of repair while others have failed altogether. Water availability has a major impact on the health, well-being, and economic potential of the people. 

***

## Business Problem

Our NGO, Danida, is focused on finding and replacing water wells that need repair. Our classification model is being used to better predict which wells in the area are operational, need repairs or are non-functional using various information such as when each well was installed, who funded the project, and population around each well. Any improvement in determining the best wells to install or in the predictability of which wells need repairs could have an enormous impact on the people of Tanzania. 

**Our goal is to provide answers to questions such as:**<br />
Can we better predict which wells will become non-functional or need repair?
What factors influence whether a well may be broken or needing repairs?<br />
What companies or organizations are more effective at maintaining their wells?<br />
Best water extraction options to keep well operational?<br />

***

## Data

We are using the Tanzanian Water Wells data set hosted by DrivenData and a part of the active competition [Pump it Up: Data Mining the Water Table](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/). We were provided with 3 datasets in total with dates ranging from 1960- 2013. 

This is a basic overview of each dataset:<br />
Training set values: 59,400 observations, 40 variables<br />
Test set: 14,850 observations, 40 variables<br />
Training set labels: 59,400 observations; which contains our target variable which is 'status_group'<br />

'status_group' has the following well categories of 'Functional', 'Functional needs repair', and 'Nonfunctional' 

***
## Methods

We are doing an iterative classification analysis on the functionality of water wells in Tanzania. We made multiple alterations in the process while comparing the improvements for each model built. We started off first with a Dummy model to get our baseline predictions. Then we moved on to Logistic Regression, Decision Trees, ExtraTrees, HistGradientBoost, Catboosted, and finally a Random Forest to achieve our final results. 

***

## Results



***
## Recommendations and Conclusions
**We have identified the regions that need the most assistance:<br />**
-Lindi (1816 non functional wells)<br />
-Mtwara (638 wells need repairs)<br />

**The best ways to extract water to maintain well operationality:<br />**
-Gravity<br />
-Handpump<br />

**Prioritize wells which provide for larger communities**

***
## For More Information

Please review our full analysis in our [EDA](https://github.com/OlgertHasko/Tanzanian-Water-Wells/blob/main/EDA.ipynb) and [Final](https://github.com/OlgertHasko/Tanzanian-Water-Wells/blob/main/Final.ipynb) Jupyter Notebooks or our presentation.

If you have any additional questions about our project, please feel free to contact us at:<br />
**Olgert Hasko: https://www.linkedin.com/in/olgert-hasko-47519097/**<br />
**Ross McKim: https://www.linkedin.com/in/ross-mckim/**<br />
**Hatice Erdogan: https://www.linkedin.com/in/haticekastan/**<br />
**Madoria Thomas: https://www.linkedin.com/in/madoria-thomas-2b9637133/**<br />

***

## Repository Structure

```
├── README.md                           
├── Final.ipynb   
├── EDA.ipynb
├── catboost_info
├── Models                                
└── Data                              
```
