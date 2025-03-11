# Car Price Prediction Project

## Project Overview
This project aims to predict the price of cars in the American market using various regression models. The purpose is to help a Chinese automobile company understand the factors influencing car prices and optimize their product design and marketing strategy accordingly.

## Dataset
The dataset contains various car features like model, engine size, fuel type, horsepower, and other characteristics that impact the price of cars. It was provided via the following link: [Download Dataset](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)

## Objective
The key objectives of this project are:
- To identify the factors significantly impacting car prices.
- To build and compare different regression models.
- To evaluate the best-performing model.
- To optimize the model using hyperparameter tuning.

## Tools and Libraries Used
The following tools and libraries were used in this project:
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for Machine Learning)

## Steps to Execute the Project

### Step 1: Load the Dataset
- Load the dataset using Pandas.
- Display the first few rows to understand the data.

### Step 2: Data Preprocessing
- Handle missing values by removing them.
- Convert categorical variables to numerical using one-hot encoding.
- Split the dataset into training and testing sets.

### Step 3: Implement Regression Models
- Implement the following five regression models:
  1. Linear Regression
  2. Decision Tree Regressor
  3. Random Forest Regressor
  4. Gradient Boosting Regressor
  5. Support Vector Regressor (SVR)

### Step 4: Model Evaluation
- Evaluate each model based on:
  - R2 Score
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- Visualize the model performance using bar plots.

### Step 5: Feature Importance Analysis
- Use Random Forest to identify the most influential features impacting car prices.
- Visualize the top 10 most important features.

### Step 6: Hyperparameter Tuning
- Apply GridSearchCV to optimize the hyperparameters of the best-performing model.
- Re-evaluate the model's performance after tuning.


## Results
The Random Forest Regressor performed the best among all models with the highest R2 Score and lowest error metrics. Additionally, the feature importance analysis revealed that engine size, horsepower, and car make were the top factors influencing car prices.

## Folder Structure
```plaintext
Car Price Prediction Project
│
├── Car_Price_Prediction.ipynb   # Jupyter Notebook with all code
├── README.md                    # Project documentation
├── data.csv                     # Dataset (if downloaded locally)
```

## Conclusion
This project provided valuable insights into the factors influencing car prices in the American market. The optimized Random Forest Regressor model can be used to predict car prices with high accuracy. This will help the automobile company in:
- Designing cars that fit a specific price range.
- Strategizing their marketing and pricing policies.

## Author
- Name: Mahalakshmi V S

