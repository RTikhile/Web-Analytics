# Web-Analytics

📌 **Project Overview**  
This project analyzes conversion rates across different times of the day during January 2021 using the Google Analytics demo dataset. The goal is to understand how conversion rates fluctuate over time to optimize promotional strategies and resource allocation. The analysis leveraged SQL functions, including `WINDOW` and `UNNEST`, to efficiently aggregate and analyze session and purchase data.

🔍 **Business Problem**  
Businesses aim to maximize conversions by optimizing marketing strategies based on user behavior. This project addresses the following key questions:  
- Do conversion rates significantly vary by the time of day?  
- Which time periods (morning, afternoon, evening, night) yield the highest conversion rates?  
- How can these insights inform more effective promotional strategies?

🏗️ **Methodology**  
- **Dataset:** Google Analytics demo data for January 2021.  
- **Data Preparation:**  
  - Utilized the `UNNEST` function to expand nested data fields for accurate analysis.  
  - Employed the `WINDOW` function to calculate rolling aggregates and understand conversion trends over time.  
  - Grouped data by hourly periods (morning, afternoon, evening, night) for targeted analysis.  
- **Statistical Analysis:**  
  - Conducted ANOVA (Analysis of Variance) to test for significant differences in conversion rates across time periods.  
  - Visualized trends using data visualization techniques for clearer insights.

📊 **Key Findings**  
✅ Conversion rates significantly vary by time of day, with evenings showing the highest conversion rates.  
✅ Afternoon periods also performed well, indicating prime engagement windows.  
❌ Early morning periods reflected lower conversion rates, suggesting less effective engagement.  
✅ Insights from the `WINDOW` analysis revealed consistent patterns that can inform better promotional timing.
