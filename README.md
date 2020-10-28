# Recommendation Engines with IBM Data

## Table of Contents
* Libraries
* Project Motivation
* File Descriptions
* Licensing, Authors, and Acknowledgements

## Libraries
The libraries used in this repository are:
* pandas
* numpy
* matplotlib
* nltk


## Project Motivation
The purpose of this project is to recommend articles to the users of IBM Watson. For this purpose 4 different recommendation approach were involved. 
* Ranked based recommendations
* Collaborative filtering
* Content based recommendations
* Matrix Factorization 

You can find a brief introduction to recommendation engines here: https://medium.com/@nkibrislioglu/how-do-recommendation-systemswork-10e17f07fea5

### Understanding the data
There are two data sets:  

**User item interaction data:** This data set consists of three columns: article id, article title and user email. We are going to use user email column as user id. This data is stored in user-item-interactions.csv

**Article content data:** This data set consists of five columns. First column includes the actual document data. Second column includes description of the article. Third column includes the name of the article. Fourth column includes docuement status live or not and the last column includes article id.

You can find additional information about the data in 1_Exploratory_Analysis.ipynb file.


## File Descriptions
There are five jupiter notebooks and two csv files in this repository. Data files were explained under the understanding the data section. File names are 
* 1_Exploratory_Analysis.ipynb: Importing and cleaning data
* 2_Ranked_based_recommendations.ipynb: Functions for ranked based recommendations
* 3_Collaborative_Filtering.ipynb:  Functions for collaborative filtering
* 4_Content_based_recommendations.ipynb: Creating content domains and providing content based recommendations
* 5_Matrix_Factorization_SVD.ipynb: Recommendations with singular value decomposition

## Licensing, Authors, and Acknowledgements
IBM data set is used in this project. 
##### Note: This repository is part of Udacity Data Science Nano degree program projects

