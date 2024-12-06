# Iris virginica Analysis 🌺

This repository provides a detailed exploration of **Iris virginica**, one of the three flower species in the famous Iris dataset. The project utilizes statistical tools and machine learning techniques to analyze and classify this species based on its distinct features.

---

## ⚡ Brief Overview

The project trains a classification model using the *train* dataset to predict the species of a flower in the *test* dataset. The classification is based on the following features:  
- `sepal length`  
- `sepal width`  
- `petal length`  
- `petal width`  

---

## 📋 Summary

**Iris virginica** is one of the three species in the Iris dataset. This repository focuses specifically on:  
- Analyzing the biological characteristics of Iris virginica.  
- Comparing its attributes to other species (Iris setosa and Iris versicolor).  
- Training and evaluating classification models to predict species based on the given features.  

---

## 📂 Repository Structure

- `data/`: Contains the Iris dataset (`iris.csv`).  
- `notebooks/`: Jupyter notebooks with step-by-step analyses.  
- `images/`: Visualizations and graphs generated during the analysis.  
- `scripts/`: Python scripts for preprocessing, visualization, and modeling.  
- `README.md`: This explanatory document.  

---

## 🔍 Analysis Details

1. **Exploratory Data Analysis (EDA):**  
   - Distribution of Iris virginica features.  
   - Correlation analysis between petal and sepal dimensions.  

2. **Data Visualization:**  
   - Scatter plots to explore feature relationships.  
   - Boxplots to compare ranges across species.  

3. **Machine Learning Models:**  
   - Classification models to identify Iris virginica using the specified dimensions.  
   - Performance evaluation of models like Logistic Regression, Decision Trees, and SVM.  

---

## 📊 Key Findings

- Iris virginica generally has the longest petals and sepals compared to the other species.  
- `petal length` is the most distinctive feature for classification.  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher.  
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.  

### Installation
1. Clone this repository:  
   ```bash
   git clone https://github.com/crisrey211/kopuru-iris-aprendizaje-superviasdo.git
### 🛠️ Setting Up a Virtual Environment

It's recommended to use a virtual environment to manage dependencies for this project. Follow the steps below:

2. Create a Virtual Environment
    Run the following command to create a virtual environment named `.venv`:
    ```bash
    py -m venv .venv
### Activate the Virtual Environment

3. On Windows:
    ```bash
    .\.venv\Scripts\activate
4. On Linux/MacOS:
    ```bash
    source .venv/bin/activate
### Install Dependencies

5. On Linux/MacOS:
    ```bash
    `pip install -r requirements.txt`