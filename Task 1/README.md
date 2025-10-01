# Student Score Prediction

This project involves building a machine learning model to predict student scores based on the number of study hours. The implementation is done in the Jupyter Notebook file `Student_Score_Prediction.ipynb`.

## Overview
The goal of this project is to demonstrate a simple regression analysis using Python. The dataset used contains two columns: the number of hours studied and the corresponding scores obtained by students.

## Steps Performed
1. **Data Loading**: The dataset is loaded into a Pandas DataFrame for analysis.
2. **Data Visualization**: A scatter plot is created to visualize the relationship between study hours and scores.
3. **Data Preprocessing**:
        - Checked for missing values.
        - Split the dataset into training and testing sets.
4. **Model Training**:
        - A linear regression model is trained using the training data.
5. **Model Evaluation**:
        - The model's performance is evaluated using metrics like Mean Absolute Error (MAE).
6. **Prediction**:
        - The model is used to predict scores for given study hours.

## Results
The linear regression model successfully predicts student scores with reasonable accuracy. The scatter plot and regression line indicate a positive correlation between study hours and scores.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Open `Student_Score_Prediction.ipynb` in Jupyter Notebook.
4. Run the cells sequentially to reproduce the results.

## Conclusion
This project, assigned by Elevvo internship, demonstrates the use of linear regression for predictive modeling. It serves as a foundational example for understanding regression techniques in machine learning.