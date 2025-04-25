# Task2-heart-disease-EDA  
# Heart Disease Dataset - Exploratory Data Analysis (EDA)

This project was completed as part of the AI & ML Internship Task 2. The goal is to perform Exploratory Data Analysis (EDA) using statistical methods and visualizations to gain insights into the dataset.

---

## Objective

Learn how to:
- Generate summary statistics
- Visualize data using histograms, boxplots, pairplots, and heatmaps
- Identify correlations and patterns
- Detect anomalies and skewness

---

## Dataset
We used the [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

---

## Tools & Libraries

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for data visualization

---

## Steps Performed

### 1. Imported Dataset
Loaded the dataset and displayed the first few rows along with info and statistical summary.

### 2. Summary Statistics
- Used `.describe()` and `.info()` to understand feature types and distributions.
- Checked for missing values (there were none).

### 3. Visualized Distributions
- Plotted **histograms** for all numeric features to understand their distribution.
- Plotted **boxplots** to detect outliers in features like `chol`, `trestbps`, and `thalach`.

### 4. Correlation Matrix & Heatmap
- Used `.corr()` to compute feature correlations.
- Created a **heatmap** to visualize relationships between variables.

### 5. Pairplot
- Plotted a **pairplot** colored by the `target` variable to observe clustering and feature relationships.

### 6. Skewness Check
- Measured skewness for all numeric features using `.skew()` to check for data asymmetry.

---

## Visualizations Included

- Histograms
- Boxplots
- Correlation heatmap
- Pairplot

---

## Final Outcome

A deep understanding of the dataset’s structure, distribution, and relationships between features — essential for building effective ML models in later tasks.

