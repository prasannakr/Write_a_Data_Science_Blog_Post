# Write_a_Data_Science_Blog_Post
First project as part of Udacity Data Science Nano degree program

## **Table of Contents:**
1. [Project Introduction](README.md#project-introduction)
2. [File Description](README.md#file-description)
3. [Libraries used](README.md#libraries-used)
4. [Results](README.md#results)
5. [Licensing, Acknowledgements](README.md#licensing-acknowledgements)

## **Project Introduction**<br/>
  For this proect, i was interested in using dataset from CarDekho on used cars to better understand how the selling price is calculated.
I analyzed the following:
  1. What is the age of the car when selling price is the best?
  
  2. Do we sell directly or through a dealer? Does first hand car get more selling price than 2nd/3rd hand etc..
  
  3. Understand the important factors behind selling price using Machine Learning Models.
  
## **File Description**<br/>
    There are two files attached in this repository. First is the excel file, which is the dataset from Kaggle (https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho) and second is the jupiter note book file with the entire analysis answering above questions

## **Libraries Used**<br/>
    Following Python libraries were used for Exploratory data analysis & modeling.
import pandas as pd <br/>
import numpy as np <br/>
import matplotlib.pyplot as plt <br/>
import datetime<br/>
import statsmodels.api as sm<br/>
import seaborn as sns<br/>
from sklearn.linear_model import LinearRegression<br/>
from sklearn.model_selection import train_test_split<br/>
from sklearn.metrics import r2_score, mean_squared_error<br/>
from sklearn.impute import KNNImputer<br/>
from matplotlib.ticker import FuncFormatter<br/>
%matplotlib inline<br/>

## **Results**<br/>
  The main findings of the code can be found at the post available [here](https://prasannakr.medium.com/getting-smart-with-selling-used-cars-ef77257d6c73).
 
## **Licensing, Acknowledgements**<br/>
  Must give credit to CarDekho for the data & the same being available on Kaggle.
