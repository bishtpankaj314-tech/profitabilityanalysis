# Superstore Profit & Table Analysis

An exploratory data analysis (EDA) project using **Python (Pandas, Matplotlib, Seaborn)** to analyze retail sales, identify profit drains, and uncover regional performance trends using the Superstore dataset.

---

## 📊 Project Overview
This project investigates store-wide sales, profit margins, and discounting strategies to pinpoint underperforming product categories. A deep-dive analysis revealed that **Tables** operate at a significant net loss, prompting a granular breakdown of city-wise performance to isolate profitable markets.

### Key Business Insights:
* **The Problem Product:** *Tables* generated a total net loss of over **-$17,700**, heavily impacted by heavy discounting (30% or higher).
* **Discount Threshold:** Discounts exceeding 30% entirely erase profit margins on furniture items like tables.
* **Geographic Breakdown:** While major hubs like New York City and Philadelphia suffered severe losses on tables, specific cities (such as *Seattle*, *Harrisonburg*, and *Jackson*) maintained positive profit margins.

---

## 🛠️ Built With
* **Language:** Python
* **Libraries:** 
  * `pandas` (Data manipulation & aggregation)
  * `numpy` (Numerical operations)
  * `matplotlib` & `seaborn` (Data visualization)

---

## 📂 Project Structure
```text
├── profitanalysis.ipynb      # Main Jupyter Notebook with complete analysis and code
├── superstore.csv            # Retail dataset used for the analysis
└── README.md                 # Project documentation
```

---

## 🚀 How to Run the Project
1. Clone this repository or download the project files.
2. Ensure you have the required Python libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open Jupyter Notebook / Google Colab and run `profitanalysis.ipynb`. Ensure `superstore.csv` is in the same directory.

---

## 💡 Future Improvements
* Build an interactive dashboard using Power BI or Tableau to filter city-level table profitability dynamically.
* Implement predictive modeling to forecast optimal discount caps to prevent product-level losses.