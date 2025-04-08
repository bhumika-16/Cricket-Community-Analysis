# 🏏 Analysis of Cricket Community Based on Social Network

This project presents a novel approach to quantify and rank the performance of individual players and teams in the Indian Premier League (IPL) 2020 using **Social Network Analysis (SNA)** and **Machine Learning (ML)**.

## 📌 Objective

To analyze individual and team performance in cricket by treating players as nodes in a social network and interactions (like batting partnerships or bowler-batsman duels) as edges. The performance insights are validated using ML techniques.

---

## 📊 Key Contributions

- Developed graph-based models to analyze batsmen-bowler and batsmen-batsmen interactions.
- Introduced **Performance Centrality** metrics for players and teams.
- Created **network models** for:
  - Batsman-Batsman (Partnership Network)
  - Batsman-Bowler
  - Bowler-Batsman
- Computed **centrality metrics** like:
  - Weighted Degree Centrality
  - Closeness Centrality
  - Betweenness Centrality
  - Eigenvector Centrality
  - PageRank
- Proposed custom indices like:
  - **Performance Index of Batsman (PIB)**
  - **Quality Index of Bowler (QIB)**
  - **Performance Centrality of Team (PCT)**

---

## 🧪 Machine Learning Component

- **Algorithm Used:** Random Forest Classifier
- **Input Features:** Toss winner, Toss decision, Team names
- **Output:** Predicted match winner
- **Data Source:** IPL match results (2014–2019 for training, 2020 for testing)

---

## 🧮 Datasets Used

- IPL 2020 Delivery-wise Data
- Career Bowling Averages
- IPL Match Results (2014–2020)
- Point Tables

---

## 📈 Results

| Metric                     | Accuracy     |
|---------------------------|--------------|
| Top 10 Batsmen (SNA vs IPL) | 87.81%       |
| Top 10 Bowlers (SNA vs IPL) | 74.19%       |
| Team Ranking (SNA vs IPL)   | 87.5%        |
| Team Ranking (ML vs IPL)    | 87.85%       |
| ML vs SNA                  | 91.66%       |

---

## 🧠 Insights

- Centrality metrics highlight **key players and partnerships**.
- ML model supports the SNA-based rankings.
- Project proves strong **correlation** between network-based performance and actual tournament outcomes.

---

## 🛠️ Tech Stack

- **Languages:** Python, R
- **Libraries:** NetworkX, Pandas, Scikit-learn, Matplotlib
- **Data Sources:** Kaggle, IPLT20, Cricinfo

---

## 📁 Folder Structure

