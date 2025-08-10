# Exploratory-Data-Analysis-EDA-on-Iris-Dataset
# Iris Dataset EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the famous **Iris dataset** to understand its structure, feature relationships, and data distributions.

## 🎯 Objectives
- Load and inspect the Iris dataset.
- Clean and validate the data.
- Generate statistical summaries.
- Visualize feature distributions and correlations.
- Derive insights from observed patterns.

## 🛠️ Technologies Used
- Python 3
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## 📂 Steps Performed
1. **Dataset Loading**  
   - Loaded the dataset using `sklearn.datasets.load_iris()`.
2. **Data Overview**  
   - Viewed the first few rows, dataset shape, structure, and checked for missing values.
3. **Statistical Summary**  
   - Generated descriptive statistics using Pandas.
4. **Visualizations**  
   - Histograms for feature distributions.  
   - Pairplot for feature relationships by species.  
   - Boxplots for comparing feature distributions across species.  
   - Heatmap for correlation analysis.
5. **Insights**  
   - Dataset contains 150 rows and 5 columns (4 numeric features + 1 target).  
   - Three species, each with 50 samples.  
   - Strong correlation between petal length and petal width.  
   - Setosa generally has smaller petals and sepals.

## ▶️ How to Run
### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/iris-eda.git
cd iris-eda
pip install -r requirements.txt
jupyter notebook iris_eda.ipynb
python iris_eda.py
