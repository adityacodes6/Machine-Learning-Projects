# 💵 Salary Prediction Using Linear Regression

## 📌 Project Overview
This project uses **Linear Regression**, a supervised machine learning algorithm, to predict an employee's salary based on their years of work experience.

The model is trained using historical salary data and predicts salaries for new experience values.

## 🎯 Project Objectives
- Understand and implement Linear Regression.
- Perform basic data exploration and preprocessing.
- Split the dataset into training and testing sets.
- Train a machine learning model.
- Predict salaries based on experience.
- Evaluate model performance using evaluation metrics.
- Visualize actual and predicted salaries.

## 🛠️ Technologies Used

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Scikit-learn – Machine learning and model evaluation
- Jupyter Notebook – Development environment

## 📂 Dataset

**Dataset:** `Salary_dataset.csv`

The dataset contains the following columns:

| Column | Description |
|---|---|
| YearsExperience | Number of years of work experience |
| Salary | Corresponding salary |

The project uses:
- **Input Feature (X):** YearsExperience
- **Target Variable (y):** Salary

The `Unnamed: 0` column is removed because it is not useful for prediction.

## ⚙️ Project Workflow

### 1. Import Libraries
Import the required Python libraries for data handling, visualization and machine learning.

### 2. Load Dataset
Load the salary dataset using Pandas.

### 3. Exploratory Data Analysis (EDA)
- Display the first few records.
- Check dataset dimensions.
- Examine column information.
- Generate statistical summaries.
- Check for missing values.

### 4. Data Preprocessing
- Check for missing values.
- Remove the unnecessary `Unnamed: 0` column.
- Separate input features and target variables.

### 5. Train-Test Split
Split the dataset into:
- 80% Training Data
- 20% Testing Data

The `random_state=42` parameter ensures reproducibility.

### 6. Model Creation
Create a Linear Regression model using Scikit-learn.

### 7. Model Training
Train the model using `model.fit(X_train, y_train)`.

### 8. Prediction
Use `model.predict(X_test)` to predict salaries for the testing dataset.

### 9. Model Evaluation
Evaluate model performance using:

| Metric | Purpose |
|---|---|
| MAE | Measures average absolute prediction error |
| MSE | Measures average squared prediction error |
| RMSE | Measures prediction error in the original unit |
| R² Score | Measures how well the model explains variations in salary |

### 10. Data Visualization
Visualize the actual salary values and predicted salary values using a scatter plot and regression line.

### 11. New Prediction
The trained model is also used to predict the salary of a person with **9 years of experience**.

## 📊 Model Evaluation

The model is evaluated using four metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The evaluation results are displayed when the notebook is executed.

## 🚀 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone <your-github-repository-link>
```

**Step 2:** Navigate to the project folder.

```bash
cd Salary-Prediction
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

**Step 4:** Make sure `Salary_dataset.csv` is available in the project folder.

**Step 5:** Open Jupyter Notebook.

```bash
jupyter notebook
```

**Step 6:** Open `salary_Prediction_using_linear_regression.ipynb` and run all cells.

## 🔮 Example Prediction

The project predicts the salary for a person with 9 years of experience.

```python
new_data = pd.DataFrame({
    'YearsExperience': [9]
})

prediction = model.predict(new_data)
```

## 📌 Conclusion

This project demonstrates the implementation of a basic Linear Regression model for salary prediction.

It covers the complete machine learning workflow, including data exploration, preprocessing, model training, prediction, evaluation and visualization.

The project helped develop practical knowledge of Python, Scikit-learn and supervised machine learning.

## 👨‍💻 Author

**Aditya Mungekar**

BSc Data Science and Analytics Student

