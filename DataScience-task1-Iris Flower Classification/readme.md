# Iris Flower Classification Using Machine Learning

## Oasis Infobyte – Data Science Internship

### Project Overview
This project focuses on classifying Iris flowers into three species: Setosa, Versicolor, and Virginica using Machine Learning algorithms.

The project uses the Iris dataset available in Scikit-learn. Exploratory Data Analysis (EDA), data visualization, model training, and performance evaluation are performed.

### Objective
To develop a Machine Learning model that predicts the species of an Iris flower based on its sepal and petal measurements. Logistic Regression and K-Nearest Neighbors (KNN) algorithms are trained and compared to identify the better-performing model.

### Dataset
The Iris dataset contains:
- 150 flower samples
- 3 species: Setosa, Versicolor, and Virginica
- 4 input features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

The dataset is loaded directly using `sklearn.datasets.load_iris()`.

### Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### Project Workflow
1. Import required Python libraries.
2. Load the Iris dataset.
3. Convert the dataset into a Pandas DataFrame.
4. Perform Exploratory Data Analysis (EDA).
5. Visualize the data using pairplots and boxplots.
6. Discuss feature selection.
7. Split the dataset into training and testing sets (80:20).
8. Train Logistic Regression and KNN classifiers.
9. Generate predictions using both models.
10. Evaluate models using accuracy, confusion matrices, precision, recall, and F1-score.
11. Compare both models and select the best-performing model.

### Model Performance

| Machine Learning Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| K-Nearest Neighbors (KNN) | 93.33% |

### Best Performing Model
Logistic Regression achieved an accuracy of **96.67%**, while KNN achieved 93.33%.

Therefore, Logistic Regression was selected as the best-performing model for this project based on its higher test accuracy and macro F1-score.

### Conclusion
The Iris Flower Classification project demonstrates how Machine Learning can be used to classify flower species based on physical measurements.

Both Logistic Regression and KNN performed well. Logistic Regression achieved the higher accuracy of 96.67%.

This project provided practical experience in data analysis, visualization, model training, and evaluation.


### Author
**Bhushan Hiralal Patel**

Data Science Intern – Oasis Infobyte
