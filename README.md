# CS_510_Midterm_Project_A Statistician’s Priority List for Boosting Home Value

## Purpose
The primary objective of this project is to find out a priority list for home improvement that can be helpful for boosting home values from a statistician’s view. Commonly used house attributes would be analyzed and the project would be planned to figure out the most relevant features of a house regarding sale prices. Hopefully, this project could offer some suggestions on house improvement and home value boosting for home investors during their stay.

## How to Run
Copy this repository and open **MidtProject.Rproj** in RStudio. 

Open **Mid Project_Home values.Rmd**. Proceed to install all associated libraries and run each file.

## Data
A real-world dataset that contains house sale price information and the corresponding house features of King County, Washington from 2014 to 2015 will be used. It is originated from Kaggle, and can be imported to R from mlr3data package. Basically, there are 21,613 observations along with 19 house features such as the number of bathrooms, bedrooms, floors, and square footage of the housein the original data. 

## Packages 
The first package that will be used in this project is mlr3data, which offers the dataset that we are going to analyze. Besides, we will use the ggplot2 and lattice packages for the purpose of data visualization and randomForest for random forest models that can be helpful to analyze the effects of the house factors on the house price. Also, we will utilize the stargazer package to offer neat and more readable model results of linear regressions. Anotehr important package that can be useful in this project is GGally, in which the ggcorr function can help us obtain the correlation matrix. Finally, we also use the dplyr package to manipulate and modify data frames.

## Conclusion
Based on the codes, a priority list for boosting home value should contain the following two things:
1.Try to maintain the house in a good condition and add more custom design so that it can be graded higher.
2.Try to expand the space of living room in the house.

Ones can compare the codes outputs of .Rmd file with the outputs of **Updated_Mid Project_Home values.pdf**. 
