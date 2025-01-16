# Prism Marketing Spend Analysis

## Introduction
This project analyses Prism's marketing expenditure across three platforms: Google, Meta, and RTB. The objective was to evaluate how these investments drive clicks and revenue, enabling the company to make data-driven decisions to optimise return on investment (ROI).

## Objectives
- Investigate the correlation between marketing spend and performance metrics (clicks, impressions, revenue).
- Identify the platforms that generate the highest ROI for Prism.
- Provide actionable recommendations for budget reallocation.

## Methodology
### 1. **Data Preparation**:
   - Aggregated data by month, consolidating marketing spend and key metrics (e.g., clicks, impressions, revenue).
   - Cleaned and structured the data for analysis using Excel.
   - Used pivot tables for grouping and summarising data by platform.

### 2. **Analysis**:
   - **Correlation Analysis**: Assessed the strength of relationships between marketing spend on each platform and total revenue.
   - **Regression Analysis**: Utilised Excel’s Data Analysis Toolpak to model the relationship between marketing spend and revenue, producing detailed regression outputs for each platform.

### 3. **Visualisation**:
   - Plotted graphs to visualise trends, correlations, and regression outputs.
   - Highlighted platforms with the highest and lowest impact on revenue.

 ## Visual Analysis of Marketing Spend

![Marketing Spend Analysis](./images/chart_analysis.png)

### Explanation
The chart above illustrates the monthly trends in marketing spending for Google Ads, Meta Ads, and RTBhouse Ads over a two-year period. Key observations include:

- **Google Ad Spend (Blue Line)**: Demonstrates significant fluctuations, with peaks observed around months 11 and 23. This aligns with increased campaign activity during critical periods.
- **Meta Ad Spend (Orange Line)**: Shows a steady upward trend, indicating consistent investment, with slight peaks around months 12 and 23.
- **RTBhouse Ad Spend (Green Line)**: Remains consistently low, suggesting minimal allocation of budget to this channel.

From the analysis, Meta Ads demonstrated the strongest correlation with total revenue, as seen in the statistical analysis, while RTBhouse Ads showed negligible impact. These insights suggest reallocating budget from RTBhouse to Meta could enhance revenue generation.

### 4. **What-If Analysis**:
   - Simulated budget reallocations to project potential changes in revenue based on revised spending strategies.

---

## Results and Insights
### **Correlation Analysis**:
- **Google Ad Spend**:
  - Moderate positive correlation (**0.403**) with revenue.
  - Indicates that while Google ads contribute to revenue, the relationship is weaker compared to Meta.
- **Meta Ad Spend**:
  - Strong positive correlation (**0.731**) with revenue.
  - Suggests that investments in Meta ads have a significant impact on revenue, making it the most effective platform for Prism.
- **RTB Ad Spend**:
  - Negligible or near-zero negative correlation (**-0.005**) with revenue.
  - Indicates that RTB ads do not meaningfully contribute to revenue and may warrant re-evaluation.

### **Regression Analysis**:
- Regression outputs confirmed the trends observed in the correlation analysis:
  - **Meta Ad Spend** demonstrated the strongest relationship with revenue, with a high coefficient and statistical significance.
  - **Google Ad Spend** had a moderate but significant relationship with revenue.
  - **RTB Ad Spend** showed a very weak and non-significant relationship, indicating low ROI for the current investment.

### **What-If Analysis**:
- A hypothetical reallocation of the 2021 budget revealed:
  - **Increasing Meta’s budget by 20%** while reducing Google’s by the same amount could result in a **4% increase in annual revenue**.
  - This suggests that redirecting funds from underperforming platforms (e.g., RTB) to high-performing ones (e.g., Meta) could enhance ROI.

### Key Recommendations:
1. **Increase Meta Ad Spend**:
   - Allocate additional budget to Meta to maximise revenue gains, given its strong positive correlation and regression results.
2. **Maintain Google Ad Spend**:
   - Keep Google in the marketing strategy, as it provides consistent but moderate contributions to revenue.
3. **Re-evaluate RTB Ad Spend**:
   - Reduce or eliminate spending on RTB, as its negligible impact on revenue suggests low effectiveness.

---

## Conclusion
The analysis highlights that Meta is Prism's most effective advertising platform, followed by Google. RTB ads contribute minimally to revenue and offer little return on investment. By reallocating budgets towards platforms with higher ROI (e.g., Meta), Prism can optimise its marketing strategy and improve overall revenue performance.

## Lessons Learned
- Practical application of Excel’s Data Analysis Toolpak for statistical modelling.
- Advanced understanding of correlation and regression techniques in real-world scenarios.
- Enhanced skills in deriving actionable business insights from data and presenting findings clearly.

## How to Recreate
1. Download the dataset from this repository.
2. Use the `Data Analysis Toolpak` in Excel to run correlation and regression analyses.
3. Review the included charts and insights to understand how marketing spend impacts revenue
