# Quantium Data Analytics Project

## Overview
This repository contains my analysis for a **Quantium retail analytics case study** focused on the **Chips category** for a supermarket client. The goal of the project was to understand customer purchasing behavior, segment customers, and evaluate the performance of a store layout trial. Insights from this analysis feed into strategic planning for the next half-year.

---

## Project Background
As part of Quantium’s retail analytics team, tasked with delivering data-driven recommendations for the Category Manager for Chips. The project had two main objectives:

1. **Customer Analysis**
   - Examine transaction and customer datasets.
   - Clean the data, remove inconsistencies, and merge customer and transaction data.
   - Analyze purchasing patterns and segment customers.
   - Derive metrics like total sales, drivers of sales, and high-performing customer segments.

2. **Store Trial Evaluation**
   - Evaluate the performance of trial store layouts in stores 77, 86, and 88.
   - Compare trial stores against control stores using metrics such as:
     - Total sales revenue
     - Number of customers
     - Average number of transactions per customer
   - Provide a data-driven recommendation on whether the trial layouts should be rolled out.

---

## Data Sources
The project used the following datasets:

- **Transaction data:** Contains details of chips purchases across stores.
- **Customer data:** Includes demographics and other attributes for customers.
- **QVI_data dataset:** Used to analyze monthly sales performance for trial and control stores.

All data cleaning, preprocessing, and feature derivation were performed in **R**, with Python used for additional exploration and visualization where appropriate.

---

## Project Workflow

### 1. Data Cleaning and Preprocessing
- Checked for missing values and inconsistencies in both transaction and customer datasets.
- Identified and removed outliers to ensure accurate analysis.
- Corrected incorrect data formats.
- Derived additional features such as `pack size` and `brand name` from raw data.
- Merged transaction and customer datasets for unified analysis.

### 2. Exploratory Data Analysis (EDA)
- Analyzed total sales, sales drivers, and store performance.
- Visualized trends using bar charts, histograms, and scatter plots.
- Identified high-value customer segments and purchasing patterns.
- Key insights:
  - **Mainstream Young Singles & Couples** are the primary buyers of chips.
  - Opportunities exist to target **Young and Older Families**.
  - Pack size preferences influence purchasing behavior.

### 3. Customer Segmentation
- Grouped customers based on purchasing behavior.
- Defined metrics for segmentation:
  - Average spend per transaction
  - Total chips purchased
  - Frequency of purchase
- Created segments to inform marketing and promotional strategies.

### 4. Trial Store Analysis
- Selected suitable control stores for comparison.
- Evaluated performance of trial stores 77, 86, and 88 against controls.
- Metrics analyzed:
  - Total sales revenue
  - Number of purchasing customers
  - Average number of transactions per customer
- Findings:
  - Trial store layouts increased overall performance in certain stores.
  - Insights on whether increased sales were driven by more customers or more purchases per customer.

### 5. Reporting and Recommendations
- All visualizations and summary tables were saved for reporting.
- Submitted initial findings for review.
- Recommendations provided for:
  - Targeting specific customer segments.
  - Rollout of successful trial store layouts.
  - Strategic decisions for the Chips category over the next half-year.

---

## Key Learnings
- Developed strong **data cleaning and preprocessing skills**, including handling missing values, outliers, and feature derivation.
- Applied **data analysis techniques** to uncover insights into customer purchasing behavior.
- Learned to **segment customers** based on multiple metrics to inform business strategy.
- Gained experience in **evaluating trial interventions** and drawing actionable recommendations from data.
- Improved **data visualization skills** for effective communication of insights to stakeholders.
- Applied both **R and Python** to solve complex real-world data analytics problems.

---

## Technologies Used
- **R** – Primary tool for data cleaning, analysis, and visualization.
- **Python** – Used for supplementary analysis and visualizations.
- **CSV Files** – Source data format.
- **Git & GitHub** – Version control and project documentation.
- **Excel** – Used minimally for quick checks and exploratory summaries.

---

## File Structure
```

Quantium-Data-Analytics/
│
├── data/                     # Raw and cleaned datasets
├── scripts/                  # R and Python scripts for analysis
├── visualizations/           # Charts and plots generated
├── README.md                 # Project documentation
└── analysis_report.pdf       # Summary of findings and recommendations

````

---

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/KibutuJr/Quantium-Data-Analytics.git
````

2. Navigate to the project folder:

```bash
cd Quantium-Data-Analytics
```

3. Explore the data in `data/` and run the analysis scripts in `scripts/`.

4. Review visualizations in `visualizations/` and the final report in `analysis_report.pdf`.

---

## Conclusion

This project showcases a full **end-to-end data analytics workflow** in a retail setting, from data cleaning and exploratory analysis to customer segmentation and evaluation of trial interventions. Insights derived are actionable and directly support strategic decisions for the Chips category in the client’s stores.

---

## Author

**Fred Kibutu**

* [GitHub](https://github.com/KibutuJr)
* [Portfolio](https://kibutujr.vercel.app)
* [Email](kibutujr@gmail.com)

---

## License

This project is for educational purposes and personal portfolio demonstration.

```

---
