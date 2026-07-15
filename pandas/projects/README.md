# 🎌 Anime Data Analysis & Feature Engineering

> A Python-based data analytics project that performs **Feature Engineering** and **Exploratory Data Analysis (EDA)** on an Anime dataset. The project transforms raw textual data into meaningful features and extracts valuable insights such as episode counts, airing duration, and top-rated anime.

---

## 📖 Project Overview

Raw datasets often contain information embedded within text fields that cannot be analyzed directly. In this project, feature engineering techniques are applied to extract structured information from the **Title** column of an Anime dataset.

The extracted features are then used to perform exploratory data analysis and answer interesting questions about anime rankings, episode counts, and airing duration.

---

## 🎯 Objectives

* Clean and preprocess the dataset.
* Extract episode counts from raw text.
* Extract anime airing duration.
* Calculate the total running duration in months.
* Perform exploratory data analysis using engineered features.
* Identify top-performing and longest-running anime.

---

## 📂 Dataset

The dataset contains information about anime such as:

* 🏆 Rank
* 🎌 Anime Title
* ⭐ Score
* 📺 Episode Information
* 📅 Airing Duration

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Datetime
* dateutil (relativedelta)

---

# ⚙️ Project Workflow

## 1️⃣ Data Loading

* Imported the Anime dataset using Pandas.
* Loaded the CSV file into a DataFrame for analysis.

---

## 2️⃣ Feature Engineering

### 📺 Episode Extraction

A custom Python function extracts the number of episodes from the **Title** column.

Example:

**Before**

```text
Fullmetal Alchemist: Brotherhood TV (64 eps)
```

**After**

```text
Episodes = 64
```

The extracted values are converted into integers for numerical analysis.

---

### 📅 Airing Duration Extraction

The project extracts the anime airing period from the title.

Example:

```text
Apr 2009 - Jul 2010
```

This information is stored in a new column named **Total Time**.

---

### 📆 Running Duration Calculation

Using Python's **datetime** and **relativedelta**, the project calculates the total running duration of each anime in months.

Example:

```text
Apr 2009 - Jul 2010

↓

16 Months
```

---

# 📊 Exploratory Data Analysis

The project answers several analytical questions, including:

* ⭐ Which anime has the highest score?
* 🥇 Top 5 highest-rated anime.
* 📺 Which anime has the highest episode count?
* ⏳ Which anime ran for the longest duration?
* 🔝 Top 5 anime with the most episodes.

---

# ✨ Features

* ✔ Feature Engineering
* ✔ Custom String Extraction
* ✔ Data Cleaning
* ✔ Date Parsing
* ✔ Duration Calculation
* ✔ Exploratory Data Analysis
* ✔ Sorting & Filtering
* ✔ Data Type Conversion

---

# 📁 Project Structure

```text
Anime-Data-Analysis/
│
├── anime.csv
├── Anime_Data_Analysis.ipynb
└── README.md
```

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/your-username/anime-data-analysis.git
```

## Navigate to the Project

```bash
cd anime-data-analysis
```

## Install Dependencies

```bash
pip install pandas numpy python-dateutil
```

## Run the Notebook

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

# 📈 Key Insights

This project successfully converts unstructured anime information into meaningful analytical features.

Some of the insights include:

* Highest-rated anime.
* Longest-running anime.
* Anime with the maximum number of episodes.
* Top 5 anime by rating.
* Top 5 anime by episode count.

---

# 💡 Skills Demonstrated

* Python Programming
* Pandas
* NumPy
* Feature Engineering
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Date & Time Manipulation
* String Processing
* Data Wrangling

---

# 🔮 Future Improvements

* Add data visualizations using Matplotlib and Seaborn.
* Perform genre-wise analysis.
* Build an interactive dashboard.
* Create an anime recommendation system.
* Apply machine learning models for predictive analytics.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!

