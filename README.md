# 🍽️ Tasty Bytes - Recipe Data Analysis & Prediction
## 📌 Project Overview
Tasty Bytes started as a recipe search engine during the Covid-19 pandemic and has now grown into a meal planning and delivery subscription service. This project analyzes recipe data to uncover insights into nutritional content, meal trends, and high-traffic recipes using Exploratory Data Analysis (EDA) and predictive modeling.

## 📊 Objectives
- ✅ Perform Exploratory Data Analysis (EDA) to understand recipe characteristics.
- ✅ Predict High-Traffic Recipes based on nutritional and categorical data.
- ✅ Identify Key Nutritional Trends such as calories, protein, carbohydrates, and sugar content.

##  📂 Dataset Details
The dataset contains recipe details, including nutritional values, category, servings, and traffic status.

| Column       | Data Type  | Description                                      |
|-------------|-----------|--------------------------------------------------|
| recipe      | Numeric   | Unique identifier for the recipe                 |
| calories    | Numeric   | Total calories per serving                        |
| carbohydrate| Numeric   | Amount of carbohydrates (grams)                   |
| sugar       | Numeric   | Amount of sugar (grams)                           |
| protein     | Numeric   | Amount of protein (grams)                         |
| category    | Character | Type of recipe (e.g., dessert, main course, etc.) |
| servings    | Numeric   | Number of servings per recipe                     |
| high_traffic| Character | Whether the recipe is high-traffic (Yes/No)       |


## 📊 Exploratory Data Analysis (EDA)
Key insights from the EDA include:

- 📌 Distribution of calories, protein, and sugar across different recipes.
- 📌 Correlation analysis between nutritional factors and high-traffic recipes.
- 📌 Top-performing recipe categories based on popularity.

## 🤖 Predicting High-Traffic Recipes
We trained a classification model to predict whether a recipe will have high traffic based on its nutritional content and category.

### 🔍 Model Training
- 1️⃣ Feature Engineering - Convert categorical data, normalize numerical values.
- 2️⃣ Train/Test Split - Splitting data into 80% training and 20% testing.
- 3️⃣ Model Selection - Tested models like Logistic Regression, Random Forest, and XGBoost.
- 4️⃣ Evaluation Metrics - Accuracy, Precision, Recall, F1-score.
