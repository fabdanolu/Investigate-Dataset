# Project: Investigate a Dataset - TMDB Movie Data Analysis

#### BY FABI DANIEL


<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#overview">Project Overview</a></li>
<li><a href="#process">Process Overview</a></li>
<li><a href="#conclusions">Conclusions</a></li>
<li><a href="#ll">Limitations and Learning Curve</a></li>
</ul>


<a id='intro'></a>
#### Introduction
This repository contains the project files both html and ipynb, the dataset in csv and the readme in md. 
The Packages used on this project include: 

* Numpy Version '1.23.1' - For arrays
* Pandas Version '1.4.3' - For 2D Data Structure 
* Matplotlib Version 3.5.2 - For Visualization

<a id='overview'></a>
#### Project Overview
I analyzed the TMDB movie dataset. Originally, the dataset contains 10866 rows and 21 columns. There are missing values and incorrect/impossible values especially in the budget and revenue columns. The dataset contains information about the production team (cast & Directors) and company, the financial records of each film and the ratings. 
Special focus was on two directors and how they rank based on these questions; Steven Spielberg & James Cameron. 
> 1. Top 25 directors with highest profits? 
    The idea is to determine the best performing directors in terms of profits by finding the sum of the differences between revenues and budgets for all their films. This analysis could be improved by adding another variable(count) to the mix, the ratio.
> 2. Top 25 Directors with highest success ratio? 
    Directors success ratio is the ratio of the profits to the total number of films for each director. This is to show the director with the highest profits per film.
> 3. Over the years, whose film has been more popular, James or Steven?

<a id='process'></a>
#### Process Overview

The steps include 
* Data Wrangling - Includes assessing the dataset programmaticaly and performing the necessary cleaning steps
    * Treating Missing Values and Duplicates
    * Making Correcting to Values in Budget and Revenue columns
* Exploratory Data Analysis
* Conclusions



<a id='conclusions'></a>
#### Conclusions
> 1. The number of films directed influences the total profits obviously.
> 2. Steven spielberg is one the greatest director of all time. He has the numbers to back it up. He is the highest grossing director. 
> 3. However taking a deeper dive into the numbers, the numbers show that he has directed more films than the others. James cameron has a very good success ratio top 2 and also rank top 3 in highest profits. 
> 4. Area of further analysis could be in the  correlation between profits and movie count

<a id='ll'></a>
#### Limitations and Learning Curve
* Majority of datasets were unusable due to the fact that some of the rows in Budget and Revenue columns have Zero as values. Dropping those rows was rational.
* Understand all the steps involved in a typical data analysis process
* Comfortable posing questions that can be answered with a given dataset and then answering those questions
* Understand how to investigate problems in a dataset and wrangle the data into a usable format
* Have experience communicating the results of analysis
* Understand vectorized operations in NumPy and pandas to speed up data analysis code
* Familiar with pandas' Series and DataFrame objects, which let you access your data more conveniently
* Understand how to use Matplotlib to produce plots showing your findings


    
