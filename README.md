# 🌍 COVID-19 Data Analysis & Visualization

This project explores the spread, impact, and vaccination progress of COVID-19 across selected countries using real-world data from [Our World in Data](https://ourworldindata.org/coronavirus). It includes data cleaning, exploratory data analysis (EDA), and interactive visualizations.

---


---

## 📌 Key Objectives

1. **Load & explore** the dataset  
2. **Clean** and preprocess the data  
3. Perform **exploratory data analysis (EDA)** on case and death trends  
4. Visualize **vaccination progress**  
5. Create an optional **choropleth map** for geographical visualization  
6. Summarize **key insights**

---

## 🔧 Tools & Technologies

- **Python**
- **Pandas** for data manipulation
- **Matplotlib** & **Seaborn** for data visualization
- **Plotly Express** for interactive maps (optional)
- **Jupyter Notebook** for interactive exploration

---

## 📊 Features & Visualizations

- ✅ Line charts: Total cases, deaths, and vaccinations over time  
- ✅ Bar charts: Top countries by cases  
- ✅ Pie charts: Vaccinated vs. unvaccinated population  
- ✅ Choropleth map: Visualizing case density (optional)  
- ✅ Descriptive statistics and trends

---

## 🌍 Countries Analyzed

- 🇮🇳 India  
- 🇺🇸 USA  
- 🇰🇪 Kenya  

---

## 🧹 Data Cleaning Steps

- Filtered selected countries  
- Converted date column to `datetime` format  
- Removed rows with missing critical values (e.g., date, total_cases)  
- Handled missing numeric values using `interpolate()` or `fillna()`

---

## 📈 Sample Insight

- India had a sharp spike in vaccinations starting mid-2021  
- The USA leads in total vaccinations but also in cumulative cases  
- Kenya had comparatively fewer reported cases but slower vaccine uptake  

---

## 🧪 How to Run

1. Clone the repository or download the ZIP  
2. Open `covid_analysis.ipynb` using **Jupyter Notebook** or **VS Code**  
3. Ensure the file `owid-covid-data.csv` is in the correct path  
4. Run the notebook cells step-by-step  

---

## 📦 Data Source

- [Our World in Data COVID-19 dataset](https://github.com/owid/covid-19-data/tree/master/public/data)

---

## 📝 License

This project is for educational and research purposes only.  
Data credit goes to [Our World in Data](https://ourworldindata.org/).
