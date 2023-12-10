# Group project, Group 1: Bank Marketing
HWG Ludwigshafen IBAIT Machine Learning Project Group 1   

***Analyzing the Bank Marketing datset.***  

Lecturer: *Dr. Jan P. Portisch*  
Group Members: *Samira Kuklinski, Max Knapczyk, Bela Gallin, Joscha Stähle*  


## Data origin
The Dataset is a widely used data set in machine learning from the UCI (University of California, Irvine) Machine Learning Repository:  
[UCI Repo Website (external)](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
Local copy of the website: [UCI Repo Website (local copy)](Bank%20Marketing%20-%20UCI%20Machine%20Learning%20Repository.html)  
  
The dataset is associated with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls, and often more than one contact to the same client was required, in order to know if the product (bank term deposit) was subscribed or not.  
The dataset was obtained from the direct marketing campaigns of a Portuguese banking institution, which were based on phone calls made from May 2008 to November 2010.  

There are in total 20 inputs with both categorical and numerical variables. The target variable is a binary value indicating whether the client has subscribed a term deposit or not. All client's personal details are fictional in order to protect privacy.  

The dataset has been used in several studies in the fiel of Machine Learning.

# Bank Marketing: Our Data and Approach

The setting and goal of our Dataset was also officially described:  
  
Setting:  
_"The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed."_  

Goal:  
_"The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y)."_  

## Nature of Data
First we looked at the Nature of the Data to get a better understanding of our dataset.  
**[Nature of Data](Nature_of_Data.ipynb)**  

## Learning process
We then started with the Machine Learning process. First, we tried different approaches on a smaller part of the datset.  
There, we conducted our main research:  
**[Learning Notebook](main.ipynb)**     
  
As one next step, we tried to do **feature selection**.  
Train every model without columns that where rated unimportant by feature important test in main. Feature selection might not work for our dataset, as the features rated unimportant changed a lot for each model and small parameter changes. Unfortunately, we found that feature selection didn't improve our results.  
More Details in the **[Feature selection Notebook](main_with_feature_selection.ipynb)**  
  
We also tried to run the optimization completely on the **big dataset**.  
When using the big dataset, we had better results and trained our ***final model***.  
**[Learning Notebook with full dataset](main_full_dataset.ipynb)**