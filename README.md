# 🏏 IPL Data Analysis (2008–2023)

## 📌 Objective
Analyze 15+ years of IPL data to uncover match-winning patterns,
player performance trends, and venue characteristics — and translate
each finding into actionable team/auction recommendations.

---

## 🔑 Key Findings & Business Recommendations

### 1. Toss vs Match Win
- Toss winners won only 50.8% of matches
- **Recommendation:** Toss impact is largely a myth — teams should
  focus on execution rather than toss strategy

### 2. All Time Greats
- V Kohli leads run scorers with 8014 runs — 1300 ahead of #2
- YS Chahal leads wicket takers with 213 wickets
- **Recommendation:** Spinners dominate the top 5 wicket takers list —
  teams should prioritize quality spinners in auctions over pace bowlers

### 3. Venue Analysis
- HPCA & Arun Jaitley Stadium are most batting friendly (185, 184 avg runs)
- Maharashtra CCA & Ekana Stadium favor bowlers (169, 170 avg runs)
- **Recommendation:** Teams should adjust playing strategy based on venue like
  extra batsman at HPCA, extra spinner at Maharashtra CCA

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Dataset
Kaggle IPL Complete Dataset (2008–2023)

---

## 📁 Project Structure
ipl-analysis/
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── ipl_analysis.ipynb
├── README.md
└── images/
    ├── toss_analysis.png
    ├── top_performers.png
    └── venue_analysis.png
