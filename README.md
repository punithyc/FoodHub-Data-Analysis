# FoodHub-Data-Analysis

##### Description
#### Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin on the delivery order from the restaurants.

 

#### Objective
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company improve its business. 

 

### Data Description
The data contains the different data related to a food order. The detailed data dictionary is given below.

### Data Dictionary:

* *__order_id__*: Unique ID of the order
* *__customer_id__*: ID of the customer who ordered the food
* *__restaurant_name__*: Name of the restaurant
* *__cuisine_type__*: Cuisine ordered by the customer
* *__cost_of_the_order__*: Price paid per order
* *__day_of_the_week__*: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
* *__rating__*: Rating given by the customer out of 5
* *__food_preparation_time__*: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
* *__delivery_time__*: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

### Conclusions
*  American cuisine is the most ordered cuisine type with nearly 600 orders
* Japanese and italian cuisines are the 2nd and 3rd most ordered cuisine types
* the least ordered cuisine types are vietanamese,spanish and korean
* American,Japanese and italian have higher ratings as they are most preferred cuisines
* there is some correlation between longer delivery times and lower ratings as they took longer time to delivered  and tend to receive lower feedback
* Cuisines like Vietnamese, Spanish, and Korean have fewer orders and lower ratings This indicates the possible issues with food quality, delivery times and other reasons

### Recommendations:

*  Encourage customers to provide ratings, especially for cuisines that are less popular, to better understand why they are underperforming
* For less popular cuisines (e.g., Vietnamese, Spanish, Korean), it may be helpful to run promotions to raise awareness and attract customers and providing the deals and discounts to increase the sales based on the day of the week
* assigning the dedicated customer support for solving the problems very quickly with common issues (e.g., late delivery, poor food quality)
* Analyze the data to identify peak order times and ensure enough delivery personnel are available during those periods
* Identifying and improving the areas with food preparation quality,packing and the delivery times.
