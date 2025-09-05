
# Used Car Price Prediction Model

## Dataset Overview

This project utilizes the [Used Car Price Prediction Dataset](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset), a comprehensive collection of automotive listings sourced from [cars.com](https://www.cars.com). The dataset contains 4,009 unique vehicle entries, each described by a rich set of features that capture essential aspects of used car valuation.

### Key Features

- **Brand & Model:** Manufacturer and specific model of the vehicle.
- **Model Year:** Year of manufacture, crucial for assessing depreciation and technological relevance.
- **Mileage:** Total distance traveled, indicating wear and maintenance needs.
- **Fuel Type:** Type of fuel (gasoline, diesel, electric, hybrid).
- **Engine Type:** Engine specifications for performance and efficiency insights.
- **Transmission:** Transmission type (automatic, manual, etc.).
- **Exterior & Interior Colors:** Aesthetic details of the vehicle.
- **Accident History:** Records of prior accidents or damage.
- **Clean Title:** Indicates legal status and resale value.
- **Price:** Listed price, serving as the target variable.

### Features Used for Model Training

- Brand & Model
- Model Year
- Mileage
- Fuel Type
- Transmission
- Accident History
- Clean Title

**Target Variable:**
- Price


## Modeling Approach & Results

Multiple machine learning algorithms were evaluated, including Random Forest, Support Vector Regression, Decision Tree, and Linear Regression. Each model was assessed using Mean Absolute Error (MAE) to determine predictive accuracy.

**Best Model:**
- **Random Forest Regressor**

**Final Performance on Test Set:**
- **Mean Absolute Error (MAE):** $15,263.36
- **R² Score:** 0.64

This means the model’s predictions deviate from actual prices by about $15,263.36 on average, and it explains 64% of the variance in used car prices—a strong result for this domain.

### Model Comparison (MAE)

- Random Forest Regressor: 17,174.41
- Support Vector Regressor: 27,250.01
- Decision Tree Regressor: 20,918.42
- Linear Regression: 20,738.51

**Hyperparameters:**
- Default values were used for all models.



## Conclusion

This model provides reliable price estimates for used cars, supporting dealers, sellers, and buyers in making data-driven decisions. While some prediction error remains, the model offers valuable guidance for pricing, inventory management, and negotiations.



## Getting Started

### Prerequisites

- Python 3.11+
- Required Python packages (see `environment.yml`)
- Download the dataset from [Kaggle](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset)

### Installation & Usage

1. **Clone the repository:**
	```sh
	git clone https://github.com/Yeshua235/used-car-price-prediction.git
	cd used-car-price-prediction
	```

2. **Install dependencies:**
	```sh
	conda env create -f environment.yml
	```

3. **Download and extract the dataset:**
	Place `used_cars.csv` in the `archive/` directory.

4. **Run the model training script:**

5. **Evaluate the model:**
	Review the output metrics and generated model file (`used_car_price_predictor.pkl`).


## License

This project is licensed under the MIT License.

## Acknowledgements

- [Kaggle](https://www.kaggle.com/)
- [scikit-learn](https://scikit-learn.org/)
- All contributors and data providers
