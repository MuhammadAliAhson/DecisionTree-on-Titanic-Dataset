### Titanic Dataset Analysis with Decision Tree Classifier

This repository contains a Python notebook demonstrating the application of Decision Tree Classifier on the Titanic dataset. Below is a brief overview of the steps involved in the analysis:

### Table of Contents

1. **Introduction**
   - Explanation of the notebook and its objectives.

2. **Data Loading**
   - Loading the Titanic dataset from a CSV file using pandas.

3. **Data Preprocessing**
   - Checking for null values and visualizing their intensity using a heatmap.
   - Exploring the distribution of data and visualizing survival rates based on different features.

4. **Data Normalization**
   - Using MinMaxScaler to normalize the data, preparing it for modeling.

5. **Feature Engineering**
   - Filling missing values in the 'Age' column based on survival status and passenger class.
   - Dropping the 'Cabin' column due to high null values.

6. **Data Visualization**
   - Visualizing the data to confirm uniformity and absence of null values.

7. **Model Training**
   - Splitting the data into training and testing sets.
   - Hyperparameter tuning using GridSearchCV to find the best parameters for the Decision Tree Classifier.
   - Training the model with the best parameters.

8. **Model Evaluation**
   - Evaluating the model's performance on the test set using accuracy score and classification report.

9. **Medium Article**
   - https://medium.com/@i212535/decision-tree-classifiers-and-the-titanic-dataset-d0e8a72fd48c(#) -
   - Medium article discussing this project in detail.

### Usage

To replicate the analysis, follow these steps:
- Clone the repository to your local machine.
- Ensure you have Jupyter Notebook installed.
- Open the notebook file `Titanic_Decision_Tree.ipynb` in Jupyter Notebook.
- Run each cell in the notebook sequentially to execute the code.

### Dependencies
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

### Contributor
- Muhammad Ali Ahson

For any questions or feedback, feel free to contact aliahson56@gmail.com.

Thank you for exploring the Titanic dataset analysis with Decision Tree Classifier! 🚢🌳
