# Automobile Data Analysis
<img src="https://www.classic-cars-for-rent.com/assets/images/home-header.jpg" alt="classic-car">  

## Table of Content
1. [Problem Description](#chapter1) 
2. [Goal](#chapter2)
3. [Dataset Description](#chapter3)
4. [Data Cleaning notebook](#chapter4)
5. [Exploratory Data Analysis notebook](#chapter5)
6. [Snapshots of Exploratory Data Analytsis](#chapter6)
7. [Conclusion](#chapter7)

## Problem Description <a class="anchor" id="chapter1"></a>
Let's say we have a friend name Tom. And Tom wants to sell his car. But the problem is he doesn't know how much he should sell his car for. Tom wants to sell his car for as much as he can. But he also wants to set the price reasonably, so someone would want to purchase it. So, the price he sets should represent the value of the car.
How can we help Tom determine the best price for his car? Let's think like data scientists and clearly define some of his problems. For example: 
- Is there data on the prices of other cars and their characteristics? 
-	What features of cars affect their prices? 
-	Does horsepower also effect the selling price, or perhaps something else like Color or Brand? 
As a Data Analyst or Data Scientist, these are some of the questions we can start thinking about.
## Goal <a class="anchor" id="chapter2"></a>
The goal of this project is to determine which car features that best predict its price.
## Dataset Description <a class="anchor" id="chapter3"></a>
<img src="Snapshots\Attributes.png" alt="Attributes">      
Just a quick note the dataset is actually from 1985.  
        
## Data Cleaning notebook <a class="anchor" id="chapter4"></a>

<ol>
  <li>Basic Insight of Dataset</li>
  <li>Data Wrangling</li>    
  <ol>       
    <li>Identify and Handle Missing Values</li>
    <li>Correct Data Format</li>
    <li>Data Standardization</li>
    <li>Data Normalization</li>
    <li>Binning</li>
    <li>Indicator Variable (Dummy Variable)</li>
   </ol>     
</ol>     
         
## Exploratory Data Analysis notebook <a class="anchor" id="chapter5"></a>

<ol>       
  <li>Analyzing Individual Feature Patterns using Visualization</li>
  <ol>
    <li>Numerical variables</li>
    <li>Categorical variables</li>
  </ol>
  <li>Descriptive Statistical Analysis</li>
  <li>Grouping</li>
  <li>Correlation</li>
  <li>ANOVA</li>
</ol>
          
## Snapshots of Exploratory Data Analytsis <a class="anchor" id="chapter6"></a>

<img src="Snapshots\body-style-vs-price.png" alt="body-style-vs-price">  
<img src="Snapshots\engine-size-vs-price.png" alt="engine-size-vs-price"> 
<img src="Snapshots\Heatmap-drive-wheels-body-style-and-price.png" alt="Heatmap">
        
## Conclusion <a class="anchor" id="chapter7"></a>      
We now have a better idea of what our data looks like and which variables are important to take into account when predicting the car price. We have narrowed it down to the following variables:

Continuous numerical variables:

- Length
- Width
- Curb-weight
- Engine-size
- Horsepower
- City-L/100km
- Highway-L/100km
- Wheel-base
- Bore

Categorical variables:

- Drive-wheels
