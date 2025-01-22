# Laptop Price Prediction

## Overview
This project aims to predict the prices of laptops based on various features such as brand, specifications, and other attributes. The dataset used contains information about laptop models, their prices, and characteristics, allowing for a comprehensive analysis and modeling approach.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Analysis](#data-analysis)
- [Model Building](#model-building)
- [Results](#results)
- [Contributing](#contributing)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Dataset
The dataset used for this project is `laptop_prices.csv`, which contains information on various laptop models. It includes features such as:

- **Company:** Brand of the laptop
- **Product Name:** Model name of the laptop
- **Type:** Type of laptop (e.g., Ultrabook, Notebook)
- **Screen Size:** Screen size (in inches)
- **RAM:** RAM size (in GB)
- **Operating System:** Operating system
- **Weight:** Weight of the laptop (in kg)
- **Price:** Price (in euros)

## Features
- **Company:** Brand of the laptop
- **Product:** Model name of the laptop
- **TypeName:** Type of laptop (e.g., Ultrabook, Notebook)
- **Inches:** Screen size
- **Ram:** RAM size
- **OS:** Operating system
- **Weight:** Weight of the laptop
- **Price_euros:** Price in euros
- **CPU_company:** Manufacturer of the CPU
- **GPU_company:** Manufacturer of the GPU
- **Storage specifications**

## Installation
To run this project, you need to have Python installed on your machine. You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

## Usage

1. **Clone this repository to your local machine using:**

   ```bash
   git clone https://github.com/SamiUllah568/Laptop-Price-Prediction

# Navigate to the project directory:
cd Laptop-Price-Prediction
Open the Jupyter Notebook or Python script to start exploring the data and models.
```
## **Data Analysis**
In this section, the dataset is explored using visualizations and statistical analysis to identify trends and insights. The analysis includes:

**Summary statistics**
**Distribution of laptop prices**
**Correlation between features and prices**
**Model Building**
**Multiple regression models are built to predict laptop prices, including:**

**Linear Regression**
**Support Vector Regression (SVR**)
**Random Forest Regressor**
**Gradient Boosting Regressor**
XGBoost**
The models are evaluated using metrics such as R-squared and Mean Squared Error.

**Results**
The results of the model predictions are presented, including accuracy metrics and visualizations to compare predicted and actual prices.

**Contributing**
Contributions are welcome! If you want to contribute to this project, please fork the repository and create a pull request with your changes.
