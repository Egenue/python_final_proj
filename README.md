
# 📊 COVID-19 Global Data Analysis & Visualization

## 📝 Project Description
This project is a data analysis and visualization notebook that tracks and explores global COVID-19 trends using real-world datasets. It analyzes confirmed cases, deaths, and vaccinations across time and countries, providing visual insights using Python libraries.

---

## 🎯 Objectives
- Import and clean real COVID-19 data from [Our World in Data](https://ourworldindata.org/coronavirus).
- Analyze time trends for cases, deaths, and vaccinations.
- Compare metrics across countries (e.g., Kenya, USA, India).
- Visualize the data using charts and maps.
- Generate key insights and observations using narrative summaries.

---

## 🧰 Tools and Libraries Used
- **pandas** – for data loading and cleaning
- **matplotlib** – for plotting trends
- **seaborn** – for statistical visualizations
- **plotly.express** – for interactive choropleth maps
- *(Optional)* **geopandas** – for geospatial analysis (not required by default)

---

## ▶️ How to Run/View the Project

1. **Requirements**: Install necessary libraries if not already installed:
   ```bash
   pip install pandas matplotlib seaborn plotly
   ```

2. **Run in Jupyter Notebook**:
   - Open `COVID19_Data_Analysis_Notebook.ipynb` in Jupyter.
   - Execute each cell sequentially to load, clean, and visualize the data.
   - The dataset `owid-covid-data.csv` must be in the same directory.

3. **View Outputs**:
   - Interactive visualizations (line charts, bar charts, choropleth maps)
   - Descriptive summaries and insights in markdown cells

---

## 💡 Key Insights & Reflections

- The **USA** shows the highest total cases and a strong vaccination rollout.
- **India** experienced a massive surge during early 2021.
- **Kenya** has fewer reported cases but slower vaccination progress.
- Death rates vary widely by country and are influenced by healthcare capacity and response measures.
- Vaccination efforts directly correlate with a decline in new cases in most regions.
