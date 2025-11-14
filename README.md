# Altmetrics in Academia: A Python & SQL Data Analysis

This project is a technical analysis of my quantitative research monograph, "Altmetrics in Academia: A quantitative research on Usage and Impact at the University of Dhaka."

The goal of this project was to move beyond the descriptive statistics of my paper and apply a full-stack data science workflow (ETL, Database Querying, Statistical Testing, and Machine Learning) to gain deeper insights.

**This project demonstrates my readiness for graduate-level STEM research in Information Studies.**

![Familiarity vs Understanding Chart](my_grouped_chart.png)
![Student Comments Word Cloud](my_word_cloud.png)

---

## 🚀 Technical Skills Demonstrated

* **Data ETL:** Reading complex `.sav` (SPSS) files using **Python** (`pandas`, `pyreadstat`).
* **Database Management:** Creating a relational database with **SQLite** to house and structure the data.
* **Data Querying:** Writing advanced **SQL** queries (GROUP BY, UNIONs) to aggregate and segment data.
* **Statistical Analysis:** Performing **Chi-Square tests** (`scipy.stats`) to validate the statistical significance of relationships in the data.
* **Data Visualization:** Building a variety of custom charts (bar, pie, grouped, horizontal) using **Python** (`matplotlib`).
* **Machine Learning (NLP):** Generating a **Word Cloud** from qualitative text data to identify key themes in student comments.
* **Machine Learning (Predictive):** Building a **Logistic Regression** model (`scikit-learn`) to predict student familiarity based on their platform usage.

---

## 📈 Key Findings & Analyses

This notebook contains several analyses, including:

1.  **Demographic Breakdown:** A bar chart of respondent `Q1_Academic_Level`.
2.  **Perception Analysis:** A pie chart of `Q13_NecessityAltmetricsEducation`.
3.  **Familiarity vs. Understanding:** A grouped bar chart (`Q4` vs. `Q5`) showing the relationship between familiarity and self-assessed understanding.
4.  **Statistical Proof:** A Chi-Square test confirmed a **statistically significant relationship** (p < 0.05) between a student's academic level and their familiarity with altmetrics.
5.  **Predictive Model:** The Logistic Regression model was able to predict student familiarity with **59.42% accuracy**.

---

## 📂 How to View This Project

* **Full Analysis:** The complete, end-to-end code and all outputs are in the Jupyter Notebook: [`Altmetrics_Research_Data.ipynb`](Altmetrics_Research_Data.ipynb)
* **Raw Data:** The original, anonymized SPSS data file can be found here: [`Collected Data.sav`](Collected%20Data.sav)
