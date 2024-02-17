# House pricing linear regression using regularization
> This project aims to find the variables that are significant in predicting the prices of housing and how well the price varies with the variables.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset is about a US-based housing company named Surprise Housing that has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company wants to know
which variables are significant in predicting the price of a house, and how well those variables describe the price of a house. 
- We have used linear regression with regularization  to understand the variables that are influencing the prices of the houses.
- There are 3 models which have been built. One model uses linear regression only and the second uses Ridge regularization and the third model uses Lasso regularization.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimal value of alpha in Ridge regression is 10.0 and the optimal value of alpha in Lasso regression is 0.001.
- The R2 score of train data with optimum alpha is 94.9 ( For Ridge regression) and 92.9 (For Lasso regression). 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - Version 1.5.3
- Matplotlib - Version 3.7.1
- Seaborn - Version 0.12.2
- statsmodels
- sklearn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project has been developed as part of Upgrad IIITB programme for AI and ML course's case study


## Contact
Created by [@josephmattamana90] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->