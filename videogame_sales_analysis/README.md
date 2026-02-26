#  Video Game Sales Analysis Dashboard

##  Project Overview

This Power BI dashboard analyzes global video game sales performance across genres, platforms, publishers, regions, and time using the VGChartz 2024 dataset (64,000+ records).

The goal of this project is to uncover key market trends, identify high-performing segments, and evaluate competitive publisher performance using data modeling and DAX-driven insights.

---

##  Business Objective

- Identify top-performing genres and platforms  
- Understand regional market distribution  
- Evaluate publisher competitiveness  
- Analyze historical industry growth trends  
- Compare critic scores with commercial success  

---

##  Dataset Information

- **Source:** VGChartz 2024 Dataset  
- **Total Records:** ~64,000 games  
- **Time Range:** Multiple release years  
- **Sales Unit:** Million copies sold (not revenue)

### Key Columns:
- Title  
- Console (Platform)  
- Genre  
- Publisher  
- Release Date  
- NA, JP, PAL, Other Sales  
- Total Sales (Million Units)  
- Critic Score (partial availability)

---

##  Data Preparation

- Removed rows with missing `total_sales`
- Extracted Year from release date
- Filtered blank critic scores for rating analysis
- Created DAX measures for:
  - Total Global Sales
  - Total Publishers
  - Regional Sales Breakdown
- Applied Top N filtering for ranking visuals

---

##  Key Dashboard Insights

###  Industry Growth
- Peak gaming industry performance observed between 2007–2011.
- Decline observed post-2012, possibly due to mobile market expansion.

###  Genre Performance
- Action and Sports genres dominate global unit sales.

###  Platform Dominance
- PlayStation 2, Nintendo DS, and Wii rank among top-performing consoles.

###  Regional Distribution
- North America contributes the largest share of total global sales.

---

## Tools & Technologies

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query  
- Data Modeling  
- Interactive Filtering & Slicers  

---

## Key Features

- KPI Summary Metrics  
- Sales Trend Over Time  
- Genre & Platform Performance  
- Regional Market Share (Pie Chart)  
- Top 5 Best-Selling Games    
- Highest Critically Rated Game  

---

## Conclusion

This project demonstrates business intelligence workflow including data cleaning, transformation, DAX modeling, and insight-driven dashboard development.

The analysis highlights how structured data visualization can uncover strategic market insights within the global gaming industry.

---

## Author

**Arockia Roshan A**  
 Data Science 
