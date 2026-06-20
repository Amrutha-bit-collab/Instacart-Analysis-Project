# Instacart Analysis

## Project Overview
This project analyzes the Instacart Online Grocery Basket Analysis dataset to understand customer purchasing behavior, ordering patterns, product popularity, department performance, and reorder trends. The analysis combines data preparation, exploratory data analysis (EDA), and visual storytelling to generate actionable business insights for improving customer experience and operational efficiency.

## Objectives
- Understand customer shopping habits and order frequency.
- Identify peak ordering days and hours.
- Analyze product and department performance.
- Measure reorder behavior across products and departments.
- Explore basket size and category preferences.
- Compare weekday and weekend shopping patterns.
- Generate business recommendations from customer behavior trends.

## Dataset
The dataset originates from the Instacart Online Grocery Basket Analysis Dataset available on Kaggle.

### Files Used
- `orders.csv` – Customer order information.
- `products.csv` – Product catalog.
- `departments.csv` – Department information.
- `category.csv` – Product category mapping.
- `order_products__prior.csv` – Products from prior orders.
- `order_products__train.csv` – Products from training orders.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
- Imported all dataset files.
- Examined dataset structure, dimensions, and data types.

### 2. Data Preprocessing
- Checked and handled missing values.
- Removed duplicate records.
- Standardized column names.
- Merged datasets for analysis.
- Created derived features.
- Corrected data types where necessary.

### 3. Exploratory Data Analysis

#### Order Behavior Analysis
- Distribution of orders by day of week.
- Orders by hour of day.
- Average days between orders.

#### Product & Department Analysis
- Top ordered products.
- Department-wise order volume.
- Reorder ratio by department.

#### Customer & Category Analysis
- Basket size distribution.
- Most frequently ordered categories.
- Add-to-cart position analysis.

#### Shopping Pattern Analysis
- Weekday vs weekend shopping behavior.
- Peak ordering times comparison.

#### Reorder Analysis
- Most reordered products.
- Reorder ratio comparison between train and prior datasets.
- Reorder behavior across cart positions.

## Key Insights
- Customer orders are concentrated during specific hours of the day.
- A small group of products contributes significantly to total orders.
- Certain departments show consistently higher reorder rates.
- Basket sizes vary considerably across customers.
- Weekend and weekday shopping behaviors differ in timing and volume.
- Products added early to the cart tend to have stronger reorder tendencies.

## Business Recommendations
- Schedule promotions during peak shopping hours.
- Personalize recommendations using reorder history.
- Improve inventory planning for high-demand products.
- Target high-loyalty departments with retention campaigns.
- Optimize product placement based on cart-position insights.

## Repository Structure
```text
├── Instacart Analysis.ipynb
├── orders.csv
├── products.csv
├── departments.csv
├── category.csv
├── order_products__prior.csv
├── order_products__train.csv
└── README.md
```

## How to Run
1. Clone the repository.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Place all dataset files in the project directory.
4. Open `Instacart Analysis.ipynb` in Jupyter Notebook.
5. Run the notebook cells sequentially.

## Conclusion
The analysis provides a comprehensive view of customer purchasing behavior on Instacart. By understanding ordering patterns, product demand, and customer loyalty indicators, businesses can make data-driven decisions to improve customer satisfaction, marketing effectiveness, and operational efficiency.
