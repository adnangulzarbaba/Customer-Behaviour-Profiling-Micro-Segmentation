# Customer Segmentation Using RFM Analysis & Clustering

## 📌 Project Overview

This project analyzes customer purchasing behavior using **RFM (Recency, Frequency, Monetary) Analysis**, **Average Basket Size**, **Average Order Size**, **Product Diversity**, and **K-Means Clustering** to identify distinct customer segments.

The objective is to uncover valuable customer insights that help businesses improve customer retention, optimize marketing campaigns, increase revenue, and personalize customer experiences through data-driven decision-making.

---

## 🎯 Objectives

- Analyze customer purchasing patterns and spending behavior.
- Calculate key customer metrics:
  - Recency (R)
  - Frequency (F)
  - Monetary Value (M)
  - Average Basket Size
  - Average Order Size
  - Product Diversity
- Identify meaningful customer segments using clustering techniques.
- Generate actionable business recommendations for each customer segment.

---

## 📊 Dataset

The dataset consists of transactional sales records containing information such as:

- Customer ID
- Invoice Number
- Product ID
- Product Description
- Quantity Purchased
- Unit Price
- Invoice Date
- Total Revenue

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Methodology

### 1. Data Preprocessing

- Handle missing values and duplicates.
- Convert date fields into datetime format.
- Remove invalid transactions.
- Create customer-level aggregated features.

### 2. Feature Engineering

#### RFM Analysis

**Recency (R)**  
Number of days since the customer's last purchase.

**Frequency (F)**  
Total number of purchases made by the customer.

**Monetary Value (M)**  
Total amount spent by the customer.

#### Average Basket Size

Average number of items purchased per transaction.

```text
Average Basket Size = Total Quantity Purchased / Number of Orders
```

#### Average Order Size

Average monetary value of each transaction.

```text
Average Order Size = Total Revenue / Number of Orders
```

#### Product Diversity

Measures the variety of products purchased by a customer.

```text
Product Diversity = Number of Unique Products Purchased
```

---

### 3. Exploratory Data Analysis (EDA)

- Customer spending distribution
- Purchase frequency analysis
- Revenue contribution analysis
- Correlation analysis
- Outlier detection

---

### 4. Data Scaling

Features are standardized using scaling techniques to ensure equal contribution during clustering.

---

### 5. Customer Segmentation

K-Means Clustering is applied to segment customers based on purchasing behavior.

#### Cluster Optimization

- Elbow Method
- Silhouette Score

---

### 6. Cluster Profiling

Each cluster is analyzed and assigned a business-friendly label based on customer characteristics.

---

## 📌 Features Used for Clustering

- Recency
- Frequency
- Monetary Value
- Average Basket Size
- Average Order Size
- Product Diversity

---

## 📊 Customer Segments

| Segment | Characteristics | Business Strategy |
|----------|----------------|------------------|
| High-Value Customers | High spending and frequent purchases | Loyalty rewards and premium offers |
| Loyal Customers | Consistent purchasing behavior | Personalized recommendations |
| Potential Loyalists | Moderate spending with growth potential | Targeted promotions |
| At-Risk Customers | Previously active but declining activity | Re-engagement campaigns |
| Occasional Buyers | Infrequent purchases | Discount offers and reminders |
| New Customers | Recent first-time buyers | Onboarding and welcome campaigns |

---

## 📈 Visualizations

The project includes:

- RFM Distribution Analysis
- Correlation Heatmap
- Elbow Curve
- Silhouette Score Analysis
- Cluster Distribution Plots
- Customer Segment Profiles

---

## 💡 Business Insights

This analysis helps businesses:

- Identify high-value customers.
- Improve customer retention strategies.
- Detect customers at risk of churn.
- Personalize marketing campaigns.
- Increase average order value.
- Enhance customer lifetime value (CLV).
- Optimize cross-selling and upselling opportunities.

---

## 📂 Project Structure

```text
Customer-Behaviour-Profiling-Micro-Segmentation/
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── images/
│   └── visualizations/
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run the Notebook

Open:

```text
customer_segmentation.ipynb
```

and execute all cells.

---

## 📜 Conclusion

This project demonstrates how transactional customer data can be transformed into actionable business intelligence through **RFM Analysis, Average Basket Size, Average Order Size, Product Diversity, and K-Means Clustering**. The resulting customer segments enable businesses to create targeted marketing strategies, improve customer retention, and drive sustainable revenue growth.
