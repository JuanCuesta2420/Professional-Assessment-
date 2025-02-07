# Professional Assessment 
This project focuses on predicting a target variable based on 20 randomly generated independent variables. The goal is to evaluate the relationships between these variables and assess model performance using linear regression and decision trees.
Steps & Methodologies Used


1. Data Generation & Preprocessing
    - Created a synthetic dataset with 1,000 samples.
    Generated 20 random variables (Var1 to Var20) using NumPy.
    - Constructed a target variable using a combination of three selected independent variables (Var1, Var5, and Var10) plus added random noise.


2. Data Splitting
    - The dataset was split into training (70%) and testing (30%) sets using train_test_split from Scikit-learn.


3. Models Used
    - ✅ Linear Regression
      - Trained a Linear Regression model on the dataset to predict the target variable.
      - Evaluated performance using Mean Squared Error (MSE).
    - ✅ Decision Tree Regression
      - Built a Decision Tree model to improve performance and capture nonlinear relationships.
      - Adjusted tree depth to optimize the trade-off between bias and variance.
      - Compared MSE results with Linear Regression to assess model performance.


Results & Findings
    - Linear Regression: Provided a baseline for prediction accuracy, focusing on linear relationships between variables.
    - Decision Tree Regression: Captured nonlinear patterns and improved predictive performance over linear regression.
    - MSE Comparison: Helped determine which model generalized better to unseen data.
