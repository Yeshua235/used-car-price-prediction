# About Dataset (The Dataset was Downloaded from [Kaggle Website](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset) )

## About the Data
**Used Car Price Prediction Dataset is a comprehensive collection of automotive information extracted from the popular automotive marketplace website, https://www.cars.com. This dataset comprises 4,009 data points, each representing a unique vehicle listing, and includes nine distinct features providing valuable insights into the world of automobiles.**

**Features in the Dataset**
- *Brand & Model*: Identify the brand or company name along with the specific model of each vehicle.
- *Model Year*: Discover the manufacturing year of the vehicles, crucial for assessing depreciation and technology advancements.
- *Milage*: Obtain the mileage of each vehicle, a key indicator of wear and tear and potential maintenance requirements.
- *Fuel Type*: Learn about the type of fuel the vehicles run on, whether it's gasoline, diesel, electric, or hybrid.
- *Engine Type*: Understand the engine specifications, shedding light on performance and efficiency.
- *Transmission*: Determine the transmission type, whether automatic, manual, or another variant.
- *Exterior & Interior Colors*: Explore the aesthetic aspects of the vehicles, including exterior and interior color options.
- *Accident History*: Discover whether a vehicle has a prior history of accidents or damage, crucial for informed decision-making.
- *Clean Title*: Evaluate the availability of a clean title, which can impact the vehicle's resale value and legal status.
- *Price*: Access the listed prices for each vehicle, aiding in price comparison and budgeting.

**Features used in training model**
- *Brand & Model*
- *Model Year*
- *Milage*
- *Fuel Type*
- *Transmission*
- *Accidnet History*
- *Clean Title*

**Target Feature**
- *Price*

# Result Obtained

The modeling process began by training several algorithms [Random Forest, Support Vector Regression, Decision Tree, and Linear Regression], on a subset of the training data. Each model was evaluated using Mean Absolute Error (MAE) to determine its predictive accuracy. Based on its superior performance, the Random Forest Regressor was selected and subsequently trained on the entire training set.

When evaluated on the hold-out test set, the Random Forest model achieved a Mean Absolute Error of 15,263.36 and an R² score of 0.64. The MAE indicates that, on average, the model's price predictions deviate from actual prices by approximately $15,263.36. The R² score of 0.64 means that the model explains 64% of the variance in used car prices, reflecting a strong relationship between the selected features and the target variable.

## Intermittent Result

**performance Metric Used:**
- Mean Absolute Error

**Hyperparameters:**
- Default values

**Models employed and their performance (Mean Absolute Error):**
- Random Forest Regressor: 17174.41
- Support Vector Regressor: 27250.01
- Decision Tree Regressor: 20918.42
- Linear Regression: 20738.51

## Final Result

**Selected Model:**
- Random Forest Regressor

**performance metrics:**
- Mean Absolute Error
- R2 Score

**performance Obtained**
- Mean Absolute Error: 15263.36
- R2 Score: 0.64

# Conclusion

For car dealers and sellers, these results signify that the model provides reasonably accurate price estimates, helping to set competitive and fair prices based on key vehicle attributes. While some prediction error remains, the model offers valuable guidance for pricing decisions, inventory management, and negotiations, ultimately supporting more informed and data-driven business strategies.
