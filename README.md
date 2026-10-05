<div align="center">

# 🌍 Global Happiness Analysis

### Exploring the Factors Behind Life Evaluation Across Countries (2011–2025)

<p>
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-Visualization-76B900?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/github/repo-size/PalAnghan/Global-Happiness-Analysis?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/PalAnghan/Global-Happiness-Analysis?style=flat-square" />
  <img src="https://img.shields.io/github/languages/top/PalAnghan/Global-Happiness-Analysis?style=flat-square" />
  <img src="https://img.shields.io/github/license/PalAnghan/Global-Happiness-Analysis?style=flat-square" />
</p>

### 📊 From raw data → analysis → visual storytelling → insights

</div>

---

## 🎬 Project Demo

<div align="center">

### ▶️ Watch the Full Project Walkthrough

**[🎥 OPEN DEMO VIDEO](YOUR_GOOGLE_DRIVE_VIDEO_LINK)**

*The demo explains the project, dataset, cleaning process, analysis, visualizations, India findings, and final conclusion.*

</div>

---

## ✨ Project at a Glance

<table>
<tr>
<td>🌎 <b>Scope</b><br>Global happiness</td>
<td>📅 <b>Period</b><br>2011–2025</td>
<td>📊 <b>Records</b><br>2,116</td>
<td>📈 <b>Columns</b><br>13</td>
</tr>
<tr>
<td>🇮🇳 <b>Focus</b><br>India analysis</td>
<td>🏆 <b>Ranking</b><br>2025 countries</td>
<td>🔗 <b>Analysis</b><br>Correlation</td>
<td>📓 <b>Notebook</b><br>Jupyter</td>
</tr>
</table>

---

## 🎞️ Animated Preview

> 💡 **Tip:** Add a short screen-recording GIF of your notebook/dashboard here. A 5–10 second looping GIF makes the repository immediately more visual.

```text
assets/
└── demo.gif
```

```markdown
![Global Happiness Analysis Demo](assets/demo.gif)
```

---

## 🧭 Quick Navigation

<details open>
<summary><b>📚 Explore this project</b></summary>

- [📌 Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [❓ Research Questions](#-research-questions)
- [📂 Dataset](#-dataset)
- [🛠️ Tech Stack](#️-tech-stack)
- [🗂️ Project Structure](#-project-structure)
- [🔄 Workflow](#-analysis-workflow)
- [🔗 Correlation Analysis](#-correlation-analysis)
- [📈 Global Trends](#-global-happiness-trends)
- [🏆 2025 Ranking](#-2025-country-ranking)
- [🇮🇳 India Analysis](#-india-analysis)
- [📊 Visualizations](#-visualizations)
- [🧠 Key Findings](#-key-findings)
- [⚠️ Limitations](#️-limitations)
- [🚀 Future Scope](#-future-scope)
- [▶️ Run Locally](#️-run-locally)
- [📌 Project Status](#-project-status)
- [💡 Why I Chose This Project](#-why-i-chose-this-project)
- [👨‍💻 Author](#-author)

</details>

---

## 📌 Project Overview

**Global Happiness Analysis** is an exploratory data analytics project that studies life evaluation across countries and years using the **World Happiness Report 2026 – Data for Figure 2.1 (2011–2025)** dataset.

The project goes beyond simply listing happiness rankings. It investigates global trends, relationships between life evaluation and explanatory factors, country-level differences, and India's trajectory.

### 🔎 What the project explores

> 🌎 **Global patterns** → 📈 **Time trends** → 🔗 **Relationships** → 🏆 **Rankings** → 🇮🇳 **India** → 🧠 **Insights**

---

## 🎯 Objectives

- 🌍 Understand global happiness patterns from **2011 to 2025**
- 🔗 Identify factors with stronger linear associations with life evaluation
- 📈 Analyze yearly global happiness trends
- 🏆 Compare countries using 2025 life evaluation scores
- 🇮🇳 Analyze India's happiness trajectory
- 📊 Compare India's factor values between 2019 and 2025
- 🎨 Communicate results through clear visualizations
- 🧹 Demonstrate a complete real-world data analytics workflow

---

## ❓ Research Questions

### 🌎 Global

1. How has global average life evaluation changed from 2011 to 2025?
2. Which explanatory factors have the strongest association with life evaluation?
3. Which countries ranked highest in 2025?
4. Which countries ranked lowest in 2025?
5. What patterns appear across economic, social, health, freedom, and generosity-related contributions?

### 🇮🇳 India

1. How has India's life evaluation changed over time?
2. How does India compare with the global average?
3. Which factors increased or decreased between 2019 and 2025?
4. What major patterns can be observed in India's data?

---

## 📂 Dataset

### Source

**World Happiness Report 2026 – Data for Figure 2.1 (2011–2025)**

```text
WHR26_Data_Figure_2.1.xlsx
```

| Property | Value |
|---|---:|
| 📦 Records | **2,116** |
| 🧩 Columns | **13** |
| 📅 Period | **2011–2025** |
| 🔁 Duplicate rows | **0** |

### Main Variables

| Variable | Meaning |
|---|---|
| `Year` | Observation year |
| `Rank` | Happiness ranking |
| `Country name` | Country / territory |
| `Life evaluation (3-year average)` | Main life-evaluation measure |
| `Lower whisker` | Lower uncertainty bound |
| `Upper whisker` | Upper uncertainty bound |
| `Explained by: Log GDP per capita` | GDP-related explained contribution |
| `Explained by: Social support` | Social-support contribution |
| `Explained by: Healthy life expectancy` | Health-related contribution |
| `Explained by: Freedom to make life choices` | Freedom-related contribution |
| `Explained by: Generosity` | Generosity contribution |
| `Explained by: Perceptions of corruption` | Corruption-perception contribution |
| `Dystopia + residual` | Remaining contribution / residual |

---

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| 🐍 **Python** | Core programming |
| 🐼 **Pandas** | Data loading, cleaning, grouping and analysis |
| 🔢 **NumPy** | Numerical operations |
| 📊 **Matplotlib** | Charts and trend visualization |
| 🎨 **Seaborn** | Statistical visualization |
| 📓 **Jupyter Notebook** | Reproducible analysis |
| 📗 **Excel** | Source dataset |
| 🐙 **Git** | Version control |
| 🌐 **GitHub** | Project hosting |

---

## 🗂️ Project Structure

```text
Global-Happiness-Analysis/
│
├── data/
│   ├── raw/
│   │   └── WHR26_Data_Figure_2.1.xlsx
│   └── cleaned/
│
├── notebooks/
│   └── global_happiness_analysis.ipynb
│
├── reports/
│   └── project_research.md
│
├── src/
│   ├── data_cleaning.py
│   ├── analysis.py
│   └── visualization.py
│
├── visualizations/
├── assets/
│   └── demo.gif
│
├── README.md
├── requirements.txt
└── .gitignore
```

> The completed analysis is currently contained in the Jupyter Notebook. The `src/`, `visualizations/`, and `assets/` folders provide a scalable structure for future expansion.

---

## 🔄 Analysis Workflow

```text
             📂 RAW DATA
                 │
                 ▼
          🔍 UNDERSTAND DATA
                 │
                 ▼
            🧹 CLEAN DATA
                 │
                 ▼
        🕳️ CHECK MISSING VALUES
                 │
                 ▼
          📊 EXPLORE DATA
                 │
                 ▼
        🔗 CORRELATION ANALYSIS
                 │
                 ▼
          📈 TREND ANALYSIS
                 │
                 ▼
          🏆 COUNTRY RANKING
                 │
                 ▼
           🇮🇳 INDIA ANALYSIS
                 │
                 ▼
          🎨 VISUALIZATIONS
                 │
                 ▼
            🧠 INSIGHTS
                 │
                 ▼
           🏁 CONCLUSION
```

---

## 🧹 Data Preparation

The dataset was inspected using:

- `shape`
- `columns`
- `dtypes`
- `describe()`
- missing-value counts
- duplicate checks
- year-wise missingness

### 🕳️ Missing Data Strategy

The missing-value pattern is systematic. Explanatory factor data is largely unavailable for **2011–2018** and available from **2019 onward**.

Therefore, factor values were **not blindly filled or interpolated**.

Instead:

- Main life-evaluation records were retained for trend analysis.
- Complete factor records were used for global factor analysis.
- India factor comparisons were limited to the available period.

---

## 🔗 Correlation Analysis

Correlation was used to examine **linear association, not causation**.

| Factor | Correlation with Life Evaluation |
|---|---:|
| 🤝 Social support | **0.71** |
| 💰 Log GDP per capita | **0.68** |
| ❤️ Healthy life expectancy | **0.66** |
| 🕊️ Freedom to make life choices | **0.49** |
| 🎁 Generosity | **0.43** |
| 🛡️ Perceptions of corruption | **0.03** |

### 🥇 Strongest Relationships

```text
Social support             ██████████████████  0.71
Log GDP per capita         █████████████████   0.68
Healthy life expectancy   ████████████████    0.66
Freedom                    ████████████        0.49
Generosity                 ██████████          0.43
Corruption perceptions    █                   0.03
```

> **Interpretation:** Social support shows the strongest positive linear relationship with life evaluation in the analyzed global factor data.

---

## 📈 Global Happiness Trends

The yearly global average life evaluation was calculated by grouping observations by year.

### 🌟 Main Observation

The global average life evaluation reached its highest value in the dataset in **2025**, at approximately **5.65**.

The notebook also calculates:

- 📅 Yearly average happiness
- ↕️ Year-over-year absolute change
- 📊 Year-over-year percentage change
- 📈 Annotated trend visualization

---

## 🏆 2025 Country Ranking

### 🥇 Top 10

| Rank | Country | Life Evaluation |
|---:|---|---:|
| 1 | 🇫🇮 Finland | **7.764** |
| 2 | 🇮🇸 Iceland | **7.540** |
| 3 | 🇩🇰 Denmark | **7.539** |
| 4 | 🇨🇷 Costa Rica | **7.439** |
| 5 | 🇸🇪 Sweden | **7.255** |
| 6 | 🇳🇴 Norway | **7.242** |
| 7 | 🇳🇱 Netherlands | **7.223** |
| 8 | 🇮🇱 Israel | **7.187** |
| 9 | 🇱🇺 Luxembourg | **7.063** |
| 10 | 🇨🇭 Switzerland | **7.018** |

### 🔻 Bottom 10

| Country | Life Evaluation |
|---|---:|
| 🇦🇫 Afghanistan | **1.446** |
| 🇸🇱 Sierra Leone | **3.251** |
| 🇲🇼 Malawi | **3.284** |
| 🇿🇼 Zimbabwe | **3.346** |
| 🇧🇼 Botswana | **3.464** |
| 🇾🇪 Yemen | **3.532** |
| 🇱🇧 Lebanon | **3.723** |
| 🇨🇩 DR Congo | **3.761** |
| 🇪🇬 Egypt | **3.862** |
| 🇹🇿 Tanzania | **3.902** |

---

## 🇮🇳 India Analysis

### 📈 India Life Evaluation

| Year | Life Evaluation |
|---:|---:|
| 2011 | 4.98 |
| 2019 | 3.57 |
| 2020 | 3.82 |
| 2021 | 3.78 |
| 2024 | 4.39 |
| 2025 | **4.54** |

India remained below the calculated global average during the analyzed period, while its life evaluation recovered after 2019.

### 🔄 India Factor Changes: 2019 → 2025

| Factor | 2019 | 2025 | Change |
|---|---:|---:|---:|
| 💰 Log GDP per capita | 0.731 | 1.397 | **+0.666** |
| 🕊️ Freedom | 0.581 | 1.015 | **+0.434** |
| 🤝 Social support | 0.644 | 0.732 | **+0.088** |
| ❤️ Healthy life expectancy | 0.541 | 0.298 | **−0.243** |
| 🎁 Generosity | 0.237 | 0.121 | **−0.116** |
| 🛡️ Perceptions of corruption | 0.106 | 0.124 | **+0.018** |

### 🇮🇳 India Story

```text
2011  ───────────────  4.98
                       ↓
2019  ───────────      3.57
                       ↑
2025  ─────────────    4.54
```

---

## 📊 Visualizations

### 🌎 Global Visuals

- 🔥 Correlation heatmap
- 📊 Factor correlation ranking
- 💰 Happiness vs GDP
- 🤝 Happiness vs social support
- ❤️ Happiness vs healthy life expectancy
- 🕊️ Happiness vs freedom
- 🎁 Happiness vs generosity
- 🛡️ Happiness vs perceptions of corruption
- 📈 Global happiness trend
- ↕️ Year-over-year change
- 🏆 2025 country ranking

### 🇮🇳 India Visuals

- 📈 India happiness trend
- ⚖️ India vs global average
- 🔄 India factor changes: 2019 vs 2025

Suggested exported charts:

```text
visualizations/
├── correlation_heatmap.png
├── global_happiness_trend.png
├── 2025_country_ranking.png
├── india_vs_global.png
└── india_factor_changes.png
```

---

## 🖼️ Visualization Gallery

Once the chart PNG files are added to `visualizations/`, they can be displayed here:

```markdown
![Correlation Heatmap](visualizations/correlation_heatmap.png)
![Global Happiness Trend](visualizations/global_happiness_trend.png)
![2025 Country Ranking](visualizations/2025_country_ranking.png)
![India vs Global](visualizations/india_vs_global.png)
![India Factor Changes](visualizations/india_factor_changes.png)
```

---

## 🧠 Key Findings

### 🌎 Global

1. 🤝 **Social support** had the strongest positive correlation with life evaluation (**0.71**).
2. 💰 **Log GDP per capita** showed a strong positive correlation (**0.68**).
3. ❤️ **Healthy life expectancy** also showed a strong positive correlation (**0.66**).
4. 🕊️ Freedom and 🎁 generosity showed moderate positive relationships.
5. 🛡️ Perceptions of corruption showed a very weak linear relationship.
6. 📈 Global average life evaluation was highest in the dataset in **2025**.
7. 🥇 **Finland** ranked first in 2025 at approximately **7.76**.
8. 🔻 **Afghanistan** ranked lowest in 2025 at approximately **1.45**.

### 🇮🇳 India

1. India's life evaluation declined from approximately **4.98 in 2011** to **3.57 in 2019**.
2. India recovered after 2019.
3. India's life evaluation reached approximately **4.54 in 2025**.
4. India remained below the calculated global average.
5. GDP- and freedom-related explained contributions increased strongly from 2019 to 2025.
6. Healthy life expectancy and generosity decreased during the same period.

---

## ⚠️ Important Interpretation

> **Correlation does not imply causation.**

The explanatory variables are **explained contributions** within the World Happiness Report framework. They should not automatically be interpreted as raw measurements or proof that a factor directly causes happiness.

### 🇮🇳 India Caution

India has only **7 years of available factor data (2019–2025)**. Therefore, India factor correlations can be unstable. The project emphasizes the more interpretable **2019 vs 2025 comparison** instead.

---

## ⚠️ Limitations

- Factor-level data is unavailable for all years.
- Missing values are systematic.
- Correlation does not establish causation.
- Country comparisons are affected by methodology and data availability.
- India factor analysis has only seven complete annual observations.
- Pearson correlation captures linear relationships and may miss nonlinear patterns.
- The dataset does not include every possible determinant of well-being.

---

## 🚀 Future Scope

| Upgrade | Goal |
|---|---|
| 📊 Streamlit dashboard | Interactive exploration |
| 🌍 World map | Geographic comparison |
| 🔎 Country filters | Personalized analysis |
| 🇮🇳 Neighbor comparison | India vs nearby countries |
| 📈 Regression | Deeper statistical modeling |
| 🤖 ML prediction | Predict life evaluation |
| 🧠 Feature importance | Understand model drivers |
| 🔬 Nonlinear analysis | Discover complex patterns |
| 🧩 Clustering | Group similar countries |
| 📅 Automated updates | New report versions |
| ☁️ Deployment | Public online dashboard |

---

## ▶️ Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/PalAnghan/Global-Happiness-Analysis.git
cd Global-Happiness-Analysis
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Start Jupyter

```bash
jupyter notebook
```

### 4️⃣ Open the notebook

```text
notebooks/global_happiness_analysis.ipynb
```

### 5️⃣ Run all cells

Use **Run → Run All Cells**.

---

## 📚 Documentation

Detailed research and methodology are available in:

```text
reports/project_research.md
```

---

## 🎓 End-to-End Analytics Workflow

<div align="center">

**📥 Collect** → **🧹 Clean** → **🔍 Explore** → **🔗 Analyze** → **📊 Visualize** → **🧠 Interpret** → **📢 Communicate**

</div>

---

## 📌 Project Status

| Component | Status |
|---|---|
| 📦 Dataset collection | ✅ Complete |
| 🔍 Data inspection | ✅ Complete |
| 🧹 Data cleaning | ✅ Complete |
| 🕳️ Missing-value analysis | ✅ Complete |
| 📊 Descriptive statistics | ✅ Complete |
| 🔗 Correlation analysis | ✅ Complete |
| 📈 Global trend analysis | ✅ Complete |
| 🏆 Country ranking | ✅ Complete |
| 🇮🇳 India analysis | ✅ Complete |
| 🎨 Visualizations | ✅ Complete |
| 📝 Research report | ✅ Complete |
| 🌐 GitHub repository | ✅ Published |
| 🎬 Demo video | ✅ Ready |
| 🔗 Demo link | 🔗 Add your Drive link above |
| 🤖 Interactive dashboard | 🔮 Future enhancement |

---

## 💡 Why I Chose This Project

I chose **Global Happiness Analysis** because happiness is a real-world topic connecting data, economics, society, health, freedom, and human well-being.

Instead of only presenting rankings, I wanted to explore the patterns behind those rankings and apply a complete analytics workflow:

> **Collect → Clean → Explore → Analyze → Visualize → Interpret → Communicate**

This project also gave me practical experience working with a real-world dataset and communicating analytical results through visual storytelling.

---

## 🏁 Conclusion

The **Global Happiness Analysis** project demonstrates how data analytics can transform a large international dataset into understandable insights.

The analysis shows strong positive relationships between life evaluation and social support, economic conditions, and healthy life expectancy in the available global factor data.

For India, the analysis shows a recovery in life evaluation after 2019 alongside increases in GDP- and freedom-related explained contributions, while healthy life expectancy and generosity decreased between 2019 and 2025.

Overall, the project demonstrates that meaningful data analysis requires **careful preparation, appropriate interpretation, strong visualization, and clear communication of limitations**.

---

## 👨‍💻 Author

<div align="center">

# Anghan Pal

**BCA Graduate • Data Analytics • AI/ML • Full Stack Development**

🐍 Python &nbsp;•&nbsp; 📊 Data Analytics &nbsp;•&nbsp; 🤖 AI/ML &nbsp;•&nbsp; 💻 Full Stack &nbsp;•&nbsp; ⚙️ Automation

[![GitHub](https://img.shields.io/badge/GitHub-PalAnghan-181717?style=for-the-badge&logo=github)](https://github.com/PalAnghan)

**LinkedIn:** Add your profile link here

</div>

---

## ⭐ Support the Project

If you find this project useful or interesting:

⭐ **Star** the repository &nbsp; • &nbsp; 🍴 **Fork** it &nbsp; • &nbsp; 💬 **Share feedback** &nbsp; • &nbsp; 🔗 **Connect**

---

<div align="center">

## 🌍 Data tells a story.
### This project explores the story behind happiness.

**Built with Python 🐍 | Data 📊 | Curiosity 🔎**

</div>
