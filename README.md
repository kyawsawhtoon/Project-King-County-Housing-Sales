# Mod1_Project - King County House Sales

# Repository Files
The followings are the file you can find in this repository and their descriptions.
- Mod 1 -                   Project Final.ipynb - Module 1 Project's Jupyter Notebook.
- presentation.pdf -        High-level presentation of your methodology and recommendations for non-technical stakeholders
- README.md -               Descriptions of contents of the repository
- kc_house_data -           Original dataset of King Country House Prices

# Project Motivation
This is my module 1 project for Flatiron Data Science Selft Paced Program. This is my very first data sciene project. The purpose of this project is to construct a multiple linear regression model that can be used to predict the house prices. I will use the King County House Sales dataset to construct my model.

# Project Process

My approach for this project is to follow the OSEMN framework. The steps of this framework is as follow -

1. Obtain the data
2. Scrub the data
3. Explore the data
4. Model the data
5. Interpret the data

# The Model

ln(Y) = 12.2612 + 0.1919 G + 0.0002 *ln(L) - 0.0502 B

Y = Price
B = Bathrooms
L = Squared Footage of House
G = Grade

The following points can be analyzed from the model - 

- The predictor variables explain 35% of changes in house prices
- Average price of employ lots is $211,335
- Square footage of the house impacts the most on the house prices
- Grade of the house is the second most influential factor
- The number of bathrooms contributes the least
- The number of bathrooms is negatively related to the price

# Interpreting the Model

The coefficients in my model can be interpretted as below - 

- Price increases by 33% for every 100% square footage increase
- Price increases by 18% for every 50% square footage increase

![alt text](https://user-images.githubusercontent.com/29743560/93523609-4ec46a00-f901-11ea-9bb1-ec38e5776180.JPG)

- Price increases by 21% for every grade increase

![alt text](https://user-images.githubusercontent.com/29743560/93523612-4ec46a00-f901-11ea-8229-c50596329fa8.JPG)

- Price decreases by 4.9% for every bathroom added
- The grade and square footage remain fixed

![alt text](https://user-images.githubusercontent.com/29743560/93523614-4f5d0080-f901-11ea-976f-add13611ec42.JPG)



