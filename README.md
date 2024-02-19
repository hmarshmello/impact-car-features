# Impact of Car Features
**Problem Statement:** 

To find optimized pricing and product development decision for cars to maximize profitability to meet consumer demand.

**A Little about Data:**

1. We have the data regarding different vehicle styles, their features, price, popularity over the years.

**Functions Used :** COUNTIFS, AVERAGEIFS, Pivot Table, Regression Analysis, Encoding categorical variables, MIN, MAX, Conditional formatting

**Analysis:**

1. For this I have summarized the data by finding the average values of numerical features, prices and popularity for each vehicle style for each year.
2. In order to understand the specific details about which vehicle styles are popular over years, which features of these vehicle styles are the most popular and have made them popular
3. I have narrowed down the data to top 3 vehicle styles which are popular and least costly in each year.

![image](https://github.com/dshreesr/impact-car-features/assets/33718332/d8e9f1a2-3939-4172-a50a-24ab4ad07b90)

4. From above list, I have shortlisted the below vehicle styles based on popularity and cost conditions mentioned below:
   _2dr hatchback, Passenger van_ – The avg. price and avg. popularity has increased over the years.
   
   _4dr hatchback, Wagon, Sedan, Convertible_ - the popularity has remained the same even after increase in the avg price.

5. I have further analysed the features of these cars in detail.
   
![image](https://github.com/dshreesr/impact-car-features/assets/33718332/411366c4-91fa-4e9b-9a40-e5332906984a)
_Above is the sample analysis of one vehicle style (passenger van)_.

6. Then I have used exploratory analysis to find popular car features and market categories which can be focused for research and development.
![image](https://github.com/dshreesr/impact-car-features/assets/33718332/a97e54af-ea57-4f38-89ac-ff1126fb37bb)

![image](https://github.com/dshreesr/impact-car-features/assets/33718332/0d4cc7ea-3ccf-49ce-abc1-75dadcfc6e30)

![image](https://github.com/dshreesr/impact-car-features/assets/33718332/da82d37b-95f4-477a-b54f-f2b0f271a841)

7. Next, I have tried to understand the relationship of prices with car features and used regression analysis to find out which features have direct impact on price and can used to predict the car prices.
![image](https://github.com/dshreesr/impact-car-features/assets/33718332/85ac3716-46ca-4cc7-b055-5e407e86bff8)

8. The regression analysis of different car features and prices show that _Engine HP_ and _car price_ are highly correlated and have a high determination coefficient. This feature can be used to predict car prices.
9. Please check the attached excel file to understand the analysis in detail.

**Conclusion:**

1. The vehicle styles – _2dr, 4dr hatchbacks, sedan, wagon, passenger van, convertible_ are popular over the years and have lower prices.
2. The popular features are _Flex-fuel, Direct Drive, Four wheel drive_ and popular market categories _Flex fuel, SUV, Factory tuner, Diesel, Hybrid_ suggest involving sustainable technology in the cars.
3. But the popular vehicle styles do not have these features.
4. In order to increase the popularity of these features the manufactures should focus on product development using the features mentioned above.
5. The _Engine HP_ is directly related to the car prices more than the other features.
6. We do not have the data of profitability or manufacturing cost of the cars and the features, hence the optimized price and right features to focus during product development could not be determined.








