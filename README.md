# Banking Transaction Analysis Dashboard

## Overview
This project presents a comprehensive analysis of banking transaction data using Power BI to uncover customer behavior patterns, transaction trends, and operational insights. The dashboard provides stakeholders with actionable intelligence for strategic decision-making in banking operations.

## 📊 Dataset Information
- **Source**: [Bank Transaction Dataset for Fraud Detection](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection)
- **Total Accounts**: 495 unique customer accounts
- **Total Transactions**: 2,512 transactions analyzed
- **Data Period**: Full year analysis (January - December)
- **Geographic Coverage**: Multiple U.S. cities including Fort Worth, Los Angeles, Charlotte, Oklahoma City, Philadelphia, and others

### Key Data Fields
- **Customer Information**: Account ID, Customer Occupation, Age, Location
- **Transaction Details**: Transaction ID, Type (Credit/Debit), Amount, Duration, Channel
- **Banking Channels**: ATM, Branch, Online
- **Device Information**: Device ID for security analysis
- **Financial Metrics**: Account Balance, Transaction Amount, Login Attempts

## 🎯 Project Objectives

### Primary Goals
1. **Customer Behavior Analysis**: Understand transaction patterns across different customer segments
2. **Channel Performance Evaluation**: Assess the effectiveness of different banking channels (ATM, Branch, Online)
3. **Geographic Market Analysis**: Identify high-performing and low-activity regions
4. **Operational Efficiency**: Optimize banking operations based on transaction trends
5. **Risk Assessment**: Monitor high-value transactions and customer security patterns

### Business Questions Addressed
- Which customer segments generate the highest transaction volumes?
- What are the preferred banking channels across different demographics?
- How do transaction patterns vary by geographic location?
- Which time periods show peak banking activity?
- What are the characteristics of high-value customers?

## 📈 Key Performance Indicators (KPIs)

### Financial Metrics
- **Average Transaction Amount**: $297.59
- **Average Account Balance**: $5.11K
- **Total Transaction Volume**: 2,512 transactions
- **Credit vs Debit Ratio**: 22.61% Credit, 77.39% Debit

### Operational Metrics
- **Channel Distribution**: Branch (34.55%), ATM (33.16%), Online (32.29%)
- **Customer Segments**: Student (26.15%), Doctor (25.12%), Engineer (24.88%), Retired (23.85%)
- **Geographic Coverage**: Multiple major U.S. cities
- **Daily Transaction Range**: 7-94 transactions per day

## 🔍 Dashboard Insights & Analysis

### 1. Channel Performance Analysis
- **Visual**: Channel Distribution & Transaction Volume by Channel
- **Branch transactions**: 868 total (highest volume)
- **ATM transactions**: 833 total
- **Online transactions**: 811 total
- **Insight**: Despite similar usage percentages, branch transactions show slightly higher volume, indicating preference for in-person banking for complex transactions

### 2. Customer Segmentation by Occupation
- **Visual**: Customer Occupation Distribution & Transaction Activity
- **Students**: 26.15% of customers, 139 credit transactions, 518 debit transactions
- **Doctors**: 25.12% of customers, 140 credit transactions, 491 debit transactions
- **Engineers**: 24.88% of customers, 139 credit transactions, 486 debit transactions
- **Retired**: 23.85% of customers, 150 credit transactions, 449 debit transactions
- **Insight**: Retired customers show the highest credit transaction ratio, while students have the highest debit activity

### 3. Geographic Performance
- **Visual**: Transaction Volume by Location
- **Top Performing Cities**: Fort Worth, Los Angeles, Charlotte, Oklahoma City, Philadelphia
- **Fort Worth**: Leading with $10.9K in online transactions
- **Oklahoma City**: Strong performance across all channels ($8.8K total)
- **Low-Activity Markets**: Dallas, Washington, El Paso, Portland, Albuquerque
- **Insight**: Geographic concentration suggests opportunities for market expansion in underperforming cities

### 4. High-Value Customer Analysis
- **Visual**: Account Balance Holdings by Profession
- **Doctors**: $5.67M total holdings (highest)
- **Engineers**: $3.43M total holdings
- **Retired**: $2.72M total holdings
- **Students**: $1.03M total holdings (lowest)
- **Insight**: Doctors represent the most valuable customer segment, requiring premium service offerings

### 5. Temporal Transaction Patterns
- **Visual**: Daily & Monthly Transaction Trends
- **Peak Activity**: Days 10-15 show highest transaction volumes (84-94 transactions)
- **Monthly Stability**: Consistent activity (161-226 transactions per month)
- **Seasonal Patterns**: March shows peak activity (226 transactions)
- **Insight**: Mid-month periods require enhanced system capacity and staffing

### 6. Transaction Security Analysis
- **Visual**: Login Attempts vs Transaction Value
- **Security Monitoring**: 1-5 login attempts tracked daily
- **Transaction Values**: Range from $16K to $37K daily
- **High-Value Transactions**: Individual transactions up to $1,607.55
- **Insight**: Strong correlation between login attempts and transaction values indicates healthy security monitoring

### 7. Channel Usage by Demographics
- **Visual**: Transaction Channel Usage by Customer Occupation
- **Professional Patterns**: Each occupation shows relatively balanced channel usage
- **Channel Preferences**: Slight variations suggest targeted channel optimization opportunities
- **Transaction Duration**: Varies by profession and transaction type (80-160 average duration)
- **Insight**: Demographic-based channel optimization could improve customer experience

### 8. Merchant Network Analysis
- **Visual**: Top Customer-Merchant Transaction Network
- **Top Merchants**: M026 ($13.91K), M066 ($11.98K), M005 ($11.13K)
- **Network Relationships**: Complex merchant-customer interaction patterns
- **Transaction Frequency**: Consistent merchant partnerships indicate stable business relationships
- **Insight**: Strong merchant relationships drive transaction volume and customer retention

## 💡 Strategic Recommendations

### Customer Experience Enhancement
1. **Premium Services for Doctors**: Develop exclusive banking products for the highest-value segment
2. **Student Banking Programs**: Create cost-effective solutions for high-activity, low-balance customers
3. **Channel Optimization**: Balance capacity across channels based on usage patterns

### Geographic Expansion
1. **Market Development**: Focus expansion efforts on underperforming cities
2. **Regional Optimization**: Strengthen presence in high-performing markets
3. **Location-Specific Services**: Tailor offerings to regional preferences

### Operational Efficiency
1. **Peak Period Management**: Enhance capacity during mid-month high-activity periods
2. **Security Enhancement**: Maintain robust monitoring for high-value transactions
3. **Merchant Partnerships**: Strengthen relationships with top-performing merchant partners

## 🛠 Technical Implementation

### Tools Used
- **Power BI Desktop**: Dashboard creation and data visualization
- **Data Source**: Kaggle dataset (CSV format)

