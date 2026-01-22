# Crop Yield Data Analysis

This project performs an **exploratory data analysis (EDA)** on crop yield data to understand patterns in agricultural production across crops and over time.  
The analysis aims to uncover trends, variability, and differences in yields that can support **agricultural planning, food security analysis, and policy decisions**.

---

## Dataset

- **Content:** Crop yield data by crop type and year
- **Variables include:**
  - Crop type
  - Year
  - Yield (production measure)

---

## Objectives

- Explore crop yield distributions
- Analyze trends in crop yields over time
- Compare yield performance across different crops
- Identify variability and potential risk in agricultural production

---

## Methodology

### 1. Data Inspection
- Dataset structure and summary statistics are examined using:
  - `.head()`
  - `.info()`
  - `.describe()`

---

### 2. Data Cleaning
- Missing values and inconsistencies are identified and handled
- Dataset is prepared for reliable analysis

---

### 3. Exploratory Data Analysis (EDA)

The notebook includes:
- **Yield distribution analysis** to understand central tendency and dispersion
- **Time-series analysis** to identify yield trends over years
- **Comparative analysis across crops** using grouped statistics
- **Visualizations** such as line plots and bar charts for interpretability

---

## Key Insights

The analysis enables:
- Identification of crops with consistently high or low yields
- Understanding of long-term yield trends
- Comparison of yield stability across different crops
- Detection of anomalies or structural changes in agricultural output

---

## Tools & Libraries

- Python 3.9+
- pandas
- numpy
- matplotlib
- seaborn (if used)

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
