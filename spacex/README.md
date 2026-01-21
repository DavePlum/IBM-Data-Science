# SpaceX Falcon 9 First-Stage Landing Outcome Prediction 🚀

This project analyzes historical SpaceX Falcon 9 launch data to identify the factors associated with successful first-stage booster landings and to build a predictive model for Falcon 9 landing outcomes.

The work was completed as part of an IBM Data Science capstone project and brings together data collection, exploratory analysis, visualization, and machine learning into a single end-to-end analytical workflow.

---

## Project Overview

SpaceX’s ability to recover and reuse Falcon 9 first-stage boosters is a major driver of launch cost reduction. Understanding when landings are likely to succeed provides insight into operational strategy and cost competitiveness in space exploration and the commercial launch market.

**Key questions explored:**
- How do launch site, orbit type, payload mass, and booster version affect Falcon 9 landing success?
- Are there observable patterns in successful vs. unsuccessful landings?
- Can landing outcomes be predicted using historical mission data?

---

## Project Workflow

The notebooks in this folder follow a logical data science pipeline:

1. **Data Collection**  
   Collected launch and landing data using SpaceX APIs and web scraping techniques.

2. **Data Wrangling & Feature Engineering**  
   Cleaned raw data and prepared features relevant to landing outcomes.

3. **Exploratory Data Analysis (EDA)**  
   Analyzed landing success rates by launch site, orbit type, payload mass, and booster version using SQL queries and visualizations.

4. **Geospatial Analysis**  
   Visualized launch sites and landing locations using map-based analysis.

5. **Interactive Dashboard**  
   Built a dashboard to explore launch and landing characteristics interactively.

6. **Machine Learning Prediction**  
   Trained and evaluated classification models to predict first-stage landing success.

---

## Repository Contents

Each lab corresponds to a distinct stage of the analytical workflow:

- **Lab1 – Data Collection (API)**
- **Lab2 – Web Scraping**
- **Lab3 – Data Wrangling**
- **Lab4 – Exploratory Data Analysis (EDA) with SQL**
- **Lab5 – EDA & Data Visualization**
- **Lab6 – Launch Site Location Analysis**
- **Lab7 – Interactive Dashboard**
- **Lab8 – Machine Learning Prediction**

The notebooks are intended to be viewed in sequence, as each stage builds on the previous one.

---

## Final Deliverable

- 📄 **Final Project Report (online viewer)**  
  https://drive.google.com/file/d/1NaNzTA7HlqnGFlpnfGjrZyQcPfoE0OWl/view?usp=sharing

A downloadable copy of the report is also available in this repository for reference.

---

## Limitations & Considerations

- **Time coverage:** The analysis is based on publicly available SpaceX launch data from approximately 2010–2020. Including more recent launches would increase the sample size and may change observed patterns and model performance.

- **Sample size:** The dataset used for predictive modeling contains a relatively small number of launches, which can affect model stability, train/test splits, and performance evaluation—particularly for more complex models.

- **Dataset consistency:** Different subsets of SpaceX data were used across analysis stages (e.g., EDA, geospatial mapping, dashboards, and modeling). These datasets were not fully harmonized into a single unified source.

- **Feature selection:** Additional variables available in the SpaceX REST API (such as cost per launch or launch attempt history) were not included and may improve predictive performance if explored.

- **Outcome definition:** Certain landing categories (e.g., “no landing attempt”) were treated as unsuccessful outcomes for modeling purposes. Alternative interpretations could lead to different results.

- **Domain expertise:** The analysis relies solely on publicly available data and statistical methods and does not incorporate expert input from SpaceX or aerospace industry professionals.

---

## Tools & Technologies

- **Python**
- **Data analysis:** pandas, NumPy
- **Data acquisition:** REST APIs, BeautifulSoup (web scraping)
- **Databases & querying:** SQL (SQLite)
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Geospatial analysis:** Folium
- **Dashboarding:** Dash
- **Machine learning:** scikit-learn
- **Development environment:** Jupyter Notebook

Specific libraries vary slightly by notebook and analysis stage.

---

## Future Work & Extensions

Although this project is complete as a project and analysis, the subject remains well suited for further exploration. Potential extensions include:

- Updating the dataset to include more recent SpaceX launches and landing outcomes.
- Expanding feature engineering using additional variables available in the SpaceX REST API.
- Re-evaluating model performance with a larger and more recent sample.
- Harmonizing datasets used across analysis stages into a single, consistent source.
- Incorporating domain expertise from aerospace or space industry professionals.

Researchers or analysts interested in extending this work are welcome to explore these directions.

---

## Author

**Dave Plumstead**  

