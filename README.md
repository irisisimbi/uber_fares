## Key Features
- **Data Analysis**:
  - Fare distribution patterns
  - Hourly/daily/monthly ride trends
  - Peak period identification
- **Dashboard Components**:
  - Interactive time-series visualizations
  - Geographic ride distribution (if coordinates available)
  - Dynamic filters for drill-down analysis

## How to Use
1. **Open the Dashboard**:
   - Download `Assignment_Uber.pbix`
   - Open in Power BI Desktop (requires Power BI installed)

2. **Explore the Data**:
   - Use slicers to filter by time periods
   - Hover over visuals for detailed tooltips
   - Click elements for cross-filtering

## Methodology
### Data Preparation
- Python scripts used for:
  - Missing value handling
  - Feature engineering (hour/day/month extraction)
  - Outlier detection

### Power BI Implementation
- DAX measures for:
  - Dynamic fare calculations
  - Peak hour identification
  - Time intelligence metrics

## Key Findings
1. **Peak Demand**: 
   - Busiest hours: 7-9 AM and 5-7 PM
   - Highest fares on Friday evenings (+22% vs average)
2. **Distance Correlation**: 
   - Strong positive relationship with fares (r = 0.78)
3. **Seasonal Trends**: 
   - 15% higher ride volume in December


