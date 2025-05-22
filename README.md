
# 🔌 Electric Vehicle Population EDA (ML Assignment 1)


## 📄 About the Assignment

An exploratory data analysis assignment on Washington State's Electric Vehicle Population dataset. It includes data cleaning, feature engineering, visualizations, and statistical insights to uncover trends in EV adoption and model popularity.


## 📦 Dataset Overview

- **Source**: [Data.gov - Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)  
- **Records**: ~210,000 rows  
- **Features**: 17 columns (e.g., VIN, County, Model Year, EV Type, Electric Range, MSRP).


## 🧹 Data Preprocessing

- ✔️ Checked and handled missing values (drop rows & median imputation).
- ✔️ Encoded categorical features using One-Hot Encoding.
- ✔️ Normalized numerical features (Electric Range & Base MSRP) using Z-score standardization.



## 📊 Exploratory Data Analysis (EDA)

- Descriptive statistics (mean, median, std).
- Spatial distribution of EVs by location (map).
- Popularity of EV models (bar charts).
- Correlation between numeric features (heatmap).
- Temporal trends in EV adoption (line plots).
- Comparative analysis across counties and cities (stacked bar charts).


## 📈 Visualizations

Visuals include:
- Histograms, scatter plots, box plots.
- Geo-mapping of vehicle locations.
- Bar charts comparing model and type popularity.
- Temporal trend line plots by model year.


## 🧠 Tools Used

- `pandas` – data wrangling. 
- `numpy` – numerical operations.  
- `matplotlib` & `seaborn` – plotting and visualizations.  
- `geopandas` – spatial analysis.  


## 🚀 How to Run

1. Clone the repository.  
2. Open `ML_A1.ipynb` in Jupyter or VS Code.  
3. Run all cells to see the preprocessing steps and visualizations.
  

## 👥 Authors
- [**Razan Abdalrahman**](https://github.com/razanodeh01)
- [**Hidaya Mustafa**](https://github.com/HidayaMustafa)

> 🔍 *Exploring electric vehicle adoption through data – insights that drive the future of mobility.*
