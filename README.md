# myntra-gifts-ml

# Myntra Gifts Ltd. Retail Analytics

## 📌 Project Overview
This project analyzes transaction data from Myntra Gifts Ltd. (UK-based e-commerce division) to extract actionable business insights. The dataset contains ~541,909 transactions from December 2009 to December 2011.

**Key Objectives**:
- Identify purchasing trends and seasonality
- Analyze product performance
- Understand customer behavior
- Optimize pricing and inventory strategies

## 📂 Files Included


## 🔍 Key Insights
### 1. Order Patterns
- Median order size: 3 items
- 42% of orders contain just 1 item
- Bulk orders (10+ items) comprise 8% of transactions

### 2. Sales Trends
- Strong December peaks (holiday season)
- Weekly pattern: Highest sales on Thursdays
- Daily peak: 12:00-15:00 GMT

### 3. Product Performance
- Top 3 products account for 15% of total revenue
- 20% of SKUs generate 80% of sales (Pareto principle)

### 4. Customer Segmentation
- Top 5% customers contribute 40% of revenue
- RFM analysis reveals 3 distinct customer tiers

## 🛠️ Technical Implementation
### Libraries Used
```python
pandas==1.3.4        # Data manipulation
numpy==1.21.2        # Numerical operations
matplotlib==3.4.3    # Basic visualization
seaborn==0.11.2      # Advanced visualization
openpyxl==3.0.9      # Excel file handling


ey Visualizations
Visualization	Business Question Addressed
Monthly Sales Heatmap	When should we ramp up inventory?
Price vs. Quantity Scatter	What's the optimal price point?
Country-wise Box Plots	Which markets need localization?
RFM Segment Histograms	How should we tier our customers?

