# 🌍 Global Air Quality & CO2 Emissions Analysis

## 📌 Project Overview
This project is part of a **Capstone Data Analytics** initiative, aiming to analyze the relationship between **Air Quality Index (AQI)** and **CO2 emissions** across countries.  
The analysis explores how CO2 emissions may (or may not) correlate with air quality, highlighting top and bottom performers worldwide, and providing data-driven insights to support better environmental decision-making.  

The workflow includes:
- Data cleaning & normalization  
- Dataset merging (Air Quality & CO2 Emissions)  
- Exploratory Data Analysis (EDA) with statistics and visualizations  
- Correlation testing (Pearson & Spearman)  
- Country-level ranking & comparison  
- Insights generation & recommendations  

---

## 📂 Raw Dataset Links
- 🌐 [Air Quality Index (AQI) Dataset]((https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset?select=global+air+pollution+dataset.csv))  
- 🌐 [CO2 Emissions Dataset (World Bank)]((https://www.kaggle.com/datasets/ulrikthygepedersen/co2-emissions-by-country?resource=download))  

> Note: Datasets were merged and processed to align country names and timelines (2017–2019 average values considered).  

---

## 🔍 Insights & Findings

### ✅ Analytical Results
- **Correlation Analysis**  
  - Pearson correlation (CO2 2019 vs AQI): **0.14** → very weak positive relationship  
  - Spearman correlation: **0.19** → weak monotonic trend  
  - Conclusion: High CO2 emissions do **not directly imply** poor AQI at global scale (other pollutants & factors also contribute).  

- **Ranking by CO2 Emissions**  
  - Top emitters: **China, USA, India, Russia, Japan**  
  - Lowest emitters: **Vanuatu, Central African Republic, Palau, Comoros, Guinea-Bissau**  

- **Ranking by AQI (Air Quality)**  
  - Worst AQI: **Bahrain, Mauritania, Pakistan, UAE, Kuwait**  
  - Best AQI: **Palau, Solomon Islands, Maldives, Iceland, Bhutan**  

### 💡 Key Insights
1. Countries with **high CO2 emissions** (China, USA, India) don’t always have the **worst AQI**, suggesting additional factors like particulate matter, geography, or policies.  
2. Small island nations tend to have **low CO2 emissions & good AQI**, benefiting from natural ventilation and low industrialization.  
3. Middle Eastern countries (Bahrain, UAE, Kuwait, Qatar) show **poor AQI despite not being top CO2 emitters**, indicating other sources (dust storms, industrial air pollution, urbanization).  

### 📊 Recommendations
- Policymakers should focus not only on **reducing CO2** but also controlling **other pollutants** (PM2.5, NO2, Ozone).  
- International cooperation is needed to address air quality since **pollution transcends borders**.  
- Countries with high emissions but relatively moderate AQI (e.g., USA, Japan) can serve as **case studies** for implementing effective **emission control technologies**.  

---

### 🤖 AI-Supported Explanation
This project integrates **AI-powered tools** to support the analytical workflow and enhance insights.  

- **IBM Granite (via Replicate API)**  
  Used as the primary AI model for supporting **data analysis interpretation and explanation**, in accordance with the capstone requirements. Granite helped in generating structured insights, validating correlation results, and formulating clear recommendations.  

- **ChatGPT (OpenAI)**  
  Assisted in **drafting documentation, report structuring, and refining explanations** into professional, reader-friendly language.  

- **Google Gemini**  
  Utilized for **cross-checking interpretations and enhancing visualization ideas**, ensuring multiple perspectives from different AI systems were considered.  

By combining these AI supports, the project ensured that the results are not only **statistically accurate** but also **well-interpreted, professionally documented, and decision-oriented**.  


---

## 📌 Author
Capstone Project by **Rahmat Hadinata**  
