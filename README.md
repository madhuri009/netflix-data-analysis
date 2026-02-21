# 🎬 Netflix Data Analysis using SQL & Python
## 🎥 Project Demo Video
https://youtu.be/2Y_ykrWUJTs
## 📌 Project Overview
This project performs end-to-end data analysis on the Netflix dataset using **Python, SQL, pandas, and matplotlib**.  
It implements a **keyword-based dynamic query system** that converts user input into SQL queries and generates both **tabular and visual insights** automatically.

The system supports multiple analytical operations such as:
- Content distribution (Movies vs TV Shows)
- Year-wise trends
- Country-wise analysis
- Rating and genre analysis
- Dynamic filters (e.g., Movies after a given year)
- Automatic graph selection (Bar, Pie, Line)

---

## 🛠️ Tech Stack
- Python  
- pandas  
- SQLite (SQL integration)  
- matplotlib  
- Regular Expressions (for query parsing)

---

## ⚙️ Features
- Data cleaning and preprocessing (handling null values, date conversion, duration extraction)
- SQL + pandas integration for analytical queries
- Keyword-based natural language query mapping
- Dynamic query handling (e.g., *movies after 2018*, *TV shows in India*)
- Automatic visualization selection:
  - 📈 Line chart → Time series data  
  - 🥧 Pie chart → Small category distribution  
  - 📊 Bar chart → Category comparison
- Tabular + graphical output

---

## 📊 Supported Queries
Examples of user inputs:
- `movies vs tv shows`
- `top countries`
- `release year trend`
- `rating`
- `top genres`
- `movies after 2018`
- `tv shows in india`

The system maps these inputs to predefined analytical SQL queries.

---

## 🧹 Data Preprocessing Steps
- Converted `date_added` to datetime and extracted `year_added`
- Extracted numeric values from `duration` column
- Removed rows with missing values in key analytical columns

---

## 📈 Key Insights
- Netflix content increased significantly after 2016  
- Movies dominate the platform compared to TV shows  
- USA produces the highest number of titles on Netflix  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/madhuri009/netflix-data-analysis.git
   
