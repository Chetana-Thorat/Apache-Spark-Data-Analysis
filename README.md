
# 🏏 Apache Spark IPL Data Analysis

---

## 🚀 Overview

This project performs large-scale data analysis on **Indian Premier League (IPL)** datasets using **Apache Spark** on **Azure Databricks**. It showcases how distributed computing can be applied to derive insights from real-world cricket data.

- **Goal:** Use PySpark to analyze IPL data (till 2017) covering teams, matches, players, and deliveries.
- **Platform:** Azure Databricks
- **Tech Stack:** Apache Spark · PySpark · Databricks · Python · CSV

---

## 🛠 Technologies Used

- **Apache Spark (PySpark)** – Distributed processing of large datasets
- **Azure Databricks** – Cloud environment for Spark development
- **Python** – For writing Spark logic and transformations
- **CSV Files** – Used as the input IPL dataset format
- **Git & GitHub** – Version control and project hosting

---

## 📁 Project Structure

```

apache\_spark\_project/
├── dataset/                              # IPL CSV files
│   ├── Ball\_By\_Ball.csv
│   ├── Match.csv
│   ├── Player.csv
│   ├── Player\_match.csv
│   └── Team.csv
│
├── IPL\_data\_analysis\_spark.ipynb         # Main Databricks notebook with PySpark logic
└── README.md                             # Documentation

```

---

## 📌 How It Works

1. **Data Loading:** Load all CSV files as Spark DataFrames using `spark.read.csv()`.
2. **Exploration:** Inspect schemas, clean missing values, and understand data distributions.
3. **Analysis:** Perform analytical queries using `groupBy`, `join`, `agg`, `filter`, etc.
4. **Insights Derived:**
   - Top-performing players and teams
   - Toss-winning impact
   - Venue-based match trends
   - Most common dismissal types
   - Player contributions by season

---

## 📊 Dataset Used

This dataset is publicly available and contains comprehensive IPL match data till 2017.  
🔗 [Source: IPL Data on data.world](https://data.world/mkhuzaima/ipl-data-till-2017)

Included files:
- `Ball_By_Ball.csv` – Each delivery across all IPL matches
- `Match.csv` – Match metadata
- `Player.csv` – Player details
- `Player_match.csv` – Player participation records
- `Team.csv` – Team names and codes

---

## 🧠 Learnings

- Hands-on experience with PySpark and lazy evaluation
- Schema inference, null handling, and column manipulation
- Performing joins, aggregates, and filters at scale
- Real-time development and visualization in Databricks
- End-to-end pipeline from data import to insight generation

---

## 🙌 Author

**Chetana Thorat**  
📧 thoratchetana8@gmail.com  
🎓 Master's in Data Science @ Indiana University Bloomington  
🔗 [LinkedIn](https://www.linkedin.com/in/chetana-thorat) | [GitHub](https://github.com/Chetana-Thorat)

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
```
