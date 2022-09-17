# Estimating diamond prices
 
Status: Completed

## Objective
#### Scenario: Rick Harrison and his family own and run a pawn shop in Las Vegas. They purchase, sell and evaluate interesting artefacts with fascinating stories. In this episode of Pawn Stars, Rick has 5000 diamonds and he’s called you to valuate them.

#### Goal: Your job is to upload a .csv file containing the diamonds and a new column 'price_predicted' with the predictions of your linear model using the historical database you are given. Your goal is to create a prediction that will obtain a root mean squared error below 900 dollars.

## Technologies
- Python 

## Project Description
In this project I used a historical data of diamonds shared by Ironhack, Rick's list of diamonds and, lastly, the Streamlit website to upload all .csv test files. The historical dataset contained each diamond's carat quantity, depth, price and other details.

The Streamlit website can be found here: <https://daft-oct2020-rick-diamonds.herokuapp.com/>

## Steps

1) Accessing database
> In this case, using Python

2) Understanding database
> Measuring correlation between variables and price

3) Comparing historical database with Rick's database
> Eliminating entries below or above Rick's minimum and maximum values since they wouldn't improve the model

4) Testing different combinations for the linear model
> Building the model using distinct columns and later introducing categoric variables to create different model combinations

## Conclusion

#### From all tests, the best model considers carat, depth, table and x for each combination of color and clarity, and has a root mean squared error of 709.

## Contact
  
If you have any questions or comments, please let me know!
  
https://www.linkedin.com/in/carolinatannus/
 
