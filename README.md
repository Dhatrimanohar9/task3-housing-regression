#  Housing Price Prediction using Linear Regression

This project was completed as part of Task 3 for the AI & ML Internship.  
The goal was to implement a simple and multiple linear regression model to predict house prices based on various features from the dataset.



##  Objective

- Understand how linear regression works in real-world datasets
- Train and evaluate a regression model
- Interpret the impact of each feature on the predicted outcome



##  Files in this Repository

- `Housing.csv` – The dataset containing features like area, number of bedrooms, bathrooms, etc.
- `Task3_Housing_LinearRegression.ipynb` – Jupyter notebook with complete code, plots, and model evaluation
- `README.md` – You’re reading it!



##  Technologies Used

- Python
- Pandas & NumPy (data handling)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (model building & evaluation)



##  Steps Performed

### 1. **Data Preprocessing**
- Converted categorical features (like `mainroad`, `guestroom`, `airconditioning`, etc.) into numerical values using `map()` and `get_dummies()`.

### 2. **Train-Test Split**
- The dataset was split into 80% training and 20% testing using `train_test_split`.

### 3. **Model Training**
- A `LinearRegression` model was trained using the processed features to predict the target variable `price`.

### 4. **Model Evaluation**
We evaluated the model using standard regression metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

### 5. **Visualization**
- Plotted **Actual vs Predicted Prices** to understand model performance visually.
- Extracted **feature coefficients** to understand which features impact the price most.



## Sample Output (example)
Mean Absolute Error (MAE): 528172.53
Mean Squared Error (MSE): 495202316291.78
R² Score: 0.67




##  Key Insights

- Houses with **better furnishing**, **air conditioning**, or in a **preferred area** tend to have higher predicted prices.
- Linear regression is simple yet surprisingly effective for this kind of structured, numeric data.



##  Dataset Source

- [Kaggle: Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)



##  Submission Info

This task was completed as part of **Task 3: Linear Regression** for the AI & ML Internship.  
All code and documentation are included for review and replication.





