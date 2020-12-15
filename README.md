# Write_a_Data_Science_Blog_Post
First project as part of Udacity Data Science Nano degree program

## H2**Table of Contents:**
1. [Project Introduction](https://github.com/prasannakr/Write_a_Data_Science_Blog_Post/blob/main/README.md#-Project-Introduction)
2. [File Description](https://github.com/prasannakr/Write_a_Data_Science_Blog_Post/blob/main/README.md#-File-Description)
3. Libraries used
4. Results
5. Licensing, Acknowledgements

**Project Introduction**<br/>
  For this proect, i was interested in using dataset from CarDekho on used cars to better understand how the selling price is calculated.
I analyzed the following:
  1. What is the age of the car when selling price is the best?
  
  2. Do we sell directly or through a dealer? Does first hand car get more selling price than 2nd/3rd hand etc..
  
  3. Understand the important factors behind selling price using Machine Learning Models.
  
**File Description**<br/>
    There are two files attached in this repository. First is the excel file, which is the dataset from Kaggle (https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho) and second is the jupiter note book file with the entire analysis answering above questions

**Libraries Used**<br/>
    Following Python libraries were used for Exploratory data analysis & modeling.
import pandas as pd 
import numpy as np 
import matplotlib.pyplot as plt 
import datetime
import statsmodels.api as sm
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_squared_error
from sklearn.impute import KNNImputer
from matplotlib.ticker import FuncFormatter
%matplotlib inline

**Results**<br/>
  The main findings of the code can be found at the post available here.
 
**Licensing, Acknowledgements**<br/>
  Must give credit to CarDekho for the data & the same being available on Kaggle.
