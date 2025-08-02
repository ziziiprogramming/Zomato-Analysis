# Zomato-Analysis
A data-driven exploration and visualization of restaurant trends using the Zomato dataset. This project aims to extract actionable insights from real-world data about restaurants, cities, cuisines, and customer preferences.

---

## Project Objectives

- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA) to uncover hidden patterns.
- Visualize key insights using Matplotlib and Seaborn.
- Understand how ratings, cuisines, votes, and pricing vary across cities and restaurants.

---

## Dataset

- **Source:** [Kaggle – Zomato Restaurants Data](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)
- **Rows:** 9,551  
- **Columns:** 21  
- **Attributes Include:** Restaurant Name, Location, Cuisines, Price Range, Votes, Ratings, Delivery Options, etc.

---

## Data Cleaning

- Checked and removed **missing/null values**.
- Removed **duplicates**.
- Verified **column names** and data types.
- Dropped irrelevant fields for analysis.

---

## Exploratory Data Analysis

- Top restaurant chains on Zomato.
- Most popular cuisines across cities.
- Distribution of ratings and votes.
- Cities with the most Zomato-listed restaurants.
- Price range vs Rating/Popularity.
- Delivery trends and booking availability.

---

## Visualizations

Implemented insightful visualizations using:

- `Matplotlib`
- `Seaborn`

Examples:
- Bar plots (e.g., most popular cuisines)
- Pie charts (e.g., delivery vs non-delivery)
- Count plots (e.g., restaurant count by city)
- Heatmaps (e.g., correlation matrix)

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/ziziiprogramming/zomato-data-analysis.git
   cd zomato-data-analysis

2. Install Dependencies
Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate

3. Then install requirements:
pip install -r requirements.txt

3. Run the Notebook:
jupyter notebook zomato_analysis.ipynb

OR 
If you're using VS Code:

1. Open the project folder.
2. Open zomato_analysis.ipynb.
3. Run all cells from the toolbar.

Dataset:
- Make sure the zomato.csv dataset is in the project folder.

- If not, download it from Kaggle and place it in the same directory.
