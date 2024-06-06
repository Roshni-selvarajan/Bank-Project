
## Project Overview
This project focuses on analyzing direct marketing campaigns by a Portuguese bank, with the goal of predicting client subscription to term deposits based on collected features. By leveraging machine learning techniques, we aim to uncover insights into the factors affecting client decisions and enhance future marketing strategies.

## Dataset
The dataset includes the following features: age, job, marital status, education, default, balance, housing status, loan, contact, day, month, duration, campaign, pdays, previous, poutcome, and Target (y).

These features cover client demographics, previous campaign interactions, economic indicators, and social factors.

## Classification Objective
The primary objective is to predict whether a client will subscribe (yes or no) to a term deposit (variable y). This binary classification task employs machine learning algorithms to train predictive models using historical campaign data.

## Data Analysis
1. **Exploratory Data Analysis (EDA)**: Conducted a thorough EDA to understand feature distributions, identify outliers, and explore relationships between variables.
   
2. **Feature Engineering**: Created new features and transformed existing ones to improve predictive power and model performance. Addressed class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

## Conclusion
1. **Predictive Performance**: Evaluated four machine learning models: K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest, and Logistic Regression. Hyperparameter tuning was performed using GridsearchCV to optimize each model.
   
2. **Model Evaluation**: Random Forest demonstrated superior performance with higher precision and recall, effectively identifying positive instances. Due to the dataset's imbalance, accuracy was not a reliable metric, highlighting the importance of precision and recall.

3. **Strategic Insights**: Derived actionable insights to improve future marketing efforts, such as identifying high-propensity demographics, refining communication strategies, and optimizing resource allocation.

## Technologies Used
- **Python Libraries**: Utilized Pandas for data manipulation, Scikit-learn for machine learning, and Matplotlib along with Seaborn for data visualization.
- **Google Colab**: Employed Google Colab for collaborative development and execution of Jupyter notebooks.

## Getting Started
To begin working with this project:

1. **Clone Repository**: Clone this repository to your local machine.
   ```sh
   git clone https://github.com/your-username/direct-marketing-analysis.git
   ```
2. **Download Dataset**: Obtain the dataset file `bank_full.csv`.
3. **Install Dependencies**: Install the necessary dependencies by running:
   ```sh
   pip install -r requirements.txt
   ```
4. **Explore Notebooks**: Review the Colab notebook provided in the repository to understand data analysis and machine learning model implementation.

## License
This project is licensed under the MIT License, permitting modification and distribution under specific conditions.
