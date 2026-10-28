
# SVM Machine Failure Classification

## Lab 8: Support Vector Machine (SVM)

### Objective
To implement the Support Vector Machine algorithm for classification and predict machine failures using machine operating data.

### Project Overview
This project uses Python and machine learning to classify whether a machine is likely to experience a failure based on its operating conditions.

### Technologies Used
- Python
- Jupyter Notebook
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn

### Algorithms Implemented
- Linear Support Vector Machine
- RBF Kernel Support Vector Machine
- GridSearchCV for hyperparameter tuning

### Dataset
AI4I 2020 Predictive Maintenance Dataset.

The dataset includes machine operating measurements such as air temperature, process temperature, rotational speed, torque, and tool wear.

### Methodology
1. Load and explore the dataset.
2. Check missing values and duplicate records.
3. Separate input features and the target variable.
4. Split the data into training and testing sets.
5. Preprocess numerical and categorical features.
6. Train Linear SVM and RBF SVM models.
7. Tune model hyperparameters using GridSearchCV.
8. Evaluate the models using accuracy, precision, recall, F1-score, and confusion matrices.

### How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Place `ai4i2020.csv` in the project folder.
4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run the cells in order.

### Author
Avaneesh Keshpage

### Academic Details
Section: A-A4
Roll No.: 64
Lab: 8
