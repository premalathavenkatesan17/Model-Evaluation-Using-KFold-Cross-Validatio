# Model Evaluation Using K-Fold Cross Validation

## 📌 Project Overview

This project demonstrates the process of evaluating a machine learning classification model using **Stratified K-Fold Cross Validation**.

The project uses the **Breast Cancer Wisconsin Dataset** to build and evaluate a Logistic Regression model. Cross-validation is an important technique in machine learning because it provides a more reliable estimate of how well a model performs on unseen data.

Instead of evaluating the model using only a single train-test split, the dataset is divided into multiple subsets called **folds**. The model is trained and evaluated multiple times, with each fold being used as validation data once.

---

## 🎯 Objective

The main objective of this project is to evaluate the performance of a machine learning model using **K-Fold Cross Validation**.

The project aims to:

* Load and explore the Breast Cancer Wisconsin Dataset.
* Understand the structure and features of the dataset.
* Check for missing values.
* Separate input features and target variables.
* Apply feature scaling using StandardScaler.
* Build a Logistic Regression classification model.
* Perform 5-Fold Stratified K-Fold Cross Validation.
* Calculate accuracy for each fold.
* Calculate the mean cross-validation accuracy.
* Analyze the variation in model performance.
* Generate a classification report.
* Create and visualize a confusion matrix.

---

## 📊 Dataset

### Breast Cancer Wisconsin Dataset

The Breast Cancer Wisconsin Dataset is a widely used dataset for machine learning classification tasks.

The dataset contains various numerical features that describe characteristics of breast cancer cells.

### Dataset Information

* **Number of Samples:** 569
* **Number of Input Features:** 30
* **Target Variable:** `target`
* **Problem Type:** Binary Classification

The dataset is used to classify breast cancer samples into two categories.

---

## 🛠️ Technologies and Libraries Used

This project is implemented using Python and the following libraries:

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 🤖 Machine Learning Model

### Logistic Regression

The machine learning model used in this project is **Logistic Regression**.

Logistic Regression is a supervised machine learning algorithm commonly used for classification problems. It predicts the probability of an observation belonging to a particular class.

---

## 🔄 Cross Validation Technique

### Stratified K-Fold Cross Validation

This project uses **5-Fold Stratified K-Fold Cross Validation**.

The dataset is divided into five folds. During each iteration:

1. Four folds are used for training.
2. One fold is used for validation.
3. The process is repeated five times.
4. Each fold is used as validation data exactly once.
5. The accuracy scores from all folds are collected.
6. The average accuracy is calculated.

Stratified K-Fold Cross Validation is particularly suitable for classification problems because it maintains approximately the same class distribution in every fold.

---

## ⚙️ Project Workflow

The project follows the following workflow:

### Step 1: Import Libraries

Import the required Python libraries for:

* Data manipulation
* Data visualization
* Machine learning
* Model evaluation

### Step 2: Load the Dataset

The Breast Cancer Wisconsin Dataset is loaded using Pandas.

### Step 3: Explore the Dataset

The dataset is examined using:

* Dataset preview
* Dataset shape
* Column names
* Data types
* Statistical summary

### Step 4: Check Missing Values

The dataset is checked for missing values to ensure data quality.

### Step 5: Separate Features and Target

The dataset is divided into:

* **X:** Input features
* **y:** Target variable

### Step 6: Feature Scaling

The input features are standardized using **StandardScaler**.

Feature scaling helps ensure that all numerical features are on a similar scale.

### Step 7: Build the Machine Learning Pipeline

A machine learning pipeline is created that combines:

* StandardScaler
* Logistic Regression

This ensures that feature scaling is performed correctly during each cross-validation fold.

### Step 8: Configure Stratified K-Fold

The dataset is divided using:

* Number of Folds: **5**
* Shuffle: **True**
* Random State: **42**

### Step 9: Perform Cross Validation

The Logistic Regression model is evaluated using Stratified K-Fold Cross Validation.

The accuracy score is calculated for each fold.

### Step 10: Analyze Results

The following values are calculated:

* Accuracy of each fold
* Mean Cross-Validation Accuracy
* Standard Deviation

### Step 11: Generate Classification Report

The classification report provides important evaluation metrics such as:

* Precision
* Recall
* F1-Score
* Support

### Step 12: Generate Confusion Matrix

A confusion matrix is created to visualize the model's classification performance.

---

## 📈 Evaluation Metrics

The model is evaluated using the following metrics:

### Accuracy

Accuracy measures the proportion of correctly predicted observations.

### Precision

Precision measures how many predicted positive values are actually positive.

### Recall

Recall measures how many actual positive values are correctly identified.

### F1-Score

The F1-Score is the harmonic mean of Precision and Recall.

### Mean Cross-Validation Accuracy

This represents the average accuracy obtained across all folds.

### Standard Deviation

This measures the variation in accuracy scores across the folds.

---

## 📂 Project Structure

```text
Model-Evaluation-Using-KFold-Cross-Validation/
│
├── Breast_Cancer_Wisconsin_Dataset.csv
│
├── Model_Evaluation_Using_KFold_Cross_Validation.ipynb
│
└── README.md
```

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

Clone or download this repository to your local system.

### Step 2: Open Google Colab

Open the Jupyter Notebook using Google Colab.

### Step 3: Upload the Dataset

Upload the following dataset file:

```text
Breast_Cancer_Wisconsin_Dataset.csv
```

### Step 4: Run the Notebook

Run each code cell sequentially.

### Step 5: View Results

The notebook will display:

* Dataset information
* Missing value analysis
* Target class distribution
* Accuracy for each fold
* Mean Cross-Validation Accuracy
* Standard Deviation
* Classification Report
* Confusion Matrix

---

## 📊 Expected Output

After successfully running the project, the following results will be generated:

* Five individual cross-validation accuracy scores.
* Mean accuracy across all folds.
* Standard deviation of accuracy scores.
* Classification report.
* Confusion matrix.
* Visualization of cross-validation accuracy.

---

## ✨ Key Features

* Professional machine learning workflow.
* Uses the Breast Cancer Wisconsin Dataset.
* Implements Logistic Regression.
* Uses StandardScaler for feature preprocessing.
* Implements 5-Fold Stratified Cross Validation.
* Evaluates accuracy across multiple folds.
* Generates a classification report.
* Visualizes the confusion matrix.
* Suitable for academic and machine learning laboratory exercises.

---

## 📚 Learning Outcomes

After completing this project, you will understand:

* The importance of model evaluation.
* How K-Fold Cross Validation works.
* The difference between K-Fold and Stratified K-Fold Cross Validation.
* How to implement cross-validation using Scikit-learn.
* How to evaluate classification models.
* How to interpret accuracy scores.
* How to use classification reports.
* How to interpret confusion matrices.

---

## 📌 Conclusion

This project successfully demonstrates **Model Evaluation Using Stratified K-Fold Cross Validation** on the Breast Cancer Wisconsin Dataset.

The Logistic Regression model is evaluated multiple times using different subsets of the dataset. This provides a more reliable estimate of model performance compared to evaluating the model using a single train-test split.

Stratified K-Fold Cross Validation ensures that the distribution of target classes is maintained across all folds, making it particularly suitable for classification problems.

This project demonstrates the importance of cross-validation as a reliable technique for evaluating machine learning models.

---

## 👩‍💻 Author

**Prema Latha V**

**Artificial Intelligence and Data Science** 



