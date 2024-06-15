# Bank Credit Risk Analysis README

## About:

Welcome to the Bank Credit Risk Analysis project! This project involves analyzing a dataset that contains information on individuals who have taken credit from a bank. Each individual is classified as either a good or bad credit risk based on various attributes. The original dataset, prepared by Prof. Hofmann, contains 1000 entries with 20 categorical/symbolic attributes. To make the dataset more understandable, a Python script was used to convert it into a readable CSV file. Some columns were ignored due to their lack of importance or unclear descriptions.

The dataset includes the following selected attributes:

- **Age**: Numeric value representing the age of the individual.
- **Sex**: Text value indicating the sex of the individual (male, female).
- **Job**: Numeric value representing the job category (0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled).
- **Housing**: Text value indicating the housing status (own, rent, or free).
- **Saving accounts**: Text value representing the status of saving accounts (little, moderate, quite rich, rich).
- **Checking account**: Numeric value indicating the amount in the checking account (in DM - Deutsch Mark).
- **Credit amount**: Numeric value representing the credit amount (in DM).
- **Duration**: Numeric value indicating the duration of the credit (in months).
- **Purpose**: Text value representing the purpose of the credit (car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others).

## Work Done:

### Data Preprocessing:
- Performed basic Exploratory Data Analysis (EDA), including describing the dataset and checking for null values using `isnull`.
- Checked for unique values in each column.
- Converted all values to numerical format to ensure the model runs properly.
- Generated a correlation matrix and visualized it using a heatmap.

### Data Visualization:
- Created histograms, box plots, and display plots to visualize the distributions and relationships of numerical columns.

### Data Splitting:
- Split the data into training and testing sets to prepare for model training and evaluation.

### Machine Learning Models:
- Applied several machine learning models to predict whether an individual is a good or bad credit risk:
  - **Linear Regression**: Checked accuracy and evaluated training and testing accuracy to identify overfitting or underfitting.
  - **Support Vector Machine (SVM)**
  - **Random Forest**
  - **K-Nearest Neighbors (KNN)**
  - **Gaussian Naive Bayes (GaussianNB)**

### Deep Learning Model:
- Implemented a deep learning model using TensorFlow and Keras:
  - **Preprocessing**: Used `StandardScaler` for feature scaling and `LabelEncoder` for encoding categorical variables.
  - **Model Architecture**: Created a Sequential model with Dense layers.
  - **Training**: Trained the model and evaluated its performance.

## Repository Structure:
- **data**: Contains the raw dataset and any processed data files.
- **notebooks**: Jupyter notebooks used for data preprocessing, EDA, modeling, and analysis.
- **results**: Results and outputs generated from the analysis, including visualizations and reports.

## Getting Started:
1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed along with necessary libraries (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow, keras).
3. Navigate to the `notebooks` directory and open the Jupyter notebooks to explore the analysis and results.
4. Follow along with the steps outlined in the notebooks to reproduce the analysis or modify it as needed.

## Contributing:
- Contributions to this project are welcome! Feel free to fork this repository, make changes, and submit pull requests.
- For major changes, please open an issue first to discuss proposed updates or improvements.

## Contact:
For any questions, suggestions, or issues, please feel free to contact me via email at [your_email@example.com].

Thank you for your interest in the Bank Credit Risk Analysis project! I hope you find the insights generated from the analysis valuable.
