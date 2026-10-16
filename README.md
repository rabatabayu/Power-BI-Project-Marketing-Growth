# Marketing & Growth Analytics — Python & Power BI

## Project Overview
This project focuses on analyzing marketing performance, customer behavior, and business growth using Python and Microsoft Power BI. The goal is to evaluate marketing channel effectiveness, customer conversion, advertising efficiency, and retention patterns to support data-driven marketing strategies and sustainable business growth.

## Objectives
- Analyze marketing performance across different acquisition channels.
- Evaluate customer engagement and purchasing behavior.
- Measure advertising efficiency using key marketing metrics.
- Identify conversion opportunities throughout the customer journey.
- Analyze customer retention and repeat purchase patterns.
- Provide strategic recommendations to improve marketing effectiveness and business growth.

## Dataset Overview
The dataset contains marketing and customer activity information, including:

| Column | Description |
| --- | --- |
| `user_id` | Unique customer identifier |
| `first_visit_date` | Date of the customer's first visit |
| `channel` | Marketing acquisition channel |
| `source` | Customer acquisition source |
| `device` | Device used by the customer |
| `sessions` | Total recorded sessions |
| `page_views` | Number of page views |
| `bounce` | Customer bounce indicator |
| `add_to_cart` | Add-to-cart activity |
| `purchase` | Customer purchase indicator |
| `revenue` | Revenue generated |
| `ad_cost` | Advertising expenditure |
| `clicks` | Number of advertisement clicks |
| `impressions` | Number of advertisement impressions |
| `repeat_purchase` | Repeat purchase indicator |
| `retention_month` | Customer retention period |

## Tools & Technologies
- **Python** – Data Preparation and Exploratory Data Analysis
- **Pandas & NumPy** – Data Manipulation and Analysis
- **Matplotlib & Seaborn** – Statistical Data Visualization
- **Microsoft Power BI** – Interactive Dashboard Development
- **Power Query** – Data Transformation
- **DAX** – KPI Calculations and Business Metrics

## Project Workflow

### 1. Data Preparation
- Examined dataset structure and data types.
- Identified missing values and duplicate records.
- Reviewed numerical and categorical distributions.
- Evaluated potential outliers.
- Prepared the dataset for further analysis.

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer acquisition patterns.
- Explored revenue and advertising cost distributions.
- Evaluated customer engagement and purchasing behavior.
- Compared marketing performance across acquisition channels.
- Investigated relationships between marketing metrics.

### 3. Marketing Performance Dashboard
Developed interactive Power BI dashboards to monitor marketing effectiveness and business growth.

**Key Performance Indicators:**
- Total Revenue
- Total Advertising Cost
- Click-Through Rate (CTR)
- Cost Per Click (CPC)
- Cost Per Mille (CPM)
- Customer Acquisition Cost Proxy (CAC Proxy)
- Return on Ad Spend (ROAS)
- Revenue per User
- Conversion Rate

### 4. Customer Conversion Analysis
- Analyzed the customer journey from sessions to purchases.
- Developed conversion funnel visualizations.
- Evaluated customer engagement and purchasing activity.
- Identified potential opportunities to improve conversion performance.

### 5. Marketing Channel Effectiveness
- Compared customer acquisition channels.
- Evaluated advertising expenditure against generated revenue.
- Analyzed channel performance using ROAS and conversion metrics.
- Identified opportunities to improve marketing investment efficiency.

### 6. Customer Retention Analysis
- Explored customer retention and repeat purchase indicators.
- Developed cohort-based customer analysis.
- Evaluated customer behavior across retention periods.
- Identified opportunities to strengthen long-term customer relationships.

## Key Findings

| Analysis | Finding |
| --- | --- |
| Paid Ads Users | **251 users** |
| Paid Ads Purchasing Users | **51 users** |
| Paid Ads Conversion Rate | **20.32%** |
| Paid Ads Revenue | **13,177,258** |
| Paid Ads Cost | **10,948,907** |
| Return on Ad Spend (ROAS) | **1.20x** |
| CAC Proxy | **214,684.45** |
| Revenue per User | **52,499.04** |

### Main Insights

1. **Advertising Performance:** Paid Ads generated revenue exceeding recorded advertising expenditure, with a ROAS of 1.20x. However, this does not necessarily indicate profitability because product and operational costs are excluded.

2. **Customer Conversion:** Paid Ads recorded a purchasing-user conversion rate of 20.32%, highlighting opportunities to optimize the customer acquisition and conversion process.

3. **Customer Acquisition Efficiency:** The relatively high CAC Proxy indicates that acquiring purchasing customers requires significant marketing expenditure.

4. **Revenue Efficiency:** Revenue per User is lower than CAC Proxy. However, these metrics use different denominators and should not be directly interpreted as customer-level losses.

5. **Customer Retention:** Retention and repeat purchase indicators provide opportunities to investigate customer loyalty and long-term growth potential.

## Business Recommendations

1. **Optimize Advertising Efficiency:** Improve campaign targeting, audience segmentation, and budget allocation to increase ROAS.

2. **Improve Conversion Rates:** Optimize landing pages, customer engagement, and purchasing experiences to reduce conversion barriers.

3. **Strengthen Marketing Channels:** Prioritize channels demonstrating stronger conversion performance and advertising efficiency.

4. **Improve Customer Retention:** Develop loyalty programs, personalized promotions, and repeat purchase incentives.

5. **Monitor Marketing Performance:** Continuously evaluate CTR, CPC, CPM, CAC Proxy, ROAS, and conversion rates to support marketing investment decisions.

6. **Improve Customer Value:** Focus on increasing purchase frequency and customer value to strengthen long-term marketing sustainability.

## Analysis Limitations
- ROAS measures revenue relative to advertising expenditure and does not account for total business profitability.
- CAC Proxy represents advertising cost per purchasing user rather than verified new customer acquisition cost.
- Retention analysis depends on assumptions regarding the interpretation of `retention_month`.
- Incomplete monthly observations may affect comparisons of marketing performance over time.
- Relationships identified through exploratory analysis do not necessarily imply causation.

## Conclusion
The Marketing & Growth Analytics project provides insights into customer acquisition, advertising performance, conversion behavior, and customer retention.

The analysis reveals that Paid Ads successfully generate conversions and revenue exceeding recorded advertising expenditure. However, a ROAS of 1.20x and relatively high acquisition costs indicate opportunities to improve marketing efficiency.

By integrating Python for exploratory data analysis and Microsoft Power BI for interactive dashboard development, this project demonstrates how marketing data can be transformed into actionable insights to optimize advertising investments, improve customer conversion, and support sustainable business growth.
