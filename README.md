# Pharmaceutical Sales & Behavioral Analytics

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on historical pharmaceutical transaction records. The objective is to extract actionable business intelligence regarding volume drivers, seasonal trends, and consumer purchasing behaviors to optimize supply chain operations and sales strategies.

**Target Role:** Data Analytics Associate (DAA)  
**Domain:** Healthcare / Pharmaceuticals Consulting  

---

## Business Value & Impact
In pharmaceutical consulting, identifying *what* sells is only half the battle; understanding *when* and *how* it sells drives profitability. This analysis provides data-backed recommendations for:
*   **Inventory Optimization:** Preventing stock-outs of core revenue-driving medications.
*   **Logistics Efficiency:** Re-routing delivery schedules based on daily purchasing velocity.
*   **Strategic Cross-Selling:** Identifying correlated drug categories for bundled sales pitches to healthcare providers.

---

## Tech Stack
*   **Language:** Python 3
*   **Data Manipulation:** `pandas`, `numpy`
*   **Data Visualization:** `matplotlib`, `seaborn`
*   **Environment:** Jupyter Notebook

---

## Key Insights & Strategic Recommendations

### 1. Volume Drivers (The Core Asset)
*   **Finding:** Analgesics/Painkillers (`N02BE`) completely dominate the sales volume, outperforming all other categories combined.
*   **Action:** Protect the supply chain for `N02BE`. This is the anchor product; automated, priority re-ordering systems must be in place to prevent any disruption in availability.

### 2. The "Weekend Effect" (Logistics)
*   **Finding:** There is a severe, measurable drop in pharmacy transaction volume during weekends (Saturday & Sunday).
*   **Action:** Optimize warehouse delivery schedules to arrive on Monday mornings to replenish stock. Pharmacies can safely reduce weekend staffing to lower operational overhead without impacting revenue.

### 3. Cross-Selling Opportunities (Correlation)
*   **Finding:** A Pearson correlation analysis revealed a strong positive relationship between Asthma (`R03`) and Allergy (`R06`) medications.
*   **Action:** Sales representatives should pitch these categories as a bundled inventory package to clinics, specifically targeting respiratory health campaigns prior to peak allergy seasons.

---

## Dataset Information
The analysis utilizes a synthesized pharmaceutical sales dataset containing transactional records across 8 distinct ATC (Anatomical Therapeutic Chemical) drug categories. 

*(Note: To maintain data minimalism and focus on strategic insights, only Daily and Monthly aggregations were utilized in this analysis to filter out noise).*

---

## How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/Aditya-scp/Pharma-Sales-Analysis.git](https://github.com/Aditya-scp/Pharma-Sales-Analysis.git)
2. **Install the required libraries:**
   ```bash
   pip install pandas matplotlib seaborn
3. **Launch the analysis:**
Open ZS_Pharma_Analytics_Project.ipynb in Jupyter Notebook to view the code, visualizations, and business commentary.
