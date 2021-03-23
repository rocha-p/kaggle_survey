# <center> Kaggle Survey Analysis </center>
### <center> By Pedro Ignacio Rocha </center>
-------

## Table of Contents

1. [Installation and Libraries](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation and Libraries  <a name="installation"></a>

Python version: `3.8.5`

You will need to install the following libraries:

* Pandas `import pandas as pd`
* Numpy `import numpy as np`
* Matplotlib `import matplotlib.pyplot as plt`
* Defaultdict`from collections import defaultdict`

## Project Motivation<a name="motivation"></a>
In this project I analyze [2017 Kaggle Machine Learning & Data Science Survey](https://www.kaggle.com/kaggle/kaggle-survey-2017), in order to answer the following questions:

* Which jobs give more satisfaction?
* Another insights in job satisfaction
* What platforms people use to learn?
* How much time people spend studying Data Science?
* What languages people recommend to learn?
* What skills do users think are the most necessary for a career in Data Science?

## File Descriptions <a name="files"></a>
Repository structure:
    
    kaggle_survey_analysis/                  # folder
    ├── README.md                            # read.me file 
    ├── multipleChoiceResponses.csv          # data set
    ├── schema.csv                           # data set schema
    ├── Kaggle_Survey_Project.ipynb          # Jupyter notebook with the analysis

All the .csv used in the analysis are download from Kaggle. You can check the files [in this link](https://www.kaggle.com/kaggle/kaggle-survey-2017).

## Results<a name="results"></a>

The conclutions of the analysis are:

* ML engineers and Data scientists are the jobs with the best satisfaction score.
* It seems that how much our work fits with the title has a lot to do with the satisfaction that the job position can give us.
* The more remote work the greater the satisfaction
* Kaggle and online courses are the most used options to learn by Kaggle users.
* Coursera and Udacity are the most used platforms to enroll online courses
* Python, followed by R and SQL are the recommended programming languages by Kaggle users
* Python, statistics and visualizations are the Top 3 skills consider consider most necessaries.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
You can find the Licensing for the data and other descriptive information in Kaggle.
The link to the Data Set: [2017 Kaggle Machine Learning & Data Science Survey](https://www.kaggle.com/kaggle/kaggle-survey-2017)

You can check my blog about this project in this [Medium Link](https://rochapedroignacio.medium.com/these-advices-from-kaggle-users-will-make-your-career-easier-e347858a394d)
