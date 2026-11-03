# 🛒 Olist Brazilian E-Commerce Data Analysis

### End-to-End Data Analytics Project | Python | Pandas | NumPy | Matplotlib | Seaborn

![Project](https://img.shields.io/badge/Project-E--Commerce%20Analytics-blue)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-yellow)
![Status](https://img.shields.io/badge/Status-Completed%20Analysis-success)

## 📌 Project Overview

This project focuses on analyzing the Brazilian E-Commerce Public Dataset by Olist to uncover meaningful business insights related to customer behavior, sales performance, product categories, seller performance, payment patterns, delivery operations, and customer satisfaction.

The objective is to transform raw e-commerce data into actionable insights that can help businesses understand their performance, identify operational challenges, and make data-driven decisions.

The project follows an end-to-end data analytics workflow using Python, covering data understanding, data quality assessment, exploratory data analysis (EDA), KPI development, visualization, and business recommendations.

## 🎯 Business Objectives

- Analyze customer purchasing behavior and repeat purchase patterns.
- Evaluate order volume, order status, and delivery performance.
- Understand revenue distribution across payment methods.
- Identify top-performing product categories and products.
- Analyze seller distribution and geographical performance.
- Measure customer satisfaction through review scores.
- Identify operational inefficiencies and opportunities for improvement.
- Provide actionable recommendations based on data-driven findings.

## 🗂️ Dataset Information

The project uses the **Brazilian E-Commerce Public Dataset by Olist**, which contains information about orders, customers, products, sellers, payments, reviews, and geolocation.

The dataset consists of 9 CSV files:

| Dataset | Records |
|---|---:|
| Customers | 99,441 |
| Geolocation | 1,000,163 |
| Order Items | 112,650 |
| Order Payments | 103,886 |
| Order Reviews | 99,224 |
| Orders | 99,441 |
| Products | 32,951 |
| Sellers | 3,095 |
| Category Translation | 71 |

**Source:** [Brazilian E-Commerce Public Dataset by Olist – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 🛠️ Tools & Technologies

- **Python** – Primary programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis environment

## 🔍 Project Workflow

1. Data Collection and Understanding
2. Data Quality Assessment
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. KPI Calculation
6. Data Visualization
7. Business Insights Generation
8. Actionable Business Recommendations

## 📊 Key Performance Indicators (KPIs)

The following KPIs were calculated and analyzed during the project.

| KPI | Result |
|---|---:|
| Total Customer Records | 99,441 |
| Unique Customers | 96,096 |
| Total Orders | 99,441 |
| Delivered Orders | 96,478 |
| Delivery Rate | 97.02% |
| Late Delivery Rate | 8.11% |
| Average Delivery Time | 12.56 Days |
| Total Order Items | 112,650 |
| Unique Products | 32,951 |
| Unique Sellers | 3,095 |
| Product Revenue | R$13,591,643.70 |
| Freight Revenue | R$2,251,909.54 |
| Average Product Price | R$120.65 |
| Average Freight Value | R$19.99 |
| Average Review Score | 4.09 / 5 |

*Note: KPIs use their respective analysis-level definitions. For example, product revenue is calculated from order item prices, while delivery metrics are based on delivered orders with valid delivery dates.*

## 📈 Analysis & Key Business Insights

### 1. Customer Analysis

- Analyzed 99,441 customer records representing 96,096 unique customer identities.
- Approximately 96.88% of unique customers made only one purchase.
- Only 3.12% of unique customers made repeat purchases.
- São Paulo accounted for approximately 41.98% of customer records.

**Business Insight:** The business has a significant opportunity to improve customer retention and encourage repeat purchases.

**Recommendation:** Introduce personalized offers, loyalty programs, post-purchase engagement, and targeted email campaigns.

### 2. Orders & Delivery Performance

- Total orders: 99,441.
- Delivered orders: 96,478.
- Delivery rate: 97.02%.
- Approximately 8.11% of delivered orders with valid delivery dates were late.
- Average actual delivery time was 12.56 days.
- Late orders experienced an average delay of 9.55 days.

**Business Insight:** Overall delivery performance is strong, but certain regions experience considerably higher delivery delays.

**Recommendation:** Monitor regional logistics performance, optimize delivery routes, improve estimated delivery dates, and proactively communicate delays.

### 3. Payment Analysis

- Credit cards represented the largest payment method by transaction count.
- Credit card payment value: R$12.54 million.
- Boleto payment value: R$2.87 million.
- Credit card accounted for approximately 73.9% of payment records.

**Business Insight:** Credit cards are the dominant payment method, indicating their importance in the customer payment experience.

**Recommendation:** Maintain a smooth card payment experience while improving the usability of alternative payment methods.

### 4. Order Items & Sales Analysis

- Total order items: 112,650.
- Unique orders represented in order items: 98,666.
- Product revenue: R$13.59 million.
- Average product price: R$120.65.
- Average freight value: R$19.99.
- Approximately 90.06% of orders containing order items had a single item.

**Business Insight:** Most orders contain only one item, creating an opportunity to increase average order value.

**Recommendation:** Experiment with product bundles, cross-selling, frequently bought together suggestions, and free-shipping thresholds.

### 5. Product Category Analysis

Top revenue-generating categories:

| Product Category | Revenue |
|---|---:|
| Health & Beauty | R$1,258,681.34 |
| Watches & Gifts | R$1,205,005.68 |
| Bed & Bath Table | R$1,036,988.68 |
| Sports & Leisure | R$988,048.97 |
| Computers & Accessories | R$911,954.32 |

**Business Insight:**
- Health & Beauty generated the highest revenue among product categories.
- Bed & Bath Table recorded the highest unit sales among the top categories.
- Watches & Gifts had the highest average product price among the top 10 categories.

**Recommendation:** Prioritize inventory planning and marketing campaigns based on category-specific revenue, demand, and average selling price.

### 6. Seller Performance Analysis

- Total sellers: 3,095.
- São Paulo accounted for approximately 59.74% of sellers.
- Seller revenue varied significantly across cities.
- Guariba recorded the highest revenue among the analyzed seller cities.

**Business Insight:** Seller activity is geographically concentrated, particularly in São Paulo.

**Recommendation:** Monitor seller concentration, evaluate regional performance, and explore opportunities to strengthen seller coverage in underserved regions.

### 7. Customer Review Analysis

- Average review score: 4.09 out of 5.
- Positive reviews: 77.07%.
- Neutral reviews: 8.24%.
- Negative reviews: 14.69%.
- Median review response time: 40.2 hours.

**Business Insight:** Overall customer satisfaction is positive, but negative reviews still represent a meaningful opportunity for improvement.

**Recommendation:** Investigate recurring customer complaints, improve issue resolution, and prioritize faster responses to customer feedback.

## 💡 Overall Business Recommendations

Based on the analysis, the following actions could help improve business performance:

1. **Customer Retention:** Develop loyalty programs and personalized campaigns to increase repeat purchases.
2. **Delivery Optimization:** Focus on regions with high late-delivery rates and improve logistics monitoring.
3. **Revenue Growth:** Use product bundling and cross-selling to increase average order value.
4. **Category Strategy:** Prioritize high-revenue and high-demand categories.
5. **Seller Optimization:** Improve geographical seller coverage and monitor seller-level performance.
6. **Customer Experience:** Analyze negative reviews and strengthen customer support operations.
7. **Payment Experience:** Continue optimizing the dominant credit card payment channel while supporting alternative methods.

## 📁 Project Structure

```text
Olist-Ecommerce-Data-Analysis/
│
├── Olist_Ecommerce_Data_Analysis.ipynb
│
├── reports/
│   └── Olist_Ecommerce_Professional_Project_Summary.pdf
│
├── visualizations/
│
├── requirements.txt
├── .gitignore
└── README.md
```

*Note: Raw dataset files are downloaded separately from Kaggle and are not included in this repository.*

## ⚙️ How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/NehaKumari990/Olist-Ecommerce-Data-Analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd Olist-Ecommerce-Data-Analysis
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Download the Dataset

Download the Olist Brazilian E-Commerce dataset from Kaggle and extract the CSV files.

### 5. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `Olist_Ecommerce_Data_Analysis.ipynb` and execute the cells in sequence.

*Make sure the dataset file paths in the notebook match your local folder structure.*

## ⚠️ Data Quality & Analysis Considerations

- Missing values were assessed before analysis.
- Duplicate geolocation records were investigated and aggregated by ZIP code prefix.
- Suspicious geographical coordinates were flagged for further validation.
- Missing delivery timestamps were considered when calculating delivery metrics.
- Repeated review IDs were investigated rather than automatically deleted.
- Statistical outliers were identified and retained where deletion was not justified.
- Payment records and orders were treated at their respective granularities to avoid incorrect aggregation.

## 🚀 Key Learnings

Through this project, I strengthened my practical understanding of:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data manipulation using Pandas and NumPy
- KPI calculation and interpretation
- Statistical analysis and outlier detection
- Data visualization
- Business problem-solving
- Translating analytical findings into actionable recommendations

## 👩‍💻 Author

**Neha Kumari**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Data Visualization

GitHub: [NehaKumari990](https://github.com/NehaKumari990)

---

⭐ If you find this project interesting, feel free to explore the notebook and share your feedback!
