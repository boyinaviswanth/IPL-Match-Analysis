# 🏏 IPL Match Analysis (2008–2017)

### Exploratory Data Analysis of Indian Premier League Matches Using Python

![Python](https://img.shields.io/badge/Python-EDA-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0?style=for-the-badge)

---

## 📌 Project Overview

The **IPL Match Analysis** project is an Exploratory Data Analysis (EDA) project based on Indian Premier League match data from 2008 to 2017.

The project explores historical IPL matches to understand team performance, match outcomes, toss decisions, player achievements, venue patterns and other factors influencing match results.

Using Python and its data analysis and visualization libraries, the project identifies patterns and trends through data exploration and visual analysis.

## 🎯 Project Objectives

- Analyse the number of matches played across different IPL seasons.
- Examine team-wise match participation and victories.
- Identify teams with the highest number of wins.
- Understand toss decisions and their relationship with match outcomes.
- Identify players receiving the most Player of the Match awards.
- Analyse match distribution across cities and venues.
- Explore team performance across different venues.
- Examine matches affected by the Duckworth-Lewis (D/L) method.
- Analyse victories by winning runs and wickets.

## ❓ Business Questions

1. How has the number of IPL matches changed across seasons?
2. Which teams have played the most matches?
3. Which teams have recorded the highest number of victories?
4. Does winning the toss influence the match result?
5. Which toss decisions are more frequently selected?
6. Who are the most frequent Player of the Match award winners?
7. Which venues and cities have hosted the most matches?
8. Which teams perform well at different venues?
9. How frequently has the D/L method been applied?
10. What are the patterns in victories by runs and wickets?

## 📊 Analysis Performed

| Analysis Area | Description |
|---|---|
| Season Analysis | Number of matches played in each season |
| Venue Analysis | Matches distributed across venues and cities |
| Team Participation | Number of matches played by each team |
| Team Performance | Total wins recorded by each team |
| Toss Analysis | Toss decisions and toss-winning patterns |
| Player Performance | Top Player of the Match award winners |
| Umpire Analysis | Most frequently featured umpires |
| Match Outcomes | Comparison of toss winners and match winners |
| Venue-wise Performance | Team wins across cities and venues |
| D/L Method Analysis | Matches involving the Duckworth-Lewis method |
| Victory Analysis | Wins by runs and wickets |

## 🔍 Key Insights

| Analysis Area | Key Findings |
|---|---|
| **Season Analysis** | 2013 recorded the highest number of matches (approximately 76), while 2014 recorded the lowest (approximately 53). |
| **Venue Analysis** | M. Chinnaswamy Stadium hosted the highest number of matches among the venues analysed. |
| **City Analysis** | Mumbai hosted the highest number of matches, followed by Bangalore and Kolkata. |
| **Team Performance** | Mumbai Indians recorded the highest number of wins (approximately 91), followed by Chennai Super Kings and Kolkata Knight Riders. |
| **Toss Decision Analysis** | Teams chose to field first in 57.1% of tosses, while 42.9% chose to bat. |
| **Player Performance** | Chris Gayle received the most Player of the Match awards (18), followed by Yusuf Pathan (16). David Warner and AB de Villiers received 15 each. |
| **Umpire Analysis** | HDPK Dharmasena officiated the most matches (84), followed by S Ravi (83). |
| **Toss vs Match Winner** | In 51.4% of matches, the toss winner also won the match, while in 48.6% the toss winner lost. |
| **D/L Method Analysis** | 2016 recorded the highest number of D/L-affected matches (4). The 2009 and 2011 seasons recorded 3 each. |
| **Victory by Runs** | Winning margins by runs varied across teams, with the box plot highlighting differences in median margins and outliers. |
| **Victory by Wickets** | Winning margins by wickets also varied across teams, revealing differences in their match-winning patterns. |

## 🛠️ Tools & Technologies

- **Python** – Data analysis and exploration.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Jupyter Notebook** – Interactive analysis environment.

## 🗄️ Dataset

The project uses the IPL match dataset stored in:

`Data/matches.csv`

The dataset contains historical match-level information, including seasons, teams, toss decisions, match results, venues, cities, player awards and umpire details.

## 📁 Repository Structure

```text
IPL-Match-Analysis/
│
├── README.md
│
├── Python/
│   └── indian-premier-league.ipynb
│
├── Data/
│   └── matches.csv
│
└── Assets/
    └── screenshots/
        ├── 01_season_analysis.png
        ├── 02_venue_analysis.png
        ├── 03_city_analysis.png
        ├── 04_team_participation.png
        ├── 05_team_wins.png
        ├── 06_toss_decisions.png
        ├── 07_player_performance.png
        ├── 08_umpire_analysis.png
        ├── 09_toss_vs_match_winner.png
        ├── 10_dl_method_analysis.png
        ├── 11_victory_analysis.png
        └── 12_victory_by_wickets.png
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/boyinaviswanth/IPL-Match-Analysis.git
cd IPL-Match-Analysis
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the analysis

Open `Python/indian-premier-league.ipynb` and execute the notebook cells.

The notebook loads the dataset using a relative file path:

```python
ipl_df = pd.read_csv("../Data/matches.csv")
```

## 👤 Author

**Viswanth Boyina**

- GitHub: [boyinaviswanth](https://github.com/boyinaviswanth)
- LinkedIn: [Viswanth Boyina](https://www.linkedin.com/in/boyinaviswanth/)

---

*This project is an independent exploratory data analysis project using historical Indian Premier League match data.*
