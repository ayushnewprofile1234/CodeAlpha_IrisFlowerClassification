# CodeAlpha_IrisFlowerClassification
Iris flower classification using KNN
# 🌸 Iris Flower Classification — CodeAlpha Data Science Internship (Task 1)

This project is a part of the **CodeAlpha Data Science Internship**.  
We use the **Iris flower dataset** to build a **machine learning classification model** that can predict the species of an iris flower based on its petal and sepal measurements.

---

## 📌 Project Objective

The main goal is to train a machine learning model to **classify iris flowers** into one of the three species:
- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

We use **K-Nearest Neighbors (KNN)** algorithm for classification.

---

## 🧠 What is the Iris Dataset?

The Iris dataset is a famous dataset in the world of machine learning. It contains **150 samples** of iris flowers with the following features:

- **SepalLengthCm**
- **SepalWidthCm**
- **PetalLengthCm**
- **PetalWidthCm**
- **Species** (target/output)

---

## 🔧 Tools & Technologies Used

- Python 🐍
- Pandas (Data manipulation)
- Seaborn & Matplotlib (Data visualization)
- Scikit-learn (Model building)
- Google Colab (for development)

---

## 📊 Steps Performed in Project

1. **Data Loading**: Read the Iris dataset (`Iris.csv`) using Pandas.
2. **Data Cleaning**:
   - Removed `Id` column.
   - Checked for missing values.
3. **Data Visualization**:
   - Pairplots to understand feature relationships.
   - Heatmap to check correlation between features.
4. **Model Building**:
   - Used `KNeighborsClassifier` from scikit-learn.
   - Trained the model using 80% of the data.
5. **Model Evaluation**:
   - Predicted on test data (20%).
   - Checked accuracy and classification report.
   - Plotted Confusion Matrix.

---

## 📈 Output & Results

- **Model Accuracy**: ~100% (on test data)
- Model performed extremely well in classifying the species.
- Confusion matrix showed 100% correct classification on test set (for K=3).

---

## 🗂 Files Included

| File Name                  | Description                           |
|---------------------------|----------------------------------------|
| `iris_classification.ipynb` | Complete Jupyter Notebook code         |
| `Iris.csv` *(local only)*   | Dataset used (not included in repo)   |
| `README.md`               | Project summary and explanation       |

---

## 🎥 LinkedIn Video Explanation

> I have posted a short explanation video on LinkedIn with project summary and GitHub repo link as required by CodeAlpha internship.

---

## 🚀 Learning Outcomes

- Understood classification problem from scratch
- Got hands-on with data cleaning, visualization, and machine learning
- Built confidence in training and evaluating ML models using real-world data

---

## 🙌 Acknowledgment

Thanks to **CodeAlpha** for providing this internship opportunity and helping me build real-world data science skills.

🔗 [CodeAlpha Official Website](https://www.codealpha.tech)

---

