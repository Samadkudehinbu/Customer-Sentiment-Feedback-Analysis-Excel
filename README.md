# 💬 Customer Sentiment Feedback Analysis
> An end-to-end Excel analytics project transforming 10,000 customer feedback records into actionable insights on product performance, sentiment distribution, and regional satisfaction trends across the United States.

📝 **Non-technical read:** [Medium Article](https://medium.com/@kudehinbusamad/customer-sentiment-feedback-analysis-ae4afc8334e5)

💼 **Download Excel Dashboard:** [Customer Sentiment Feedback Analysis.xlsx](https://github.com/user-attachments/files/28012594/Customer.Sentiment.Feedback.Analysis.xlsx)

---

## 📖 Project Overview

Customer reviews are more than text — they are signals that can reshape business decisions, improve products, and drive long-term loyalty. This project analyses a dataset of 10,000 customer feedback records from across the United States to uncover what customers truly think, which products and categories are winning or losing, and where businesses should focus to raise satisfaction levels. The entire workflow — from data cleaning through to an interactive multi-page dashboard — was carried out in Microsoft Excel and Power Query.

---

## 🎯 Project Objectives

The analysis set out to answer the following business questions:

1. **Which products and categories receive the highest volume of customer feedback?**
2. **What does overall sentiment look like, and how does it vary by product and region?**
3. **How do product ratings highlight specific opportunities for improvement?**
4. **What regional patterns exist in customer satisfaction across US states?**
5. **Where should businesses focus to enhance customer satisfaction and build loyalty?**

---

## 🗂️ Dataset Overview

| Field | Description |
|---|---|
| `Customer ID` | Unique customer identifier |
| `Location` | US state of the customer |
| `Product Name` | Name of the reviewed product |
| `Product Category` | Beauty, Clothing, Electronics, Home, Sports |
| `Price ($)` | Unit price of the product |
| `Quantity` | Units purchased per order |
| `Order Spend ($)` | Total spend per order |
| `Rating` | Numerical product rating |
| `Sentiment` | Positive, Neutral, or Negative |
| `Feedback Comment` | Raw customer feedback text |
| `Order Date` | Date of the transaction |

- **Total Records:** ~10,000 feedback entries
- **Scope:** Customer feedback across products, categories, and US states
- **Structure:** Single consolidated table

---

## 🧹 Data Preparation

Data cleaning and transformation were carried out using **Excel and Power Query**:

- **Duplicate removal:** Identified and removed duplicate feedback records
- **Name standardisation:** Normalised product names and category labels for consistent grouping
- **Missing value handling:** Addressed blank entries in ratings and location fields
- **Date reformatting:** Converted date fields to a consistent YYYY-MM-DD format
- **Category normalisation:** Harmonised product category values across the dataset

This step ensured the analysis was built on reliable, consistent data suitable for business decision-making.

---

## 📊 Dashboard Preview

The final deliverable is a 4-page interactive Excel dashboard with slicers for dynamic filtering.

> *(Add dashboard screenshots here after uploading images to the repository)*

### Page 1 — Executive Overview
High-level KPIs (customers, orders, revenue, average rating, sentiment breakdown), monthly feedback trend, feedback by product category, sentiment distribution, top 5 states by feedback volume, and daily feedback trend.

### Page 2 — Product Insights
Top 5 products by negative feedbacks, top 5 products by average rating, and feedback breakdown by product and category.

### Page 3 — Customer Insights
Spending behaviour and feedback patterns across US states.

### Page 4 — Insights & Recommendations
Consolidated actionable findings for decision-makers.

---

## 🔍 Key Insights & Findings

### ⭐ Overall Performance
- **2,000 unique customers** across **25 products** and **10,000 orders**
- **Total revenue: $1.27M** | **Average order spend: $636.13**
- **Average product rating: 3.55** — customers are moderately satisfied, but significant room exists to improve
- **60.19% of feedbacks were positive**, with negative feedbacks accounting for 20.45% of all records

### 📦 Product & Category Performance
- **Electronics and Sports** generated the highest feedback volumes, with Sports leading at **1,618 feedbacks**
- **Top-rated products:** Football (3.69), T-Shirt (3.67), Smartwatch (3.64), Yoga Mat (3.63), Smartphone Case (3.63)
- **Highest negative feedback products:** Coffee Maker, Perfume, and Socks — each recording **79 negative feedbacks**
- **Vacuum Cleaner** also featured in the top 5 for negative feedbacks, suggesting product quality or expectation gaps

### 🌍 Regional Performance
- **New York (858), California (738), Texas (681), Illinois (581), and Florida (562)** were the top 5 states by feedback volume
- Regional sentiment varied significantly — strategies cannot be one-size-fits-all across US markets
- New York and Texas exhibit distinct feedback trends that warrant location-specific product and marketing approaches

### 📅 Temporal Trends
- **August** recorded the highest monthly feedback volume at **730**, followed by May (689)
- **Tuesday (1,173)** and **Saturday (1,163)** were the busiest days for feedback activity
- Feedback is broadly distributed across the week, with no single day showing a dramatic drop-off

### 📊 Year-over-Year Comparison
- Orders grew **~98.1% YoY** and quantity sold grew **~98.1% YoY**, suggesting the current year captures roughly double the activity of the prior year period
- Average rating and positive feedback rate remained stable YoY, indicating consistent — but not improving — customer sentiment

---

## 💡 Business Recommendations

| Area | Recommendation |
|---|---|
| **Product Quality** | Investigate root causes behind high negative feedback for Coffee Makers, Perfume, and Socks — whether quality, packaging, or expectation mismatch |
| **Category Investment** | Double down on Electronics and Sports, which drive the highest engagement and have strong rating potential |
| **Regional Strategy** | Develop location-specific marketing and support strategies for New York, Texas, and California given their distinct feedback patterns |
| **Rating Improvement** | A 3.55 average rating is acceptable but not loyalty-building — focus on bridging the gap between "satisfied" and "delighted" customers |
| **Feedback Loops** | Use high negative-feedback products as priority candidates for product improvement cycles and direct customer follow-up |

---

## ⚠️ Limitations

- The dataset is **synthetic** and may not fully reflect the diversity and complexity of real-world customer feedback
- **Ratings alone** cannot capture all dimensions of customer experience, such as delivery delays or post-purchase service issues
- **Feedback text comments** were not subjected to deep natural language processing (NLP) — sentiment was derived from structured fields rather than unstructured text analysis

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data analysis, KPI calculation, and dashboard design |
| **Power Query** | Data cleaning, deduplication, date formatting, and category normalisation |
| **Pivot Tables & Pivot Charts** | Aggregation and dynamic visualisation |

---

## 👤 Author

**Abdulsamad Kudehinbu** — Data Analyst & Business Intelligence Analyst

- 🌐 [Portfolio](https://sites.google.com/view/abdulsamadportfolio/home)
- 💼 [LinkedIn](https://www.linkedin.com/in/abdulsamad-kudehinbu/)
- ✍️ [Medium](https://medium.com/@kudehinbusamad)

---

> *"Customers are generally satisfied — but satisfaction is not the same as loyalty. The businesses that close that gap are the ones that win."*
