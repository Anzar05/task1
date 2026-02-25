# task1
# COVID-19 Data Analysis and Visualization

## 📌 Project Overview

This project analyzes a COVID-19 patient dataset using **Python, Pandas, and Matplotlib**.
The goal is to clean the dataset and visualize important trends such as:

* Daily COVID-19 Cases
* Daily Deaths
* Recovery Trends

The project demonstrates basic data analysis steps including **data loading, cleaning, processing, and visualization**.

---

## 📂 Dataset

The dataset used in this project contains COVID-19 patient records with information such as:

* Age
* Gender
* Medical conditions
* ICU admission
* Date of death

The dataset file used:

```
Covid Data.csv
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook / VS Code

---

## ⚙️ Installation

1. Install Python (if not installed)
2. Install required libraries:

```bash
pip install pandas matplotlib
```

---

## 📊 Data Cleaning Steps

The dataset was cleaned before visualization:

* Removed duplicate records
* Converted column names to uppercase
* Replaced invalid values (97, 98, 99, 9999-99-99)
* Converted `DATE_DIED` to datetime format
* Removed missing ages
* Created a new column:

```
DIED = True  → Patient died
DIED = False → Patient recovered
```

---

## 📈 Visualizations

### 1️⃣ Daily Cases

Bar chart showing estimated daily COVID-19 cases.

### 2️⃣ Daily Deaths

Bar chart showing number of deaths per day.

### 3️⃣ Recovery Trends

Bar chart showing daily recovery trends.

### 4️⃣ Death vs Recovery Ratio

Pie chart showing the percentage of deaths and recoveries.

---

## ▶️ How to Run

1. Place the dataset file in the project folder:

```
Covid Data.csv
```

2. Run the Python script:

```bash
python covid_analysis.py
```

or run in Jupyter Notebook.

---

## 📷 Output

The program generates:

* Daily Cases Chart
* Daily Deaths Chart
* Recovery Trend Chart
* Death vs Recovery Pie Chart

---

## 🎯 Learning Outcomes

From this project, you will learn:

* How to load datasets using Pandas
* How to clean real-world data
* How to create visualizations
* How to analyze trends
* Basic data science workflow

---

## 📁 Project Structure

```
covid-data-analysis/
│
├── Covid Data.csv
├── covid_analysis.py
└── README.md
```

---

## 👤 Author

**Name:** SHAIK MAHAMOOD ANZAR
**Project:** COVID-19 Data Analysis
**Tools:** Python, Pandas, Matplotlib

---

## 📜 License

This project is for educational purposes.
