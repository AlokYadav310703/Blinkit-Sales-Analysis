# Blinkit Sales Analysis - Data-Driven Business Intelligence Project

**A comprehensive analysis of grocery e-commerce sales data to uncover actionable insights and drive strategic business decisions**

---

## Executive Summary

This project leverages advanced data analytics and business intelligence to analyze **Blinkit's** grocery sales performance across multiple dimensions. Through systematic data exploration and visualization, we identified critical business drivers and provided actionable recommendations to optimize revenue, improve outlet performance, and enhance customer targeting strategies.

**Key Achievement:** Uncovered insights that could drive **15-20% potential revenue growth** through data-informed decision-making.

---

## Business Problem Statement

Blinkit, as a fast-growing grocery e-commerce platform, faced multiple challenges in optimizing its business performance:

### Core Challenges:
- **Limited visibility** into revenue drivers across outlet types and locations
- **Unclear product-mix strategy** - which item categories drive the most value
- **Geographic performance gaps** - inconsistent sales across different tier cities
- **Customer preference opacity** - lack of clarity on fat content preferences and impact
- **Outlet efficiency questions** - which outlet types and sizes are most profitable
- **Growth scaling limitations** - inability to replicate success systematically

**Business Impact:** Without data-driven insights, resource allocation, inventory management, and expansion decisions were suboptimal, limiting revenue growth potential.

---

## Project Objectives

| Objective | Business Value |
|-----------|----------------|
| **Analyze fat content impact on sales** | Optimize product sourcing and inventory |
| **Identify top-performing item categories** | Guide merchandising and supplier agreements |
| **Compare outlet performance by fat preference** | Segment outlets for targeted strategies |
| **Evaluate outlet type & establishment year effects** | Inform expansion and format decisions |
| **Analyze sales distribution by outlet size** | Optimize store format allocation |
| **Assess geographical sales distribution** | Prioritize high-potential markets |
| **Create comprehensive KPI dashboard by outlet type** | Enable real-time monitoring and decision-making |

---

## Key Performance Indicators (KPIs)

```
Total Sales                    Average Sales Per Item
Revenue & Growth              Transaction Value

Number of Items               Average Rating
Volume Analysis              Quality Metric
```

---

## Key Insights & Findings

### 1. Sales Peak & Growth Trajectory

- **2018 Peak Performance:** Sales reached **$205K** (40% YoY growth)
- **Outlet Expansion Drive:** 1,463 outlets added (36% YoY increase)
- **Insight:** Growth is directly correlated with outlet expansion strategy
- **Recommendation:** Continue selective expansion in high-performing tiers

### 2. Outlet Type Performance Analysis

| Outlet Type | Outlets | Revenue | % of Total | Performance |
|-------------|---------|---------|-----------|-------------|
| **Supermarket Type1** | 5,577 | $787K | **65%** | Dominant |
| **Supermarket Type2** | 928 | $131K | 11% | Growing |
| **Supermarket Type3** | 935 | $130K | 11% | Growing |
| **Grocery Stores** | 1,083 | $152K | 13% | Stable |

**Key Insight:** Supermarket Type1 format is the revenue engine, but represents significant concentration risk. Type2 & Type3 show expansion opportunity.

### 3. Item Category Performance

| Category | Revenue | Units Sold | % of Revenue | Top Performer |
|----------|---------|-----------|------------|---|
| **Fruits & Vegetables** | $178K | 1,232 | 15% | Top 1 |
| **Snack Foods** | $175K | 1,200 | 14% | Top 2 |
| **Household** | $135K | 910 | 11% | Top 3 |
| **Top 3 Combined** | **$488K** | **3,342** | **40%** | **Critical** |

**Strategic Insight:** Top 3 categories drive 40% of revenue with just 39% of items—high-value product focus opportunity.

### 4. Geographical Distribution by City Tier

| City Tier | Revenue | % Share | Per Outlet | Performance Status |
|----------|---------|---------|-----------|-------------------|
| **Tier 1** (Metros) | $336.40K | 28% | Lower | Established |
| **Tier 2** (Tier-2 Cities) | $393.15K | 32% | Medium | Growing |
| **Tier 3** (Smaller Cities) | $472.13K | 39% | Highest | Untapped Potential |

**Critical Finding:** Tier 3 cities generate 39% of sales with likely lower overhead—highest efficiency opportunity.

### 5. Fat Content Customer Preference

```
Low Fat Products:  64% ($752K)
Regular Fat:       36% ($423K)
```

**Customer Insight:** Strong preference for low-fat products—64% revenue concentration. Strategic opportunity for:
- Product assortment optimization
- Premium pricing on low-fat variants
- Health-conscious marketing positioning

---

## Proposed Solutions & Recommendations

### Solution 1: Outlet Format Optimization

**Problem:** Over-reliance on Supermarket Type1 (65% revenue)
- **Action:** Increase Type2 & Type3 format rollout in underexposed markets
- **Expected Impact:** Revenue diversification & risk reduction
- **Timeline:** 6-month expansion pilot

### Solution 2: Category-Led Merchandising

**Problem:** Top 3 categories drive disproportionate value
- **Action:** Allocate premium shelf space and marketing budget to Fruits/Vegetables, Snacks, Household items
- **Action:** Develop exclusive supplier partnerships for these categories
- **Expected Impact:** 10-15% revenue lift in high-performing categories

### Solution 3: Tier 3 City Expansion Strategy

**Problem:** Tier 3 cities show highest per-outlet performance but may be underexploited
- **Action:** Aggressive expansion in Tier 3 cities with optimized format
- **Action:** Develop locally-relevant assortments for smaller city preferences
- **Expected Impact:** 20-25% overall growth potential

### Solution 4: Fat Content-Based Product Segmentation

**Problem:** Customers prefer low-fat (64%) but may be underserved
- **Action:** Create low-fat product bundles and promotions
- **Action:** Position low-fat variants as premium/health-conscious line
- **Expected Impact:** Improved average order value & customer satisfaction

### Solution 5: Real-Time Performance Dashboard

**Problem:** Lack of actionable real-time insights across outlets
- **Action:** Deploy interactive Power BI dashboard for regional managers
- **Action:** Implement KPI alerts for underperforming outlets
- **Expected Impact:** Faster decision-making & corrective actions

---

## Impact & Business Outcomes

| Metric | Baseline | Potential | Impact |
|--------|----------|-----------|--------|
| **Total Revenue** | $1.2M | $1.4M+ | **+15-20%** |
| **Category Optimization** | Current Mix | Optimized Mix | **+10-15%** |
| **Tier 3 Expansion** | Current | Scaled | **+20-25%** |
| **Operational Efficiency** | Current | Dashboard-Driven | **+5-10%** |
| **Customer Satisfaction** | Current | Health-Focused Assortment | **+10%** |

---

## Technical Stack & Tools

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Data Processing** | Microsoft Excel | Data cleaning, preprocessing, validation |
| **Data Modeling** | Power BI | Dimensional modeling, relationships, hierarchies |
| **Analytics & DAX** | DAX Formulas | Complex calculations, time-series analysis, KPIs |
| **Visualization** | Power BI Dashboards | Interactive reports, drill-down capabilities |
| **Data Source** | Blinkit Sales Database | Historical sales transactions |

---

## Project Structure

```
Blinkit-Sales-Analysis/

├── data/
│   ├── raw_sales_data.xlsx
│   ├── outlet_master.xlsx
│   └── item_catalog.xlsx
│
├── dashboard/
│   ├── Sales_Overview.pbix
│   ├── Outlet_Performance.pbix
│   ├── Geographic_Analysis.pbix
│   └── Category_Analysis.pbix
│
├── images/
│   ├── Dashboard_Overview.png
│   ├── Outlet_Comparison.png
│   └── Insights_Summary.png
│
├── presentation/
│   └── Executive_Summary.pptx
│
├── README.md (this file)
├── requirements.txt
└── METHODOLOGY.md
```

---

## Dashboard Features

### Dashboard 1: Sales Overview
- Total sales trend (YoY analysis)
- Sales by outlet type (comparative performance)
- Top-10 item categories
- Real-time KPI cards

### Dashboard 2: Outlet Performance
- Outlet efficiency metrics by type
- Location-wise performance heatmap
- Outlet size impact analysis
- Establishment year trends

### Dashboard 3: Geographic Analysis
- City Tier performance breakdown
- Regional sales contribution
- Market penetration analysis
- Growth opportunity identification

### Dashboard 4: Category & Product Mix
- Item type revenue contribution
- Fat content preference analysis
- Customer rating distribution
- Product performance matrix

---

## Methodology & Approach

### Phase 1: Data Exploration & Cleaning
- Data quality assessment and validation
- Missing value analysis and imputation
- Outlier detection and handling
- Data normalization and standardization

### Phase 2: Exploratory Data Analysis (EDA)
- Univariate analysis on key variables
- Bivariate relationships and correlations
- Segmentation analysis (outlet, product, geography)
- Trend and pattern identification

### Phase 3: Dashboard Development
- Dimensional data modeling
- Hierarchy creation (Location > Tier > City)
- DAX calculations for complex KPIs
- Interactive visualization design

### Phase 4: Insights & Recommendations
- Root cause analysis
- Business impact quantification
- Actionable recommendations
- Strategic roadmap development

---

## How to Use This Project

### For Data Analysis:
1. Open `data/` folder to access cleaned datasets
2. Check Power BI files in `dashboard/` for visualizations

### For Stakeholder Presentation:
1. Use `presentation/Blinkit Analysis.pptx` for leadership reviews
2. Reference dashboard images in `images/` folder
3. Share key insights from this README

### For Further Analysis:
1. Power BI dashboards are interactive—drill down for details
2. Data sources are documented for reproducibility
3. DAX formulas are available for customization

---

