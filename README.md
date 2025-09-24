# End-to-End Data Analytics Project: Hospitality Domain 🏨

## Project Overview
This repository contains a complete end-to-end data analytics project focused on the hospitality domain, specifically analyzing revenue insights for AtliQ Grands hotel chain. The project demonstrates the entire workflow of a data analyst role, from business understanding to delivering actionable insights through interactive dashboards.

## Project Objectives
- Provide AtliQ Grands with revenue insights to make data-driven decisions
- Identify key performance indicators (KPIs) and business metrics
- Analyze booking patterns, revenue trends, and occupancy rates
- Create an interactive Power BI dashboard for stakeholder decision-making
- Implement best practices in data modeling and visualization

## Dataset Structure
The project utilizes a star schema data model with the following tables:

### Dimension Tables
- **dim_date.csv** - Date dimension with calendar information
- **dim_hotels.csv** - Hotel master data including properties and locations  
- **dim_rooms.csv** - Room category information

### Fact Tables
- **fact_bookings.csv** - Detailed booking transactions (13+ MB)
- **fact_aggregated_bookings.csv** - Pre-aggregated booking metrics

### Supporting Files
- **meta_data_hospitality.txt** - Data dictionary and field descriptions
- **metrics list.xlsx** - Key performance indicators and calculated measures
- **mock up dashboard_atliq grands.png** - Initial dashboard design mockup
- **Helper Document - hospitality.pdf** - Project requirements and business context

## Dataset Summary
- **Total Files**: 11 files
- **Total Size**: ~16.5 MB
- **Main Components**:
  - 3 Dimension tables (CSV format)
  - 2 Fact tables (CSV format)
  - 1 Power BI dashboard file (.pbix)
  - Supporting documentation and metadata

## 🛠️ Tools & Technologies Used
- **Power BI Desktop** - Primary analytics and visualization tool
- **Power Query** - Data transformation and cleaning
- **DAX (Data Analysis Expressions)** - Calculated measures and KPIs
- **Star Schema Modeling** - Optimized data architecture
- **CSV Files** - Source data format

## 📈 Key Performance Indicators (KPIs)
- **Revenue per Available Room (RevPAR)**
- **Average Daily Rate (ADR)**
- **Occupancy Percentage**
- **Realization Percentage**
- **Daily Sellable Room Nights (DSRN)**
- **Daily Booked Room Nights (DBRN)**
- **Daily Utilized Room Nights (DURN)**

## 🔄 Project Methodology
1. **Business Understanding** - Analyzed client requirements and defined success metrics
2. **Data Exploration** - Examined data quality, structure, and relationships
3. **Data Cleaning & Transformation** - Prepared clean, analysis-ready datasets using Power Query
4. **Data Modeling** - Implemented star schema for optimal performance
5. **Measure Development** - Created DAX calculations for business metrics
6. **Dashboard Creation** - Built interactive visualizations aligned with mockup design
7. **Testing & Validation** - Ensured accuracy through data validation techniques
8. **Stakeholder Review** - Incorporated feedback and refined deliverables

## 💡 Key Insights Delivered
- **Revenue Optimization** - Identified high-performing properties and time periods
- **Booking Pattern Analysis** - Discovered seasonal trends and customer behavior
- **Occupancy Insights** - Analyzed room utilization across different categories
- **Performance Benchmarking** - Compared properties against industry standards
- **Actionable Recommendations** - Provided data-driven strategies for revenue growth

## 📱 Dashboard Features
- **Executive Summary View** - High-level KPIs and trends
- **Property Performance Analysis** - Hotel-wise revenue and occupancy metrics
- **Time-based Analysis** - Trend analysis across different time periods
- **Interactive Filters** - Dynamic filtering by property, room type, and date ranges
- **Mobile-Responsive Design** - Optimized for various device types

## 🎓 Learning Outcomes
This project provided hands-on experience with:
- End-to-end data analytics project lifecycle
- Business consulting and stakeholder management
- Advanced Power BI development techniques
- Data modeling best practices using star schema
- Creating customer-centric, actionable dashboards
- Performance optimization for large datasets
- Real-world hospitality industry metrics and KPIs

