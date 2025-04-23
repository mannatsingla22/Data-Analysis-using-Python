# Blinkit Data Analytics

This project performs comprehensive data analysis on a Blinkit retail sales dataset to extract actionable insights on product performance, outlet characteristics, and overall sales patterns. The goal is to support business decisions through clear visualizations and data-driven reporting.

## Dataset

The dataset includes the following columns:

- **Item Fat Content**: Category of fat content (e.g., Regular, Low Fat)
- **Item Identifier**: Unique product ID
- **Item Type**: Product category (e.g., Fruits and Vegetables, Soft Drinks)
- **Outlet Identifier**: Unique store outlet ID
- **Outlet Establishment Year**: Year the outlet was opened
- **Outlet Location Type**: Tier (Tier 1, Tier 2, Tier 3)
- **Outlet Size**: Classification (Small, Medium, High)
- **Outlet Type**: Format (Supermarket Type1, Grocery Store, etc.)
- **Item Visibility**: Shelf space proportion for the product
- **Item Weight**: Product weight in grams
- **Sales**: Total sales value (numeric)
- **Rating**: Customer rating (constant in this dataset)

## Analysis Workflow

1. **Data Cleaning & Imputation**
   - Identify and fill missing or inconsistent values in key columns.
2. **Data Quality Report**
   - Generate summary statistics and detect outliers or anomalies.
3. **Exploratory Data Analysis (EDA)**
   - Univariate analysis: distributions of numerical features.
   - Categorical analysis: frequency counts and bar charts.
   - Bivariate analysis: correlations and cross-tabulations.
4. **Sales Trends & Patterns**
   - Time-series or year-based analysis of sales by store age.
   - Seasonal or monthly trends if timestamps are available.
5. **Product & Outlet Performance**
   - Top-selling item types and fat-content categories.
   - Outlet comparison by location type, size, and outlet type.
6. **Visualization & Dashboard**
   - Create charts (histograms, box plots, bar charts, heatmaps).
   - Assemble interactive dashboard or static storyboards.
7. **Reporting**
   - Compile insights into a report (PDF, PowerPoint, or HTML).

## Tools & Technologies

- **Programming**: Python 3.x, SQL (for any database queries)
- **Data Processing & Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly (optional)
- **Reporting**: Jupyter Notebook, PowerPoint, or Markdown-to-PDF tools
