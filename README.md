# Phase-2-Independent-Project
Moringa School
Phase 2 Housing project

# Business Problem
The business problem the client is facing is how to create a successful platform for buying and selling houses in King County. To achieve this goal, the platform needs to provide accurate estimates of house prices, which is crucial for both buyers and sellers.

To accomplish this, the client wants to use a model that can infer the most important features that determine house prices in King County. These features might include factors such as the location of the house, the number of bedrooms and bathrooms, the size of the house, and other relevant factors.

The model needs to be trained on data that accurately represents the real estate market in King County, including historical sales data, current property listings, and other relevant data sources. By using this data, the model can learn to accurately estimate the value of a house based on its features.

Once the model is trained, it can be integrated into the platform to provide buyers and sellers with accurate estimates of house prices, which can help them make informed decisions about buying or selling a property. By providing a reliable and accurate platform for buying and selling houses in King County, the client can establish themselves as a leader in the local real estate market and attract a large and loyal customer base. 


### Project Objectives 
* To identify the key features that significantly influence house prices in King County.
* To develop a model that accurately estimates house prices based on the identified features.
* To evaluate the performance of the developed model in estimating house prices in King County.

# Data Understanding 
I utilized the following dataset to help make predictions of house prices in Kings County 
King County House Data: a dataset that we were provided at the onset of the project. This file contains data for 21,597 homes built in King County, Seattle from 1900 to 2015. Each home in the set contains information regarding features such as number of bedrooms/bathrooms, number of floors, square footage, zip code, condition, and more.

### Data Attribute Information;
* id
* date
* price 
* bedrooms 
* bathrooms 
* sqft_living 
* sqft_lot
* floors
* waterfront
* view
* condition
* grade
* sqft_above
* sqft_basement
* yr_built
* yr_renovated
* zipcode
* lat
* long
* sqft_living15
* sqft_lot15

# Results
### Explaratory Analysis
1. <strong> Number of bedrooms vs Price <\strong> <br>
<img src="https://github.com/Rafael-Muthemba/Phase-2-Independent-Project/blob/907883d7317278ce9ac4ccec40e7475778a0a069/Bedroom%20vs%20price.JPG" alt="example image" width="500" height="250">
<br>
* We saw that as number of bedrooms increase, so too does the price of the house.

<br>
    2. Number of bathrooms vs Price <br>
<img src="https://github.com/Rafael-Muthemba/Phase-2-Independent-Project/blob/3cdf14ebf0bba6d9c856746b43b034e76ab97bbe/Bathroom%20vs%20price.JPG" alt="example image" width="500" height="250">* 
We saw that as number of bathrooms increase, so too does the price of the house.

<br>
    3. Average Price by Grade <br>
<img src="https://github.com/Rafael-Muthemba/Phase-2-Independent-Project/blob/3cdf14ebf0bba6d9c856746b43b034e76ab97bbe/average%20price%20by%20grade.JPG" alt="example image" width="500" height="250">
We can observe that as the grade increases so does the average price of each grouped category, and rise of price from 3 to 9 is gradual then rises sharply 9 to 13

<br>

    4. Price Vs Conditions <br>
<img src="https://github.com/Rafael-Muthemba/Phase-2-Independent-Project/blob/3cdf14ebf0bba6d9c856746b43b034e76ab97bbe/Condition%20vs%20price.JPG" alt="example image" width="500" height="250">
* From this we can see that price increases as the condition of the house increases
* However it appears that houses in poor condition are priced higher than those with fair condition
<br>
    5. Waterfront vs Price <br>
    <img src="https://github.com/Rafael-Muthemba/Phase-2-Independent-Project/blob/3cdf14ebf0bba6d9c856746b43b034e76ab97bbe/Waterfront%20vs%20price.JPG" alt="example image" width="500" height="250">
  From this we can see that houses with waterfronts are expensive by a wide range
