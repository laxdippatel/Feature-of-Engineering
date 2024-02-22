# Feature Engineering & Feature Selection
## Motivation

Feature Engineering & Selection is the most essential part of building a useable machine learning project, even though hundreds of cutting-edge machine learning algorithms coming in these days like deep learning and transfer learning. Indeed, like what Prof Domingos, the author of  'The Master Algorithm' says:

> “At the end of the day, some machine learning projects succeed and some fail. What makes the difference? Easily the most important factor is the features used.”
>
> — Prof. Pedro Domingos
![image](https://github.com/laxdippatel/Feature-of-Engineering/assets/102856079/8c38054f-c5f5-4053-bbea-d060e8f2df38)

Data and feature has the most impact on a ML project and sets the limit of how well we can do, while models and algorithms are just approaching that limit. However, few materials could be found that systematically introduce the art of feature engineering, and even fewer could explain the rationale behind. This repo is my personal notes from learning ML and serves as a reference for Feature Engineering & Selection.


## Download

Download the PDF here:
 [**PDF Download**](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.pdf)

Same, but in markdown:

- [**Mark Down Download**](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md)

PDF has a much readable format, while Markdown has auto-generated anchor link to navigate from outer source. GitHub sucks at displaying markdown with complex grammar, so I would suggest read the PDF or download the repo and read markdown with [Typora](https://typora.io/).


## What You'll Learn

Not only a collection of hands-on functions, but also explanation on  **Why**, **How** and **When** to adopt **Which** techniques of feature engineering in data mining. 

- the nature and risk of data problem we often encounter
- explanation of the various feature engineering & selection techniques
- rationale to use it
- pros & cons of each method 
- code & example



## Getting Started

This repo is mainly used as a reference for anyone who are doing feature engineering, and most of the modules are implemented through scikit-learn or its communities.

To run the demos or use the customized function,  please download the ZIP file from the repo or just copy-paste any part of the code you find helpful. They should all be very easy to understand.

**Required Dependencies**:

- Python 3.5, 3.6 or 3.7
- numpy>=1.15
- pandas>=0.23
- scipy>=1.1.0
- scikit_learn>=0.20.1
- seaborn>=0.9.0



## Table of Contents and Code Examples

Below is a list of methods currently implemented in the repo. 

**1. Data Exploration**

  -    1.1 Variables 
  -    1.2 Variable Identification  
       -  Check Data Types   [[guide]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#11-variables)  [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)
  -    1.3 Univariate Analysis  
       -  Descriptive Analysis   [[guide]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#13-univariate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)  
       -  Discrete Variable Barplot   [[guide]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#13-univariate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb/master/1_Demo_Data_Explore.ipynb)  
       -  Discrete Variable Countplot   [[guide]](https://github.com/ashishpatel26/Amazing-Feature-Engineering/blob/master/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#13-univariate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)  
       -  Discrete Variable Boxplot   [[guide]](https://github.com/ashishpatel26/Amazing-Feature-Engineering/blob/master/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#13-univariate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)  
       -  Continuous Variable Distplot   [[guide]](https://github.com/ashishpatel26/Amazing-Feature-Engineering/blob/master/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#13-univariate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)
  -    1.4 Bi-variate Analysis  
       -  Scatter Plot   [[guide]]((https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb))   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)  
       -  Correlation Plot   [[guide]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#14-bi-variate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)  
       -  Heat Map   [[guide]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md#14-bi-variate-analysis)   [[demo]](https://github.com/laxdippatel/Feature-of-Engineering/blob/main/1_Demo_Data_Explore.ipynb)

