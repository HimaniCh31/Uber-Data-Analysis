# 🚖 Uber Rides Data Analysis

A comprehensive **Exploratory Data Analysis (EDA)** project on the Uber Rides Dataset using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This project analyzes ride patterns, trip purposes, travel distances, ride categories, and temporal trends to uncover meaningful business insights through data visualization and statistical analysis.

---

## 📌 Project Overview

This project focuses on understanding Uber ride data by performing data preprocessing, feature engineering, exploratory data analysis, and visualization. The analysis identifies ride frequency, travel patterns, popular trip purposes, ride distribution across months and weekdays, and distance-based insights.

The notebook demonstrates a complete EDA workflow, making it suitable for beginners and aspiring data analysts looking to strengthen their data analysis skills using Python.

---

## 🎯 Objectives

- Clean and preprocess Uber ride data.
- Handle missing values and duplicate records.
- Perform feature engineering on date and time attributes.
- Analyze ride categories and trip purposes.
- Study ride trends across months and weekdays.
- Examine ride distance distribution.
- Generate visual insights using Python libraries.
- Explore relationships between numerical variables using correlation analysis.

---

## 📂 Dataset

The project uses the **Uber Dataset** containing ride information such as:

- Start Date
- End Date
- Category
- Start Location
- Stop Location
- Miles Travelled
- Purpose of Trip

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | One-Hot Encoding |

---

## 📊 Project Workflow

### 1️⃣ Data Loading
- Imported dataset using Pandas.
- Explored dataset dimensions and structure.

### 2️⃣ Data Cleaning
- Filled missing values in the **Purpose** column.
- Converted date columns into datetime format.
- Removed null values.
- Removed duplicate records.

### 3️⃣ Feature Engineering
Created additional features including:

- Month
- Weekday
- Day/Night Classification

These features help analyze ride trends over time.

### 4️⃣ Exploratory Data Analysis

Performed visual analysis on:

- Ride Categories
- Trip Purposes
- Day vs Night Trips
- Monthly Ride Distribution
- Weekly Ride Distribution
- Ride Distance Distribution
- Outlier Detection using Boxplots
- Correlation Heatmap

### 5️⃣ Data Encoding

Applied **One-Hot Encoding** to categorical variables for further analysis.

---

## 📈 Visualizations Included

- Category Count Plot
- Purpose Count Plot
- Day vs Night Ride Analysis
- Purpose vs Category Comparison
- Correlation Heatmap
- Monthly Ride Analysis
- Weekday Ride Distribution
- Ride Distance Boxplots
- Ride Distance Distribution Plot

---

## 🔍 Key Insights

- Business and personal trips contribute significantly to ride frequency.
- Ride demand varies across different months.
- Ride distribution changes throughout the week.
- Most Uber rides are relatively short-distance trips.
- A small number of rides are outliers with significantly higher travel distances.
- Correlation analysis provides insights into relationships among numerical features.

---

## 📁 Project Structure

```
Uber-Rides-Data-Analysis/
│
├── Uber_Rides_Data_Analysis_using_Python.ipynb
├── UberDataset.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/Uber-Rides-Data-Analysis.git

cd Uber-Rides-Data-Analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```
Uber_Rides_Data_Analysis_using_Python.ipynb
```

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

You can also install using:

```bash
pip install -r requirements.txt
```

---

## 🎓 Learning Outcomes

This project demonstrates practical knowledge of:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Handling Missing Values
- Outlier Detection
- Correlation Analysis
- One-Hot Encoding
- Python for Data Analysis

---

## 📸 Sample Analysis

The notebook includes visualizations for:

- Ride Category Distribution
- Ride Purpose Analysis
- Monthly Ride Trends
- Weekly Ride Trends
- Correlation Heatmap
- Distance Distribution
- Boxplots for Outlier Analysis

---



## 👩‍💻 Author

**Himani**

- Python Developer
- Data Analyst
- AI & Generative AI Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository!
