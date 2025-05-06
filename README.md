# 🌪️ FEMA Climate Disaster Analysis

This project explores the frequency and impact of climate-related disasters across the United States using the publicly available FEMA Disaster Declarations dataset. It also demonstrates how to visualize disaster patterns by state and year, and compares them with a social vulnerability index to evaluate regional resilience.

---

## 📊 Project Objectives

- Identify which U.S. states are most frequently affected by hurricanes, wildfires, droughts, and storms
- Visualize the distribution of disaster types by state using heatmaps
- Analyze trends over time (year-by-year disaster frequency)
- Compare disaster frequency with vulnerability index to assess climate resilience

---

## 🗂️ Data Sources

- **FEMA Disaster Declarations Summary**  
  https://www.fema.gov/api/open/v2/DisasterDeclarationsSummaries.csv  
  (includes type of disaster, state, date, and more)

- **CDC Social Vulnerability Index **  
  https://www.atsdr.cdc.gov/placeandhealth/svi/index.html

---

## 🐍 Tools Used

- **Python 3**
- Libraries: `pandas`, `matplotlib`, `seaborn`
- Tableau Public for advanced dashboard

---

## 🚀 How to Use

1. Clone the repository
2. Run the Jupyter Notebook: `FEMA_Climate_Disaster_Analysis.ipynb`
3. All charts will be generated automatically:
   - Top disaster types in the US
   - Heatmap: disaster types per state
   - Time-series plot: disasters per year
   - Vulnerability vs disaster frequency (scatter)

---

## 🖼️ Sample Visuals

### 📌 Top 20 Disaster Types in the U.S.
![Disaster Types Bar Chart](images/top_disaster_types.png)

### 🗺️ Heatmap: Disaster Frequency by State & Type
![Heatmap](images/disaster_heatmap.png)

### 📈 Trend: Disasters Per Year
![Disaster Trend](images/yearly_trend.png)

### 🔍 Scatter: Disaster Frequency vs Vulnerability Index
![Scatter Plot](images/vulnerability_scatter.png)

---

## 📄 Output Files

- `fema_cleaned_data.csv`: cleaned dataset
- `fema_disaster_state_totals.csv`: total number of disasters per state
- `fema_disaster_heatmap_data.csv`: pivot table for heatmap

---
## 📃 License

This project is licensed under the MIT License.

---

## 🤝 Contributions

Pull requests and forks are welcome!  
Let’s build smarter, more resilient communities together 🌎


