# Data-science-capstone-project
# 🚀 IBM Data Science Capstone Project

This repository contains the final project of the **IBM Data Science Professional Certificate**, where a complete data science pipeline is applied to solve a real-world business challenge.

🔗 **GitHub Repository:** [github.com/Kaja-avinash/Data-science-capstone-project](https://github.com/Kaja-avinash/Data-science-capstone-project)  
📅 **Completed On:** May 26, 2025

---

## 📌 Objective

A fictional aerospace company, SpaceY, wants to compete with SpaceX by reusing rocket boosters. The goal is to build a machine learning model that predicts the likelihood of a successful first-stage landing to help reduce launch costs.

---

## 📊 Executive Summary

- Collected and combined data from SpaceX's public API and Wikipedia page.
- Processed data using SQL, Pandas, and visualization tools.
- Created new features and transformed categorical data using one-hot encoding.
- Trained four ML models: Logistic Regression, SVM, Decision Tree, and KNN.
- Achieved ~83.33% accuracy; all models slightly overpredicted successful landings.
- Developed an interactive dashboard and Folium maps for visualization.

---

## 🧱 Project Structure

| File/Notebook | Description |
|---------------|-------------|
| [`Data Collection Api.ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/Data%20Collection%20Api%20.ipynb) | API data collection from SpaceX |
| [`Data Collection with Web Scraping.ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/Data%20Collection%20with%20Web%20Scraping.ipynb) | Scraped launch data from Wikipedia |
| [`Data wrangling .ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/Data%20wrangling%20.ipynb) | Cleaned and merged datasets |
| [`EDA with Visualization.ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/EDA%20with%20Visualization.ipynb) | Visual exploration using Seaborn and Matplotlib |
| [`EDA with SQL.ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/EDA%20with%20SQL.ipynb) | SQL analysis with IBM DB2 |
| [`Interactive Visual Analytics with Folium.ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/Interactive%20Visual%20Analytics%20with%20Folium.ipynb) | Interactive maps showing launch sites and outcomes |
| [`spacex_dash_app.py`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/spacex_dash_app.py) | Dashboard built using Plotly Dash |
| [`Machine Learning Prediction.ipynb`](https://github.com/Kaja-avinash/Data-science-capstone-project/blob/main/Machine%20Learning%20Prediction.ipynb) | ML modeling and evaluation |

---

## 🔍 Methodology

1. **Data Collection:** API requests and web scraping
2. **Data Wrangling:** Cleaned and formatted datasets
3. **Exploratory Data Analysis:** Using SQL and visualization libraries
4. **Visualization:** Interactive maps with Folium and dashboard with Plotly Dash
5. **Modeling:** Classification models tuned using GridSearchCV

---

## 📈 Results

- **Accuracy:** ~83.33% on all four models (LogReg, SVM, Decision Tree, KNN)
- **Key Finding:** Models tend to overpredict successful landings
- **Best Launch Site:** KSC LC-39A had the highest success rate
- **Feature Importance:** Payload mass and orbit type significantly impact outcomes

---

## ✅ Conclusion

- Built an end-to-end predictive ML model for rocket landing success.
- Enabled data-driven decision making for SpaceY’s launch attempts.
- Suggested improvements: gather more data, use ensemble methods, integrate weather features.

---

## 🙏 Acknowledgments

This project was completed as part of the **IBM Data Science Professional Certificate** on Coursera.

**Instructors:**
Rav Ahuja, Alex Aklson, Aije Egwaikhide, Svetlana Levitan, Romeo Kienzler, Polong Lin, Joseph Santarcangelo, Azim Hirjani, Hima Vasudevan, Saishruthi Swaminathan, Saeed Aghabozorgi, Yan Luo

🔗 [IBM Data Science Certificate on Coursera](https://www.coursera.org/professional-certificates/ibm-data-science)

---

## 📜 License

This repository is for educational purposes only.
