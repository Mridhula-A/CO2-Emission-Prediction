# CO₂ Emission Prediction Using Regression

## 📌 Domain Explanation

CO₂ is a major greenhouse gas that contributes to global warming and climate change. Vehicles produce CO₂ emissions mainly through the burning of petrol, diesel, and other fossil fuels.

CO₂ emissions depend on factors such as:

* Engine size
* Number of cylinders
* Fuel type
* Transmission
* Fuel consumption

Regression analysis helps identify the relationship between these vehicle features and CO₂ emissions and predict emissions in grams per kilometre (g/km).

## 🎯 Problem Statement

The objective is to develop a regression model to predict vehicle CO₂ emissions in grams per kilometre (g/km).

The analysis examines engine size, number of cylinders, fuel type, transmission, and fuel consumption. Exploratory Data Analysis (EDA) is performed to identify important patterns and relationships.

## 📊 Dataset

The dataset contains information about vehicles and their CO₂ emissions.

| Feature       | Description                  |
| ------------- | ---------------------------- |
| Make          | Manufacturer of the vehicle  |
| Model         | Name/Model of the vehicle    |
| Vehicle Class | Category of the vehicle      |
| Engine Size   | Engine size in litres        |
| Cylinder      | Number of cylinders          |
| Transmission  | Type of vehicle transmission |
| Fuel Type     | Type of fuel used            |

## 🔍 Exploratory Data Analysis

EDA was performed to understand the dataset and identify relevant features. The analysis included:

* Dataset shape and information
* Descriptive statistics
* Duplicate value checking
* Missing value checking
* Feature distributions
* CO₂ emission distribution
* Fuel consumption distribution
* Correlation analysis

### Key EDA Findings

* Most vehicles have engine sizes between 2.0 and 4.0 litres.
* Most CO₂ emissions are between approximately 180 and 300 g/km.
* CO₂ emissions generally increase with the number of cylinders.
* Larger engines tend to have higher CO₂ emissions.
* Higher fuel consumption is strongly associated with higher CO₂ emissions.
* Higher fuel efficiency (MPG) is associated with lower CO₂ emissions.

## 🔗 Correlation Analysis

Important correlations identified:

* Engine Size and Cylinders: **0.93**
* Engine Size and CO₂ Emissions: **0.85**
* Cylinders and CO₂ Emissions: **0.83**
* Combined Fuel Consumption and CO₂ Emissions: **0.92**
* City Fuel Consumption and CO₂ Emissions: **0.92**
* Highway Fuel Consumption and CO₂ Emissions: **0.88**
* Fuel Consumption (MPG) and CO₂ Emissions: **-0.91**

These results show that engine characteristics and fuel consumption are important factors influencing CO₂ emissions.

## 🤖 Regression Model

A machine-learning regression model is used to predict CO₂ emissions based on relevant vehicle features.

The target variable is:

**CO₂ Emissions (g/km)**

## 📈 Model Evaluation

The regression model is evaluated using:

* **MAE** – Mean Absolute Error
* **MSE** – Mean Squared Error
* **RMSE** – Root Mean Squared Error
* **R² Score** – Coefficient of Determination

Lower MAE, MSE, and RMSE indicate smaller prediction errors, while a higher R² score indicates better model performance.

## 💡 Insights

* Larger engine sizes generally produce higher CO₂ emissions.
* Vehicles with more cylinders tend to have higher emissions.
* Higher fuel consumption results in higher CO₂ emissions.
* Fuel-efficient vehicles generally produce lower emissions.
* City driving generally requires more fuel than highway driving.
* Engine size, cylinders, and fuel consumption are important factors for predicting CO₂ emissions.

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 📁 Files

* `CO2_Emission_Regression.ipynb` – Google Colab/Jupyter Notebook
* `CO2_emissions.csv` – Dataset
* `README.md` – Assignment documentation

## 🔗 Google Colab

[Open Google Colab Notebook](https://colab.research.google.com/drive/1mzpEGHmbe8_bnBkW63w8cQjkoKChMdthP-)

## ✅ Result

The regression analysis successfully identifies important factors influencing vehicle CO₂ emissions and provides a machine-learning approach for predicting CO₂ emissions.
