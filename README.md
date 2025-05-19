# valorant-leaderboard-eda

This notebook explores Valorant leaderboard data (Episode 4: Act 3), focusing on high-rank agent preferences and rating/winrate trends across regions. It includes preprocessing, exploratory charts, and a discussion of limitations in using incomplete or biased competitive data.

## 📊 Dataset
Source: https://www.kaggle.com/datasets/aliibrahim10/valorant-stats/data

Fields include: player name, region, agent choices, rating tier, win percentage, headshot stats, and more.

## Dashboard
▶️ **Live Tableau Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/gabriel.hu5222/viz/ValorantLeaderboardDashboardE4A3/Dashboard1?publish=yes)

## 🔧 Tools Used
- **Python** (`pandas`, `seaborn`, `matplotlib`)
- **Tableau Public** (interactive dashboard
- Jupyter Notebook
- GitHub

## 🧠 Key Questions Explored
- What are the most common agents among high-ranked players (Immortal and Radiant)?
- How does win percentage vary by agent (with sample size filtering)?
- How does average win percentage vary across rating tiers?
- What are the differences in average rating across well-represented regions?


## 📈 Sample Visualizations
![image](https://github.com/user-attachments/assets/ad8de7cc-e93a-4c0f-8d6a-f60ef401a73e)
![image](https://github.com/user-attachments/assets/25574356-540e-4d6d-895f-f7bdff6aa5e8)

## ✅ What I Learned
- Cleaned large datasets using pandas
- Created insights using groupby, sorting, and aggregation
- Visualized multi-variable relationships
- Practiced storytelling with data
- Identified and handled biases introduced by uneven sample sizes
- Learned how to reframe unclear questions based on data limitations

## 📌 Notes
- The dashboard includes **weapon usage trends** by region and rating, which were not part of the original notebook. These were added during exploratory design in Tableau for greater insight.
- NA values in the `region` column were cleaned and restored during preprocessing.
