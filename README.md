# A Northwestern County House Sales Analysis

Author: TROY STEVE




![WhatsApp Image 2022-07-04 at 3.22.39 AM]





### Problem:
We will use regression modeling to analyze house sales in a northwestern county. Our aim is to predict the house prices so that we can enlighten anyone who wants to get into this business on which features lead to better sale prices

### Data
This project uses the King County House Sales dataset. The dataset has features id, date, bedrooms, bathrooms, sqft_living and many others and price as our target. 

### Methods
The data cleaning, processing and exploration was done. Later, regression models were build. 

### Results
The features that affect the price of a house in Kings County are sqft_living, grade,bedrooms, waterfront and sqft_basement.
The p-values of these features were all below 0.05 and our validation score was higher than the test score of the r-squared test.


### Recommendations
Those who wish to increase the prices of their houses should consider constructing or adding the square footage of their houses. In so doing, they should endevour using quality materials in order to increase the grade of the houses. More bedrooms also has a positive relationship with the house prices.


### Limitations and Next Steps
Althought our model tries to predict prices in the best way possible, more analysis will be need to be done. This is because we still violated some assumptions even after doing away with some features in order to deal with multicollinearity. We removed the outliers from our price column. This means that our model doesn't predict correctly the extreem prices.

### REPOSITORY STRUCTURE

```bash
├── code
├── data
├── images
├── _index_.ipynb
├── _init_.py
├── README.md
 ```