# Single Neuron Logistic Regression

This project utilizes a Single Neuron Logistic Regression model to analyze the relationship between different types of vehicle fuel consumption, focusing on distinguishing between high-end and standard vehicle makes based on their fuel consumption patterns.

## Dataset Overview

The dataset encompasses a wide range of vehicle attributes, with an emphasis on their fuel consumption characteristics and make:

- `Make`: Brand of the car
- `Model`: Specific model of the car
- `Vehicle Class`: The category to which the vehicle belongs
- `Engine Size(L)`: The size of the engine measured in liters
- `Cylinders`: The number of cylinders in the engine
- `Transmission`: The type of transmission used
- `Fuel Type`: The kind of fuel the vehicle utilizes
- `Fuel Consumption City (L/100 km)`: The vehicle's fuel consumption in urban settings
- `Fuel Consumption Hwy (L/100 km)`: The vehicle's fuel consumption on highways
- `Fuel Consumption Comb (L/100 km)`: The vehicle's combined fuel consumption
- `Fuel Consumption Comb (mpg)`: The combined fuel consumption measured in miles per gallon
- `CO2 Emissions(g/km)`: Carbon dioxide emissions in grams per kilometer

### Data Source

The dataset is available for public access on Kaggle: [CO2 Emission by Vehicles Dataset](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)

## Logistic Regression Model

The Single Neuron Logistic Regression model, a fundamental binary classifier in machine learning, is employed in this project to identify patterns that differentiate high-end vehicle makes (like BMW and Lamborghini) from standard ones based on their fuel consumption metrics.

### Implementation

The logistic regression model is implemented in Python, utilizing essential libraries such as NumPy for numerical operations and Matplotlib for data visualization. The model focuses on analyzing 'Fuel Consumption City (L/100 km)' and 'Fuel Consumption Hwy (L/100 km)' to classify vehicles into different makes.

---

For a detailed walkthrough of the implementation and results, please refer to the accompanying Jupyter notebook in this repository.
