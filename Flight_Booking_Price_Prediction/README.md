# Flight Booking Price Prediction

The objective is to analyze the flight booking dataset obtained from a platform which is used to book flight tickets and make prediction on price.

Data set information:
- Flight booking price prediction dataset contains around 3 lacs records with 11 attributes

![Fligh data set information](https://github.com/user-attachments/assets/d1f37d9a-cb96-4c34-9d08-3dd5725579f1)

key insights:
- There is a variation in price with different airlines
- Vistara has the highest price followed by Air_India
- The price of the ticket increases as the days left for departure decreases
- Prices of Business class are much higher than economy class
- Flight Prices Are Highest Closer to Departure
- Prices Drop Sharply as Days Increase, afte days left > 20 prices stabalize across all cities
- Booking early (20+ days in advance) ensures lower prices.
- Last-minute bookings lead to significantly higher costs.
- vistara has highest frequency i.e., it is used most
- Delhi and Mumbai has the highest no. of passangers whether its departure on arrival
- Most flights depart in Morning and Evening
- There is generally one stop or no stop at during journey
- Most flights have arrival time of Night and Evening
- Economy class has most number of passangers

Model Insights:
  
- During Linear Regression there is too much variation in predictions as you can see
  - r2 Score :  0.9064134893861682
  - Mean Absolute Error :  4624.680638432283
  - Mean Absolute Percentage Error (MAPE) :  0.44130196573394637
  - Mean Squared Error (MSE) :  48275800.60388493
  - Roor Mean Squared Error (RMSE) :  6948.0789146270445

    ![{962615BC-5376-4497-B14D-38AF239F41C4}](https://github.com/user-attachments/assets/da116fea-7316-4bd2-9ccd-7be3040b1abe)

- During Decision Tree Regression the Error is much less compared to linear regression
  - r2 Score :  0.9768053567366441
  - Mean Absolute Error :  1159.5848451791558
  - Mean Absolute Percentage Error (MAPE) :  0.07457322244106941
  - Mean Squared Error (MSE) :  11964758.231882557
  - Roor Mean Squared Error (RMSE) :  3459.0111638852163 
 
    ![{AB581712-AA77-4546-825C-50FE461FF6EE}](https://github.com/user-attachments/assets/5da05586-3775-482b-80a3-f4f64d326e79)

- During Random Forest Regression the Error is much less compared to linear regression and Decision Tree model
  - r2 Score :  0.9857241469812169
  - Mean Absolute Error :  1069.7841889606818
  - Mean Absolute Percentage Error (MAPE) :  0.06968891379720951
  - Mean Squared Error (MSE) :  7364076.609597237
  - Roor Mean Squared Error (RMSE) :  2713.6832183578904
 
    ![{C0F02BA6-42A3-4624-9C35-1DE6F7E609F3}](https://github.com/user-attachments/assets/5da05586-3775-482b-80a3-f4f64d326e79)
)

### Random Forest is the best model for this prediction

