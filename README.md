# Cognifyz Data Analysis Internship Program

> Exploratory Data Analysis on a Restaurant Dataset – Levels 1 & 2

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?style=for-the-badge&logo=pandas)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge&logo=matplotlib)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple?style=for-the-badge)](https://seaborn.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)](https://jupyter.org)

---

## 📑 Table of Contents

- [📁 Project Structure](#-project-structure)
- [📊 Dataset Overview](#-dataset-overview)
- [📓 Level 1 Notebook](#-level-1-notebook)
- [📓 Level 2 Notebook](#-level-2-notebook)
- [🛠️ Requirements](#️-requirements)
- [▶️ How to Run](#-how-to-run)
- [👤 Author](#-author)
- [📄 License](#-license)

---

## 📁 Project Structure

```
Cognifyz Data Analysis Internship Program/
├── README.md                                      # Project documentation
├── Dataset.csv                                    # Restaurant dataset used for analysis
├── Data Analysis Program PDF.pdf                  # Program reference document
├── Cognifyz_Data_Analysis_Level_1.ipynb           # Level 1 analysis notebook
└── Cognifyz_Data_Analysis_Level_2.ipynb           # Level 2 analysis notebook
```

---

## 📊 Dataset Overview

The analysis is based on **`Dataset.csv`**, which contains restaurant information across multiple cities.

| Column | Description |
|:-------|:------------|
| `Restaurant ID` | Unique identifier for each restaurant |
| `Restaurant Name` | Name of the restaurant |
| `Country Code` | Country code where the restaurant is located |
| `City` | City of the restaurant |
| `Address` | Full address |
| `Locality` | Area/locality name |
| `Longitude`, `Latitude` | Geographic coordinates |
| `Cuisines` | Type(s) of cuisine served |
| `Average Cost for two` | Approximate cost for two people |
| `Currency` | Currency used |
| `Has Table booking` | Table booking available (Yes/No) |
| `Has Online delivery` | Online delivery available (Yes/No) |
| `Price range` | Price category (1 = Low, 4 = High) |
| `Aggregate rating` | Overall customer rating |
| `Rating color`, `Rating text` | Visual and text rating label |
| `Votes` | Number of customer votes |

---

## 📓 Level 1 Notebook

**File:** `Cognifyz_Data_Analysis_Level_1.ipynb`

Level 1 focuses on **Exploratory Data Analysis** with four tasks:

| Task | Objective |
|:-----|:----------|
| **Task 1: Top Cuisines** | Identify top 3 most common cuisines and calculate their percentage |
| **Task 2: City-wise Online Delivery** | Find cities where >50% restaurants offer online delivery |
| **Task 3: Price Range Distribution** | Analyze price range distribution and visualize with a bar chart |
| **Task 4: Online Delivery Analysis** | Compare average ratings of restaurants with vs. without online delivery |

---

## 📓 Level 2 Notebook

**File:** `Cognifyz_Data_Analysis_Level_2.ipynb`

Level 2 covers **Advanced Analysis** with four tasks:

| Task | Objective |
|:-----|:----------|
| **Task 1: Restaurant Ratings** | Analyze rating distribution, find mode, and calculate average votes |
| **Task 2: Cuisine Analysis** | Explore cuisine patterns and their relationship with ratings |
| **Task 3: Geographic Mapping** | Clean lat/long data and plot restaurant locations by city |
| **Task 4: Restaurant Chains** | Identify restaurant chains and analyze outlets, ratings, and votes |

---

## 🛠️ Requirements

The notebooks use the following Python libraries:

| Library | Purpose |
|:--------|:--------|
| `pandas` | Data manipulation and analysis |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical data visualization |

**Install dependencies:**

```bash
pip install pandas matplotlib seaborn
```

---

## ▶️ How to Run

1. **Clone or download** this repository.
2. Ensure **`Dataset.csv`** is in the same directory as the notebooks.
3. Open either notebook in **Jupyter**, **JupyterLab**, or **Google Colab**:
   - `Cognifyz_Data_Analysis_Level_1.ipynb`
   - `Cognifyz_Data_Analysis_Level_2.ipynb`
4. **Run all cells** to reproduce the analysis and visualizations.

---

## 👤 Author

**Vikas Kumar Gupta**  
Data Analysis Intern – Cognifyz Internship Program

---

## 📄 License

This project is part of the **Cognifyz Data Analysis Internship Program** and is intended for educational and portfolio purposes.

---

<div align="center">

**Made with ❤️ for the Cognifyz Data Analysis Internship Program**

</div>