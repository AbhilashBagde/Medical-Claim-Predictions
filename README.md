# Medical Claim Predictions 🏥

## Project Overview
This project aims to analyze medical insurance data and build machine learning models to predict medical claim counts. By leveraging demographic and health-related data, the project explores the factors influencing claim frequency and compares different regression techniques, specifically focusing on **Elastic Net** and **XGBoost (Poisson Regression)**.

## 📂 Repository Structure
* `AML_Final_Project.ipynb`: The main Jupyter Notebook containing the data analysis, preprocessing, modeling, and evaluation code.
* `cleaned_medical_insurance.csv`: The processed dataset used for training and testing.
* `categorical_bar_plots.png` / `univariate_histograms.png`: Visualizations generated during Exploratory Data Analysis (EDA).
* `outlier_box_plots.png`: Analysis of outliers in the dataset.

## 🛠️ Technologies Used
* **Language:** Python 3.11+
* **Libraries:**
    * `pandas` & `numpy`: Data manipulation.
    * `matplotlib` & `seaborn`: Data visualization.
    * `scikit-learn`: Preprocessing and Elastic Net implementation.
    * `xgboost`: Gradient Boosting for count data (Poisson distribution).

## 📊 Key Analysis Steps
1.  **Exploratory Data Analysis (EDA):**
    * Univariate analysis using histograms.
    * Categorical feature distribution using bar plots.
    * Outlier detection using box plots.
2.  **Data Preprocessing:**
    * Handling missing values (if any).
    * Encoding categorical variables.
    * Feature scaling.
3.  **Modeling:**
    * **Elastic Net Regression:** To handle potential multicollinearity and perform feature selection.
    * **XGBoost (Poisson):** specifically tuned for count data to predict the frequency of claims.
4.  **Evaluation:**
    * Comparing Predicted vs. Actual Claims counts.
    * Visualizing model performance with scatter plots and diagonal unity lines.

## 📈 Results
* The XGBoost model utilizing a Poisson objective function demonstrated the ability to capture the distribution of claim counts.
* *Add specific metrics here if you have them, e.g., RMSE, MAE, or Poisson Deviance.*

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/AbhilashBagde/Medical-Claim-Predictions.git](https://github.com/AbhilashBagde/Medical-Claim-Predictions.git)
    ```
2.  Navigate to the directory:
    ```bash
    cd Medical-Claim-Predictions
    ```
3.  Install dependencies (ensure you have the libraries listed above):
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost
    ```
4.  Run the notebook using Jupyter or VS Code.

## 👤 Author
**Abhilash Bagde**
* [GitHub Profile](https://github.com/AbhilashBagde)

---
*This project was developed for the Applied Machine Learning (AML) course.*
