# R-Wine-Project
Spring 2019 5205 FRAMEWORKS & METHODS II Group Project

Description of the data:
The dataset is shared by Zack Thoutt on Kaggle.com planning to use deep learning to predict the wine variety using words in the description/review. The dataset is built to create a predictive model to identify wines through a blind tasting as a master sommelier would. The data was scraped from WineEnthusiast during the week of June 15th, 2017. 
Source: https://www.kaggle.com/zynicide/wine-reviews

Project Objective:
This project is aiming at helping wine buyers search wine that best matches their needs and preferences. We start with our business goal and reverse engineer the process of designing such system to achieve our goal. The project includes 4 steps: 1) analyzing the data of existing wine buyers to design a questionnaire that can best reflect the needs and preferences of potential buyers. 2) Collecting the information from the questionnaire and query data from the database(wine dataset). 3) Returning a list of wine that best matches buyers’ interests. 4) Trying other techniques to find useful information to help wine buyers make decision. 

Use of Analytical Techniques: 
1)	Data cleaning: tidyr, mice package, cbind()
2)	Data visualization: ggplot2
3)	Text mining: freq_terms() in the qdap package, wordcloud
4)	Association rules: inspect() in the arules package and apriori()
5)	R Dashboard: flexdashboard and shiny package.
6)	Predictive models: decision tree and linear regression
7)	User based recommender system: recommenderlab package 

Submission:
1. cleaned dataset (data.new.csv) 
2. Working R code for Analysis (Working R code.Rmd)
3. Final R Code for Analysis and Conclusions (Final R Code.Rmd) 
4. R code for dashboard/application built (Final Project - Dashboard.Rmd)
5. A wrote-up report including data cleaning process, reasons behind the choice of analytical techniques and conclusions from analysis.(Write up.docx)
6. Presentation slides (Final Presentation.pdf)
