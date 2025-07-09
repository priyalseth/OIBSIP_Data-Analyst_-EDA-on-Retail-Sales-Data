# Retail Sales Exploratory Data Analysis (EDA)

This project performs an in-depth Exploratory Data Analysis (EDA) on a retail sales dataset to extract valuable business insights. The analysis covers product category performance, customer demographics, regional sales patterns, and time-based trends to help retailers make informed decisions.

---

## Objective

The main objectives of this project are to:

- Understand sales trends over time
- Identify top-performing product categories and regions
- Analyze customer demographics and purchasing behavior
- Visualize sales patterns to support data-driven strategies

---

##  Tools & Technologies Used

- **Python** – Programming language for analysis
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Google Colab** – Cloud-based Jupyter notebook environment

---

## Steps Performed

### 1. **Import Libraries**
Imported essential libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

### 2. **Load the Dataset**
Loaded the `retail_sales_dataset.csv` file and previewed its structure using `.head()`, `.tail()`, and `.info()`.

### 3. **Data Cleaning**
- Checked for and handled missing values using forward fill
- Removed duplicate rows
- Converted the `Date` column to datetime format for time series analysis

### 4. **Descriptive Statistics**
- Used `.describe()` for numerical analysis
- Applied `.mode()` for categorical insights

### 5. **Time Series Analysis**
- Extracted month from the `Date` column
- Aggregated monthly sales and visualized trends using a line plot

### 6. **Customer and Product Analysis**

#### A. Product Category Analysis
- Analyzed the number of purchases by product category using a bar chart
- Identified most popular product categories for customer demand

#### B. Customer Demographics
- Visualized gender distribution with a pie chart
- Analyzed age distribution with a histogram

#### C. Purchasing Behavior
- Calculated average purchase amount by gender
- Created age groups to analyze average spending by age range

#### D. Product Category vs. Month Heatmap
- Used a heatmap to visualize total monthly sales by product category
- Identified seasonal performance of each category

### 7. **Correlation Analysis**
- Generated a heatmap to visualize correlations between numerical features (e.g., units sold vs. total amount)

### 8. **Insights & Recommendations**
Summarized the major findings and provided strategic recommendations:
- Focus on top-selling categories and months
- Target high-spending demographics (age/gender)
- Adjust inventory based on seasonal demand

---

##  Outcome

- Identified top-performing product categories and high-revenue months
- Discovered customer behavior patterns based on age and gender
- Uncovered seasonal sales trends through visualizations
- Provided actionable recommendations for marketing, stocking, and customer targeting

---

##  Project Structure

Retail_Sales_EDA/
│
├── retail_sales_dataset.csv # Dataset used for EDA
├── Retail_Sales_EDA.ipynb # Google Colab notebook with full analysis
└── README.md # Project summary and documentation


---

##  Author

**Priyal Seth**  
Data Analyst | EDA | Python | Visualization  
[GitHub](https://github.com/priyalseth?tab=repositories) • [LinkedIn](https://www.linkedin.com/in/priyal-seth-2493302a2/)




