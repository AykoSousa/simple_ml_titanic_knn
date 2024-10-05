# Simple Classification Project: Titanic Survivors Analysis with KNN

This machine learning project aims to classify the survivors and non-survivors of the Titanic disaster using the K-Nearest Neighbors (KNN) model. The dataset used contains simplified information with the columns "Age," "Fare," and "Survived." The programming language used was Python.

## 📋 Project Description

The main goal of this project is to build a predictive model that can classify whether a person survived the Titanic disaster based on their characteristics. For this, only three attributes from the original dataset were used:
- **Age**: The age of the passengers
- **Fare**: The fare paid by the passenger
- **Survived**: Binary indicator of survival (0 = did not survive, 1 = survived)

The chosen classification model was **K-Nearest Neighbors (KNN)**, a simple and effective algorithm for classification problems.

## 🛠️ Technologies Used

- **Language**: Python
- **Libraries**:
  - `pandas`: For data manipulation and cleaning
  - `scikit-learn`: For implementing the KNN model and preprocessing
  - `matplotlib` and `seaborn`: For data visualization
  - `numpy`: For mathematical operations

## ⚙️ Implementation

### Data Preprocessing

The data was cleaned to handle missing values and standardized to ensure the KNN model's optimal performance. The steps include:
- In the age column, null values ​​were found, so fill in the average age of the passengers.
- Splitting the data into training and testing sets (using 80% for training and 20% for testing)

### KNN Model

The KNN algorithm was used to predict the **Survived** column based on the "Age" and "Fare" columns. The **y** value was chosen experimentally to achieve the best performance.

### Model Evaluation

The model's performance was evaluated using the following metrics:
- **Accuracy**: Percentage of correct predictions
- **Confusion Matrix**: To observe the distribution of classification errors
- **Classification Report**: Includes precision, recall, and F1-score

## 🔍 Results

The obtained results were satisfactory, considering the simplicity of the model and the limited number of variables. The final accuracy was approximately `69,95%`. The model proved to be effective in identifying survival patterns with the selected columns.

## 📈 Visualizations

Graphs were generated for data and result analysis, including:
- Counting survivors and non-survivors
- What is the best number of neighbors to set?
- Confusion Matrix

## 📝 Conclusions

This project demonstrates the practical use of the KNN model in a binary classification problem. Despite the simplicity of the data used, the model showed promising results, indicating that even with a few variables, it is possible to build significant predictive models.

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/AykoSousa/simple_ml_titanic_knn.git
   ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
