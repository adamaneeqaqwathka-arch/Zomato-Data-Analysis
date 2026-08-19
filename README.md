# Zomato Data Analysis

## 📌 Project Overview

This project focuses on analyzing Zomato restaurant data to understand restaurant characteristics, customer reviews, ratings, cuisines, locations, and other factors that influence restaurant performance.

The project uses Python and popular data analysis and visualization libraries to perform data cleaning, exploratory data analysis (EDA), visualization, and derive meaningful insights from the dataset.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand and explore the Zomato restaurant dataset.
* Clean and preprocess the available data.
* Analyze restaurant ratings and customer reviews.
* Identify popular cuisines and restaurant categories.
* Analyze restaurant distribution across locations.
* Study factors associated with restaurant ratings.
* Visualize important patterns and trends in the data.
* Generate meaningful business insights from the analysis.

---

## 📂 Dataset

The project uses two datasets:

### 1. Restaurant Metadata

**File:** `Zomato Restaurant names and Metadata.csv`

This dataset contains restaurant-level information such as:

* Restaurant name
* Location
* Address
* Cuisine
* Ratings
* Cost information
* Restaurant type
* Other restaurant metadata

### 2. Restaurant Reviews

**File:** `Zomato Restaurant reviews.csv`

This dataset contains customer review information that can be used to analyze:

* Customer feedback
* Review ratings
* Restaurant-wise reviews
* Customer sentiment and opinions

---

## 🗂️ Project Structure

```text
Zomato-Data-Analysis/
│
├── data/
│   ├── Zomato Restaurant names and Metadata.csv
│   └── Zomato Restaurant reviews.csv
│
├── notebooks/
│   └── Zomato_Data_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computing
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and clustering
* **Jupyter Notebook** – Development and analysis environment

---

## 🔍 Analysis Performed

The project includes the following stages:

### 1. Data Loading

The datasets are loaded using Pandas and their structure is examined.

### 2. Data Understanding

The dataset is analyzed using operations such as:

* `head()`
* `tail()`
* `shape`
* `info()`
* `describe()`
* `isnull()`
* `nunique()`
* `value_counts()`

### 3. Data Cleaning

The data is checked and processed for:

* Missing values
* Duplicate records
* Incorrect data types
* Inconsistent values
* Unnecessary columns

### 4. Exploratory Data Analysis

Different aspects of the dataset are explored, including:

* Restaurant ratings
* Restaurant locations
* Popular cuisines
* Cost distribution
* Restaurant types
* Customer reviews
* Rating patterns

### 5. Data Visualization

Visualizations are created to identify patterns and relationships in the data.

Examples include:

* Bar charts
* Histograms
* Count plots
* Box plots
* Distribution plots
* Heatmaps

### 6. Machine Learning / Clustering

The cleaned restaurant data can also be used to group restaurants with similar characteristics using clustering techniques.

This can help identify different restaurant segments based on attributes such as:

* Ratings
* Cost
* Cuisine
* Location
* Customer engagement

---

## 📊 Key Insights

The analysis aims to answer questions such as:

* Which locations have the highest number of restaurants?
* Which cuisines are most popular?
* What is the distribution of restaurant ratings?
* Which restaurants receive higher customer ratings?
* How does cost relate to restaurant ratings?
* What factors may influence restaurant performance?
* Can restaurants be grouped into meaningful clusters?

The final insights will be documented in the Jupyter Notebook after completing the analysis.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/adamaneeqaqwathka-arch/Zomato-Data-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Zomato-Data-Analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Navigate to:

```text
notebooks/Zomato_Data_Analysis.ipynb
```

Run the cells sequentially to reproduce the analysis.

---

## 📈 Future Improvements

Potential improvements to the project include:

* Sentiment analysis of customer reviews.
* Restaurant recommendation system.
* Advanced clustering using different algorithms.
* Interactive dashboards using Power BI or Tableau.
* Predicting restaurant ratings.
* Building a restaurant recommendation model.
* Deploying the analysis as a web application.

---

## 👨‍💻 Author

**Adam Aneeq Aqwath K.A**

Computer Science & Design Engineering Student
Atria Institute of Technology

---

## ⭐ Project Status

🚧 **Currently under development**

The project is being developed as part of a data analysis and machine learning project.
