# 🚗 Indian Automobile Market Analysis Using Python

### Exploratory Data Analysis (EDA) | Python | Pandas | NumPy | Matplotlib | Seaborn | Power BI

## 📌 Project Overview

This project analyzes the Indian automobile market using **Python-based Exploratory Data Analysis (EDA)**. The objective is to understand vehicle pricing patterns, sales performance, brand distribution, vehicle segments, fuel types, and electric vehicle (EV) trends.

The workflow includes data inspection, cleaning, feature extraction, statistical analysis, visualization, and an interactive Power BI dashboard.

## 🎯 Project Objectives

- Analyze vehicle distribution across brands and segments.
- Explore vehicle pricing patterns across categories.
- Understand monthly sales by brand, segment, and fuel type.
- Compare electric vehicles (EVs) with non-electric vehicles.
- Examine relationships between vehicle characteristics and monthly sales.
- Identify meaningful patterns and business insights.
- Present findings through an interactive Power BI dashboard.

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation, cleaning, and aggregation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive analysis and documentation |
| Power BI | Interactive dashboard and reporting |

## 📂 Dataset Description

The dataset contains **15,000 vehicle records** representing vehicle models and variants in the Indian automobile market.

The original dataset contains 11 attributes, including Brand, Model, Launch Year, Segment, Fuel Type, Number of Variants, Ex-Showroom Price, Monthly Sales, EV Status, Battery / Mileage, and Notable Features.

Three derived numerical columns were created during data preparation:

- **Average Price (₹ Lakhs):** Calculated from the lower and upper values of the price range.
- **Mileage (kmpl):** Extracted from the battery/mileage text column.
- **Range (km):** Extracted for vehicles with range information.

The final dataset contains **15,000 rows and 14 columns**.

## 🔍 Project Workflow

### 1. Data Loading and Inspection

- Loaded the dataset using Pandas.
- Inspected records, dimensions, column names, and data types.
- Generated descriptive statistics.
- Examined unique values in categorical columns.
- Checked for missing values and duplicate records.

### 2. Data Cleaning and Transformation

- Checked missing values and duplicate rows.
- Converted price ranges stored as text into a numerical average-price column.
- Extracted mileage and EV range into separate numerical columns.
- Verified the extracted values and inspected the final dataset structure.

### 3. Exploratory Data Analysis (EDA)

- **Brand Distribution:** Compared vehicle records across brands.
- **Vehicle Segment Analysis:** Examined Hatchbacks, SUVs, Sedans, Luxury vehicles, and other segments.
- **Fuel Type Analysis:** Compared Petrol, Diesel, Electric, Petrol/CNG, and Petrol/Diesel categories.
- **EV Analysis:** Compared EV and non-EV representation, pricing, and average monthly sales.
- **Launch Year Analysis:** Examined record distribution across launch years.
- **Price Analysis:** Investigated average vehicle prices and pricing differences across segments.
- **Monthly Sales Analysis:** Compared sales across segments and brands.
- **Variants Analysis:** Examined the relationship between the number of variants and monthly sales.
- **Correlation Analysis:** Investigated relationships between price, sales, launch year, mileage, range, and variants.
- **Brand and Segment Comparison:** Compared average sales and pricing across brand-segment combinations.
- **Fuel Type Comparison:** Analyzed average price and monthly sales across fuel types.

### 4. Data Visualization

Used Matplotlib and Seaborn to create:

- Bar charts
- Histograms
- Line charts
- Scatter plots
- Pie and donut charts
- Heatmaps

These visualizations helped identify distributions, differences between categories, trends, and relationships between numerical variables.

### 5. Power BI Dashboard

The cleaned dataset was exported and used to create an interactive Power BI dashboard.

The dashboard includes:

- KPI cards for vehicle records, brands, average price, average monthly sales, and EV share.
- Average monthly sales by vehicle segment.
- Average price by vehicle segment.
- EV versus non-EV sales comparisons.
- Brand-wise average sales.
- Average monthly sales by fuel type.
- Interactive slicers for Brand, Segment, Fuel Type, EV Status, and Launch Year.

## 📊 Key Business Insights

### 1. Vehicle Segment and Sales

Hatchbacks and Compact SUVs showed strong average monthly sales, while Luxury vehicles recorded substantially lower average monthly sales.

### 2. Vehicle Pricing

Luxury vehicles had the highest average price among the analyzed segments at approximately **₹66.38 lakh**, while Hatchbacks had the lowest at approximately **₹6.12 lakh**.

### 3. Price vs. Monthly Sales

The correlation between average price and monthly sales was approximately **-0.58**, indicating a moderate negative linear relationship in the analyzed dataset.

This suggests that higher-priced vehicles generally tended to have lower monthly sales in this dataset. Correlation does not establish causation.

### 4. EV vs. Non-EV Comparison

| Metric | EVs | Non-EVs |
|---|---:|---:|
| Average Price | ₹18.82 lakh | ₹14.59 lakh |
| Average Monthly Sales | 7,948 units | 8,722 units |

EVs had a higher average price but lower average monthly sales than non-EVs in the analyzed dataset.

### 5. Other Relationships

The analysis found very weak linear relationships between monthly sales and several other variables:

- **Number of Variants vs. Sales:** Correlation ≈ -0.001
- **Launch Year vs. Sales:** Correlation ≈ 0.009
- **Mileage vs. Sales:** Correlation ≈ -0.01
- **Range vs. Sales:** Correlation ≈ 0.04

These results indicate that the variables showed little linear association with monthly sales in this dataset.

### 6. Fuel Type Analysis

Electric vehicles had the highest average price among the analyzed fuel types, while Petrol/Diesel vehicles recorded the highest average monthly sales.

## 💡 Conclusion

This project demonstrates a data analysis workflow covering dataset inspection, cleaning, feature extraction, exploratory analysis, statistical relationships, and visualization using Python.

The findings highlight differences in pricing and sales across vehicle segments and fuel types. Average price showed a moderate negative relationship with monthly sales, while several other examined variables displayed very weak linear relationships.

The Power BI dashboard complements the Python analysis by presenting key metrics and findings in an interactive format.

## 🚀 Future Improvements

- Add more detailed brand- and model-level analysis.
- Enhance the Power BI dashboard with additional drill-down views.
- Incorporate more recent and reliable market data.
- Investigate additional factors that may explain sales performance.
- Explore predictive modeling after validating data quality and suitability.

## 📁 Suggested Repository Structure

```text
indian-automobile-market-analysis/
├── Indian_Automobile_Market_Analysis.ipynb
├── README.md
├── data/
│   └── indian_vehicle_data.csv
└── README.md
```

*This is a suggested structure. Keep only files and folders that actually exist in your repository, and update the notebook filename if necessary.*

## ⚠️ Data Disclaimer

The findings represent patterns observed in the dataset used for this project. They should not automatically be interpreted as official statistics or as a complete representation of the entire Indian automobile market.

## 👨‍💻 Author

**Ganesh Jogi**

Aspiring Data Analyst | Python | SQL | Power BI | Tableau | Excel

- GitHub: [GitHub Profile](https://github.com/iganeshjogi)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/iganeshjogi)

---

⭐ If you find this project useful, feel free to explore the notebook and its analysis.
