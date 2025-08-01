# 🏏 IPL Match & Player Performance Analysis (EDA + Insights)

## 📌 Project Overview
This project analyzes **Indian Premier League (IPL)** data to uncover insights about **teams, players, venues, and seasons** using **Python**.  
It demonstrates **Data Analyst skills** like data cleaning, exploratory data analysis (EDA), visualization, and insights reporting.

**Key Features:**
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Team, Player, Venue, and Season Insights  
- Extended Analysis: Toss Impact, Win Percentage, Death Overs Performance, Boundary Analysis  
- Summary Report Generation  


## 📂 Dataset
- **Source:** [Kaggle IPL Dataset](https://www.kaggle.com/datasets/nowke9/ipldata)  
- **Files Used:**
  - `matches.csv` → Match-level details (season, teams, venue, winner, toss, etc.)  
  - `deliveries.csv` → Ball-by-ball details (runs, wickets, batsmen, bowlers, etc.)  


## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  - `Pandas` → Data Cleaning & Manipulation  
  - `NumPy` → Numerical Analysis  
  - `Matplotlib` & `Seaborn` → Data Visualization  

## 📊 Project Workflow

### 1️⃣ Data Collection
- Imported `matches.csv` and `deliveries.csv`  
- Merged both datasets for **ball-by-ball + match-level analysis**  

### 2️⃣ Data Cleaning
- Handled missing values (abandoned matches, umpire columns)  
- Removed irrelevant columns like `umpire3`  
- Converted data types where needed  

### 3️⃣ Exploratory Data Analysis (EDA)
- **Season Analysis:** Matches per season  
- **Team Performance:** Top winning teams, toss impact on match results  
- **Player Performance:** Top run scorers, wicket takers, and Player of the Match awards  
- **Venue Analysis:** Top stadiums hosting most matches  

### 4️⃣ Advanced Insights
- Team **Win Percentage**  
- **Toss Impact by Venue**  
- **Top Batsmen with Strike Rate**  
- **Death Overs (16-20) Performance**  
- **Boundary Analysis (4s & 6s)**

### 5️⃣ Insights & Reporting
- Key patterns and trends extracted  
- Saved reports as CSV for future dashboard creation  


## 📈 Key Insights

### 🔹 Teams
- Mumbai Indians have the highest overall win percentage  
- Toss-winning teams win ~52% of the matches  

### 🔹 Players
- Virat Kohli is the top run scorer  
- Lasith Malinga is the top wicket-taker  

### 🔹 Venues & Seasons
- Wankhede Stadium hosts the most matches  
- 2013 & 2019 had the highest number of matches  

🔹 Future Enhancements
Add real-time IPL data using Web Scraping or Cricinfo API

Create Interactive Dashboard using Streamlit or Power BI

Add Match Winner Prediction Model using Machine Learning

👤 Author
Vanaja P – Aspiring Data Analyst / Data Scientist
