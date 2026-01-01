# Luxury Watch Market Analytics Platform

## Project Overview
This project analyzes a marketplace dataset of 280,000+ luxury watch listings to provide 
market insights for collectors and retailers. Beyond identifying market trends, I built a specialized Data Quality & Inventory Health system to detect unreliable data and identify where the marketplace is losing information. This cleaned dataset serves as the foundation for a Luxury Watch Recommender System.

## Business Problem
- Need for data-driven pricing insights in luxury watch market
- Lack of standardized data quality metrics
- Multiple stakeholder needs (executives vs. detailed analysts)

## Technical Implementation

### Data Engineering
- Cleaned and standardized 500+ watch records
- **Feature engineering:** box/paper availability, case diameter, item condition, watch model imputation from description
- Created brand segmentation and year-based market segments
- SQL database design for efficient querying

### Visualization & Dashboards (Tableau)
1. **Executive Summary Dashboard:** Inventory KPIs for management
2. **Data Features Completeness:** Highlights missing data for crucial features
3. **Inventory Health:** Highlights suspicious listings and variety of model listings

## Key Insights
- Identified that more than 50% of market inventory share is dominated by the Premium Luxury Brands which include brands such as Rolex, Omega, Cartier and similar.
- Data Health Gap: Identified that 60% of technical specifications were missing across high-value brands, preventing users from making informed purchases.
- Discovered that 21% of marketplace volume is driven by Rolex, but only with a 0.4% model uniqueness rate indicating extreme market saturation of specific hero models. 

## Technologies Used
- **Database**: PostgreSQL
- **Analysis**: Python (Pandas, NumPy)
- **Visualization**: Tableau, Matplotlib
- **Version Control**: Git

## Skills Demonstrated
Data Cleaning | Feature Engineering | SQL | Python | Tableau | 
Dashboard Development | Data Quality Management | Business Intelligence
