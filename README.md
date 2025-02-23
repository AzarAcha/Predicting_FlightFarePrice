# Predicting_FlightFarePrice

# Problem Statement
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain.

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model which will help the customers to predict future flight prices and plan their journey accordingly.

# Features 
1.	Airline: So this column will have all the types of airlines like Indigo, Jet Airways, Air India, and many more.\
2.	Date_of_Journey: This column will let us know about the date on which the passenger’s journey will start.\
3.	Source: This column holds the name of the place from where the passenger’s journey will start.\
4.	Destination: This column holds the name of the place to where passengers wanted to travel.\
5.	Route: Here we can know about what the route is through which passengers have opted to travel from his/her source to their destination.\
6.	Arrival_Time: Arrival time is when the passenger will reach his/her destination.\
7.	Duration: Duration is the whole period that a flight will take to complete its journey from source to destination.\
8.	Total_Stops: This will let us know in how many places flights will stop there for the flight in the whole journey.\
9.	Additional_Info: In this column, we will get information about food, kind of food, and other amenities.\
10.	Price: Price of the flight for a complete journey including all the expenses before onboarding.\


# From the result
Random Forest Regressor has highest R2, lower variance (std deviation of 0.0216), it is the most stable model.
Random Forest Regressor and Gradient Boosting Regressor shows lowest RMSE value than other models shocasing these two are most performing models among all the models.

# Key Findings
Price of the flight is influenced by the following

Booking time, airline, number of stops, and departure time.\
Brand value of the airlines.\
Number of stops between the source and destination.\

# Model Performance
Random Forest performed the best with an R² score of 0.8160 and the lowest RMSE, making it the most accurate model for predicting flight prices.\
Gradient Boosting was the second-best model with an R² score of 0.7716.\
XGBoost and MLP performed the worst, indicating they are not suitable for this dataset.\

# Business Impact
For Airlines:
Helps airlines set competitive pricing based on market trends. Can optimize revenue management strategies by predicting peak demand periods.

# For Customers:
Travelers can predict future flight fares, helping them book at the best price. Can assist in planning trips in advance to avoid last-minute high fares.
