# California Housing Price Prediction

## Overview
This project uses the **California Housing Dataset** to predict median house values based on features like median income, average rooms, and location. The goal is to build and evaluate a regression model and visualize insights to improve our understanding of housing price trends.

---

## Table of Contents
1. [Dataset Description](#dataset-description)
2. [Project Workflow](#project-workflow)
3. [Visualizations](#visualizations)
4. [Model Evaluation](#model-evaluation)
5. [How to Use](#how-to-use)
6. [Future Work](#future-work)

---

## Dataset Description
The **California Housing Dataset** contains information about various housing blocks in California, including:
- **Features**:
  - `MedInc`: Median income in the area.
  - `HouseAge`: Average house age.
  - `AveRooms`: Average number of rooms per household.
  - `AveBedrms`: Average number of bedrooms per household.
  - `Population`: Total population in the area.
  - `AveOccup`: Average occupants per household.
  - `Latitude` and `Longitude`: Geographical location.
- **Target**:
  - `MedHouseVal`: Median house value (in $100,000s).

---

## Project Workflow
1. **Data Loading**: Load the California Housing dataset.
2. **Data Preprocessing**:
   - Split the dataset into training (80%) and testing (20%) sets.
   - Prepare features (`X`) and target (`y`).
3. **Model Training**:
   - Train a **Linear Regression** model on the training data.
4. **Model Evaluation**:
   - Evaluate the model using metrics like **Mean Squared Error (MSE)** and **R² Score**.
5. **Visualization**:
   - Visualize model performance and explore data insights.

---

## Visualizations
### 1. **Scatter Plot: Actual vs Predicted Values**
Shows how well the predicted values align with the actual values.

![Actual vs Predicted](path_to_actual_vs_predicted_plot.png)

---

### 2. **Residual Plot**
Visualizes the residuals (differences between actual and predicted values) to detect any patterns.

![Residual Plot](path_to_residual_plot.png)

---

### 3. **Histogram of Residuals**
Displays the distribution of residuals to check if they follow a normal distribution.

![Histogram of Residuals](path_to_residual_histogram.png)

---

### 4. **Feature Importance**
Highlights the relative impact of each feature on the target variable.

![Feature Importance](path_to_feature_importance_plot.png)

---

## Model Evaluation
### Metrics:
- **Mean Squared Error (MSE)**: `XX.XX`
- **R² Score**: `0.XX`

### Interpretation:
- A lower MSE indicates that the model makes predictions with fewer errors.
- The R² score suggests that the model explains approximately `XX%` of the variability in house prices.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/california-housing-prediction.git
   cd california-housing-prediction

