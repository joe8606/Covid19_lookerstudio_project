# 🦠 COVID-19 Vaccination Data Analysis & Dashboard

## 📌 Project Overview
This project analyzes COVID-19 vaccination data using **Jupyter Notebook (Google Colab)** for data processing and visualization. The final results are displayed using **Google Looker Studio** to create an interactive dashboard. The dataset includes vaccination trends across different age groups, states, and overall vaccination rates in the U.S.

🔗 **Live Dashboard**: [COVID-19 Looker Studio Report](https://lookerstudio.google.com/reporting/fa7dfe82-9962-4792-85dc-8224df83c175)

🔗 **GitHub Pages Preview**: [Project Page](https://joe8606.github.io/Covid19_lookerstudio_project/)

---

## 📂 Project Structure
```
Covid19_LookerStudio_Project/
│── data/               # Dataset files
│   ├── raw/            # Raw data before processing
│   ├── processed/      # Cleaned and transformed data
│   ├── covid19_cases.csv
│
│── notebooks/          # Jupyter Notebooks for analysis
│   ├── covid19_analysis.ipynb
│   ├── data_cleaning.ipynb
│
│── reports/            # Looker Studio resources
│   ├── screenshots/    # Dashboard screenshots
│   ├── dashboard_link.txt  # Looker Studio shareable link
│
│── README.md           # Project documentation
│── requirements.txt    # Required Python packages
│── .gitignore          # Ignored files
```

---

## 📊 Key Analysis & Findings
### 1️⃣ **Cumulative Vaccination Trends**
- Shows total vaccinations over time, categorized by age groups.
- The dashboard allows filtering by **state** and **vaccine stage**.

![Vaccination Trends](reports/screenshots/vaccination_trends.png)

### 2️⃣ **Funnel Chart for Vaccination Status**
- Displays vaccination progress, from the first dose to booster doses.
- Helps visualize the drop-off rates between each stage.

![Vaccination Funnel](reports/screenshots/vaccination_funnel.png)

### 3️⃣ **Vaccination Rate by State & Heatmap**
- A **treemap visualization** shows vaccination rates by state.
- A **global heatmap** highlights vaccine distribution intensity.

![Statewise Vaccination](reports/screenshots/statewise_vaccination.png)

---

## ⚙️ How to Run the Notebook
### **1️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **2️⃣ Open & Run Jupyter Notebook**
```bash
jupyter notebook
```

Alternatively, you can open the notebook in **Google Colab**:
- [covid19_analysis.ipynb](https://colab.research.google.com/github/joe8606/Covid19_lookerstudio_project/blob/main/notebooks/covid19_analysis.ipynb)

---

## 📌 Tools & Technologies Used
- **Python**: pandas, matplotlib, seaborn
- **Jupyter Notebook (Google Colab)**: Data processing & visualization
- **Google Looker Studio**: Dashboard for interactive reports
- **GitHub Pages**: Hosting the project

---

## 💡 Future Improvements
- Include **real-time data updates**.
- Add **predictive modeling** for future vaccination rates.
- Enhance dashboard interactivity with **more filtering options**.

🚀 **Contributions & Suggestions are Welcome!**

