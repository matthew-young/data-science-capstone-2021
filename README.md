# data-science-capstone-2021
 My capstone project for Udacity's Data Science nanodegree program

## Project Definition

In this project we will investigate the American Time Use Survey (ATUS) and use Singular Value Decomposition to see if we can predict what type of occupation someone has based on how they spend their day. We will also take a quick look to see if the data supports Stanley Robert Parker's thesis in The Future of Work and Leisure people who have more say in decision-making at their jobs (autonomy) participate in more active leisure activities than those who have low autonomy in their jobs.

## Results
From thee graphs and difference means, we found the daily activities are not a good way to predict occupation. Although, to the credit of the SVD regression, the predicted values for the test were not much farther off from when we inluded those b values in the SVD.

## Files

### data

ATUSsum.csv - summary statistics of the ATUS activities survey 

ATUSresp.csv - respondents of the ATUS 

### notebook

American Time Use Survey Investigation.ipynb - Jupyter Notebook with the steps taken to look into the data

## Packages

- Pandas
- numpy
- matplotlib

## Special Thanks

- Udacity
- Kaggle
- Paula Hwang
- Steve L Brunton and J Nathan Kutz
- Stanley Robert Parker
- Alexis Van Den Hoogen
