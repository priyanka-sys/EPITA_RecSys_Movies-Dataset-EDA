# Movies-Dataset-EDA

   Exploratory Data Analysis (EDA) in Python

Introduction to EDA in Python

Exploratory data analysis is the analysis of the data and brings out the insights. It’s storytelling, a story which data is trying to tell. EDA is an approach to analyse the data with the help of various tools and graphical techniques like barplot, histogram etc
EDA in Python

There are many libraries available in python like pandas, NumPy, matplotlib, seaborn etc. with the help of those we can do the analysis of the data and bring out helpful insights. I will be using Jupyter Notebook along with these libraries.
Dataset Introduction

The dataset I am using is the ‘The Movie dataset‘ dataset which has different features of These files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.
This dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

This dataset consists of the following files:

movies_metadata.csv: The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.

ratings_small.csv: The subset of 100,000 ratings from 700 users on 9,000 movies.
The Full MovieLens Dataset consisting of 26 million ratings and 750,000 tag applications from 270,000 users on all the 45,000 movies in this dataset can be accessed  
Dataset is Available in the below link :

https://www.kaggle.com/rounakbanik/the-movies-dataset

Exploratory Data Analysis in Python

First, we will import all the libraries that are required for EDA (Exploratory Data Analysis). This is the first and most important thing to do. Without importing libraries, we will not be able to perform anything.
Import Libraries

  from pathlib import Path
         import numpy as np
         import pandas as pd
         import seaborn as sns
         import matplotlib.pyplot as plt
         from scipy import stats
Data loading

After importing the libraries, the next step is loading data into the dataframe. To load the data into the dataframe, we will use pandas library. It supports various file formats like Comma Separated Values (.csv), excel (.xlsx, .xls) etc. 
To read the dataset, either store the data file into the same directory and read it directly, or provide the path of the data file where the dataset is located while reading the data.
Endnotes

All the above steps are part of EDA. This is not the end of EDA. All the steps above performed are the basics which should be performed to analyse the data before doing feature engineering or modelling.

EDA is one of the important steps during the whole process of data science. It is said that most of the time of model building goes into EDA and feature engineering. If you want to create a big set up of information from the data, you need to do an extensive EDA.

 	


