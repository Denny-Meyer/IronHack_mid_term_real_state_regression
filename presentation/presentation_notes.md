
story:

Building a house price prediction model for a Real Estate company
The company provided the dataset related to the properties in King county in the state of Washington
The request was to build a regression model to achieve a higher property price predictability
How to get a better price for a given property?

What impacts the prices?
Does the below features impact the price:
- waterfront-Denny
- Location-Denny
- Grade-Denny
- condition-Denny
- year built-Srini
- sqft living-Srini
- year_renovated-Srini
- seasonality (which months have higher sales and better prices?)-Srini
- map avg_price, location

Options to showcase a house prediction:
1. Jy Notebook calculation. Input and output in the same file or notebook
2. Jupyter(input) and Tableau (display results)
    Input: create a form in Jupyter notebook to input data for price prediction
    Calculation: Jupyter notebook calculates the price prediction results from the regression model and 
    Display: Tableau. Export the results in a predefined excel or df or file format, which can be imported into Tableau with the same file naming convention
3. Apply the linear model coefficients in Tableau? after freezing the Jupyter notebook.

Additional features in Tableau:
A prospective buyer/seller approaches for a purchase or sale of a property in King county to understand the possible price prediction.
Use filter option with input option in the Tableau.



commentary:
 We are here to discuss a regression model we build for a real estate company that deals with king county properties in the state of washington. The idea is to come up with a regression model to understand what drives prices and to predict the house prices.

Paradox:
Would you pay more for an older building. Ideally the older the building the lower the price?

high sqft_living does not always result in higher prices. it depends.
give examples

Let's explore...

 
Let's take a look at what is happening.
The average price per sqft living ($326) is higher for the older houses compared to the ones built in the last 58yrs, which has a price average of $240.
Irrespective of whether the Waterfront houses built before 1959 or after 1959 the price per sqft is $505. Roughly equal number of houses were built in both the periods.

The average price per sqft living with waterfront 508 is higher than a non-waterfront 262, despite the age of waterfront houses being older with 52.11yrs old vs the average age of 43.3.
The top ten zipcodes with avg price per sqft lie on waterfront, half of them are older than the average age of the building.

Average age of the house is 43.32

The average price per sqft living @$280.75 are higher than the properties without renovation at @$266.72

And the results show that that our initial notions are not true. The Tableau visualisation show us that the waterfront, Location, grade, condition and moderately driven by sqft_living and year_renovated.
Does our model speak the same language.
Here.... we explain briefly what we did in the model and then show them the coefficients and the arrived R2....

After analysing the dataset of 21.5k records with a train set of 80%, we came up with a regression model which has a R2 of 0.86 and MSE of ...,






 










