# Bike Sales Analysis

## Tables of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

  
### Project Overview
This project analyzes a dataset of bike purchases to identify factors influencing sales, including demographics, income, and commute distance. The analysis was conducted using Microsoft Excel

### Data Sources

Sales Data: The primary dataset used for this analysis is the "Excel Project Dataset.xlsx" file, which contains detailed information about each customer's bike purchase. This dataset consists of a thousand unique customers, their purchasing data, and key customer background data. 

### Tools

- Excel - Data Cleaning
- Excel - Data Analysis
- Excel - Creating reports

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks: 
1. Data loading/Inspection
2. Handling Missing data using filters and find and replace functions
3. Removing Duplicates
4. Data Type Conversion/Standardization, e.g converting income data type from text to currency, using "male" and "female" text descriptors
5. Error Correction using conditional formatting and IF statements.

### Exploratory Data Analysis

EDA involved exploring the bike sales data to answer key questions, such as:

- What's the average income of bike buyers vs. non-buyers, regionally? (Income comparison)
- How does the bike purchase rate change with commute distance? (Commute impact)
- Which regions have the highest/lowest bike purchase proportions? (Regional performance)
- Which demographic segments (marital status, education, age) buy bikes most/least? (Customer segments)
- Is there a link between regional income level and bike purchase rate? (Regional wealth vs. sales)

### Data Analysis

This bike sales analysis heavily utilized Microsoft Excel's Pivot Table and Pivot Chart functionality for data exploration and visualization.

* **Descriptive Statistics:** Pivot Tables were used to calculate average income (using the `AVERAGE` aggregation) and count bike purchases across various segments (gender, region, age bracket, and commute distance). Pivot Charts visually represented these summaries (e.g., "Avg Income Per Purchase" - Clustered Column, "Percentage of Bike Purchases by Region" - Stacked Column, "Bike Purchases by Age" - Line).
* **Comparative Analysis:** Pivot Charts facilitated the comparison of average income and purchase counts across different categories within the defined segments.
* **Trend Analysis:** Line Pivot Charts ("Bike Purchases by Age," "Bike Purchases by Distance") illustrated trends in purchase behavior over different age and commute distance ranges, derived from Pivot Table aggregations.
* **Segmentation Analysis:** Slicers connected to the Pivot Tables enabled dynamic filtering of the dashboard, allowing for targeted analysis of specific customer subgroups("Marital Status", "Region", "Education").
* **Derived Column:** An 'Age Bracket' column was created using `IF` functions to categorize customers for age-based analysis in Pivot Tables and Charts.
* **Implied Correlation:** A combination Pivot Chart ("Region Income and Bike Purchase Comparison") visually suggested a potential relationship between regional income levels and bike purchase volume.

Pivot Tables were the primary tool for summarizing and aggregating the data, which were then visualized using various Pivot Chart types to identify key patterns and insights in bike sales.

### Results/Findings
- In the Pacific region, the average income of bike buyers is $64,336, while for non-buyers, it's $62,532. In North America, bike buyers have an average income of $65,182 compared to $60,903 for non-buyers. In Europe, the average income for bike buyers is $42,365, and for non-buyers, it's $39,474.
- **Key Observation:** Across all three regions presented in this chart, the average income of individuals who purchased a bike is higher than the average income of those who did not. The difference in average income between buyers and non-buyers appears most significant in North America.
- The "Bike Purchases by Distance" chart indicates that the highest number of bike purchases occurs among individuals with the shortest commutes (0-1 miles). As the commute distance increases, the number of bike purchases generally decreases, with a notable drop-off after the 1-2 mile range. Interestingly, the number of individuals who don't purchase bikes tends to be higher for longer commute distances (5-10 miles and more than 10 miles).
- **Key Observation:** There's a clear inverse relationship between commute distance and the number of bike purchases. Shorter commutes are associated with a significantly higher number of bike purchases.
- The Pacific region appears to have the highest proportion of bike purchasers relative to non-purchasers among the three regions shown. There are noticeably more "Yes" purchases than "No" purchases. North America appears to have the lowest proportion of bike purchasers. There are considerably more "No" purchases than "Yes" purchases.
- Demographic Segments buying the most/least bikes:
  - Age: Middle-aged individuals represent the largest segment of bike buyers in our data. Old-aged individuals represent the group with the fewest purchases in our data.
  - Marital Status: A comparison of the 'Married' and 'Single' views indicates that single individuals generally exhibit a higher volume of bike purchases in this dataset.
  - Education: Bachelors buy bikes the most amongst the educated customers. Partial High School buys bikes the least amongst the educated customers.
  - Link between regional income and bike purchase rate:
     - The Pacific region supports a positive link: higher buyer income and higher purchase rate. Factors supporting positive such as favourable cyclical climate and developed infrastructure.
     - North America presents an interesting case: highest buyer income but lowest purchase rate, suggesting other factors are limiting overall adoption despite affordability among buyers. Factors potentially limiting overall adoption despite affordability include a car-centric culture, seasonal limitations and urban development.
     - Europe also shows a nuanced relationship: lower buyer income but a moderate purchase rate, indicating that factors beyond just buyer income are likely driving purchases. Factors include a strong cycling culture supporting consistent yet moderate purchases despite lower income, excellent infrastructure and urban density.

### Recommendations 

Based on the analysis, we recommend the following actions: 
- Target High-Income: Focus marketing on higher-income individuals, the most likely buyers.
- Promote Short Commutes: Emphasize bikes for short commutes (0-2 miles), a key purchase driver.
- Leverage Pacific Success: Analyze and replicate successful strategies from the high-performing Pacific region.
- Address North America: Research and target the lower purchase rate in North America despite buyer affluence. Conduct market research, explore partnerships, and analyze sales trends over time.
- Focus on Middle-Aged & Single: Tailor marketing to the largest (Middle-Aged) and high-volume (Single) segments.
- Investigate Education Trends: Further explore the preferences of "Bachelors" (high purchase) and "Partial High School" (low purchase) segments.
- Regional Marketing: Customize marketing based on the distinct purchase behaviors observed in each region.

### Limitations

This analysis provides valuable insights into bike purchase behavior based on the available dataset. However, it's important to acknowledge the following limitations:

* The analysis is based on a dataset of 1,000 unique customers, which might not fully represent the broader market.
* The data likely reflects a specific timeframe, and trends may vary over time.
* The analysis primarily focused on demographics, income, and commute distance and did not include other potential influencing factors.
* The project relied on Microsoft Excel for analysis, which has limitations compared to specialized statistical software for advanced modeling.
* The findings primarily highlight correlations and do not establish causal relationships.
* The accuracy of the data depends on the self-reported information provided by customers.
* The generalizability of the findings might be limited to the specific customer base and geographic regions included in the dataset.
