# 🚦 Traffic Accident Analysis - India (2023)

A comprehensive Data Science project analyzing road traffic accidents across Indian states and cities using official government data from MoRTH (Ministry of Road Transport & Highways).


## 📊 Project Overview
This project performs end-to-end data analysis including data collection, cleaning, 
exploratory data analysis, visualization, and machine learning — on real India road 
accident data from 2019-2023.

## 🎯 Key Findings
- **Tamil Nadu** leads with 67,213 accidents in 2023
- **Over-speeding** causes 68.4% of all road accidents
- **Two-wheelers** account for 44.8% of all deaths
- **Random Forest** model achieved **87.5% accuracy** in risk classification
- All states showed a COVID-19 dip in 2020, followed by steady increase

## 📁 Datasets Used
| Dataset | Source | Description |
|---|---|---|
| State-wise Accidents 2019-2023 | MoRTH / OpenCity | 5-year state level data |
| Cities Accidents 2023 | MoRTH / OpenCity | 51 major cities |
| Causes & Violations 2023 | MoRTH / OpenCity | Accident causes |
| Road Users Fatalities 2023 | MoRTH / OpenCity | Vehicle type deaths |
| Individual Accident Records | GitHub | Detailed accident records |

## 🛠️ Tools & Technologies
- **Python** — Core programming language
- **Pandas** — Data manipulation
- **Matplotlib & Seaborn** — Static visualizations
- **Plotly** — Interactive charts
- **Scikit-learn** — Machine Learning
- **Streamlit** — Interactive dashboard

## 🤖 ML Models
| Model | Accuracy |
|---|---|
| Logistic Regression | 75.0% |
| Random Forest | 87.5% ⭐ |

## 📈 Dashboard Features
- 🏠 Overview with key metrics
- 📈 5-year state trend analysis
- 🏙️ City-wise analysis with search
- ⚠️ Causes & risk factor analysis
- 🤖 ML risk prediction with feature importance

## 🚀 How to Run
```bash
pip install streamlit pandas plotly scikit-learn seaborn
streamlit run app.py
```

## 👩‍💻 Author
**Anupama Annepu**  
B.Tech CSE @ KL University | Web Dev Intern @ SkillCraft Technology  
[LinkedIn](https://www.linkedin.com/in/anupama-annepu)

## 📚 Data Source
Ministry of Road Transport & Highways (MoRTH) — data.gov.in & OpenCity
