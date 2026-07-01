# Exploratory Data Analysis 

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the data through descriptive statistics and visualizations. The analysis helps identify distributions, feature relationships, trends, and anomalies before applying machine learning models.

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about passengers aboard the Titanic, including demographics, ticket details, fare, cabin, passenger class, and survival status.

---

## 🎯 Objectives

* Explore the dataset and understand its structure.
* Generate descriptive statistics.
* Visualize the distribution of numerical features.
* Detect outliers using boxplots.
* Analyze relationships between features using pairplots and correlation matrices.
* Draw meaningful insights from the visualizations.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Plotly

---

## 📁 Project Structure

```text
EDA_Elevate_Labs/
│── Titanic-Dataset.csv
│── eda.py
│── README.md
```

---

## ⚙️ Exploratory Data Analysis Steps

### 1. Import the Dataset

* Loaded the Titanic dataset using Pandas.
* Displayed the first few rows.
* Explored the dataset structure using:

  * `head()`
  * `info()`
  * `describe()`
  * `isnull().sum()`

---

### 2. Generate Summary Statistics

Calculated descriptive statistics including:

* Mean
* Median
* Standard Deviation
* Minimum
* Maximum
* Quartiles

These statistics provide an overview of the numerical features.

---

### 3. Histogram Visualization

Created histograms to understand the distribution of numerical features such as:

* Age
* Fare

Histograms help identify skewness, spread, and concentration of values.

---

### 4. Boxplot Visualization

Generated boxplots to:

* Detect outliers
* Observe the spread of numerical data
* Compare distributions

---

### 5. Pairplot Analysis

Used Seaborn's `pairplot()` to visualize pairwise relationships between numerical variables.

This helps identify:

* Trends
* Correlations
* Clusters
* Potential outliers

---

### 6. Correlation Matrix

Computed the correlation matrix and visualized it using a heatmap.

The heatmap highlights:

* Positive correlations
* Negative correlations
* Strength of relationships between numerical features

---

### 7. Interactive Visualizations

Used Plotly to create interactive visualizations including:

* Histogram
* Scatter Plot

These interactive plots make it easier to explore the dataset.

---

## 📊 Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/VigneshMallapuram/EDA_Elevate_Labs.git
```

### 2. Navigate to the project folder

```bash
cd EDA_Elevate_Labs
```

### 3. Install the required libraries

```bash
pip install pandas matplotlib seaborn plotly
```

### 4. Run the program

```bash
python eda.py
```

---

## 📈 Key Insights

* Most passengers were between **20 and 40 years** of age.
* The **Fare** distribution is highly right-skewed.
* Boxplots reveal several outliers in the **Fare** feature.
* Passenger class (**Pclass**) has a noticeable relationship with fare.
* The correlation matrix indicates weak to moderate correlations among most numerical features.

---

## 📚 Learning Outcomes

Through this project, I learned how to:

* Perform Exploratory Data Analysis (EDA).
* Generate descriptive statistics using Pandas.
* Visualize data distributions using histograms.
* Detect outliers with boxplots.
* Analyze feature relationships using pairplots.
* Interpret correlation matrices and heatmaps.
* Build interactive visualizations with Plotly.
* Draw meaningful insights from real-world datasets.

---

## 👨‍💻 Author

**Vignesh Mallapuram**

GitHub: https://github.com/VigneshMallapuram
