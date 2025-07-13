# CODECRAFT_DS_01
# Task 1: Population Distribution Visualization

## 📄 Project Overview

This repository contains code and data to visualize the distribution of a continuous variable (total population) across all countries for the year 2024. The objective is to demonstrate data loading, cleaning, and visualization using Python, Pandas, and Matplotlib.

---

## 🔍 Dataset

The data is sourced from the World Bank Open Data:

* **File:** `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`
* **Description:** Total population figures for each country from 1960 to 2024.
* **Metadata Files:**

  * `Metadata_Indicator_API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`
  * `Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`

> The first 4 rows of the main CSV contain metadata and should be skipped when loading.

---

## 🛠️ Requirements

* Python 3.7+
* `pandas`
* `matplotlib`

Install dependencies with:

```bash
pip install pandas matplotlib
```

---

## 🚀 Usage

1. **Clone the repository**

   ```bash
   ```

git clone [https://github.com/](https://github.com/)<your-username>/population-distribution-2024.git
cd population-distribution-2024

````

2. **Place the dataset**
   - Ensure `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv` is in the root directory.

3. **Run the visualization script**
   ```bash
python visualize_population.py
````

4. **View the histogram**

   * The script will generate and display a histogram of population distribution across all countries for 2024.
   * To save the figure, uncomment the `plt.savefig(...)` line in the script.

---

## 📂 Repository Structure

```
├── API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv  # Population data file
├── visualize_population.py                 # Script to load data and plot
├── README.md                               # This file
```

---

## 📊 Visualization Details

* **Plot Type:** Histogram
* **Variable:** Total population for the year 2024
* **Bins:** 30
* **Library:** Matplotlib

---

## ✨ License & Attribution

Data sourced from the World Bank Open Data: [https://data.worldbank.org/indicator/SP.POP.TOTL](https://data.worldbank.org/indicator/SP.POP.TOTL)

---



