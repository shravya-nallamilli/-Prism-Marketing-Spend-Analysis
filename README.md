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

## Advertising Spend Analysis for 2020 and 2021

The charts below illustrate the **monthly advertising spend trends** for **Google Ads** and **Meta Ads** during the years **2020** and **2021**.

![Ad Spend Analysis](https://github.com/shravya-nallamilli/-Prism-Marketing-Spend-Analysis/blob/15ce2100c8d2ba77e0af7e790abd993728f68f6c/2020%20and%202021%20Chart%20Analysis.png)

### Observations:

1. **2020 Trends**:
   - **Google Ads (Blue Bars)**: Spending shows significant peaks in the middle and towards the end of the year, likely aligned with major campaigns or seasonal promotions.
   - **Meta Ads (Orange Bars)**: Spending remains relatively lower than Google Ads, with steady allocation throughout the year.

2. **2021 Trends**:
   - **Google Ads (Blue Bars)**: The spending pattern stabilises compared to 2020, with occasional spikes reflecting targeted campaigns.
   - **Meta Ads (Orange Bars)**: Demonstrates a gradual increase in spending throughout the year, indicating a strategic focus on Meta Ads.

### Key Insights:
- Google Ads consistently account for the majority of the marketing budget across both years, highlighting its importance as the dominant platform.
- Meta Ads display a growing share of the budget in 2021, suggesting a diversification of marketing strategies.

### Conclusion:
This analysis highlights a dynamic approach to marketing spend, with Google Ads being the main focus, while Meta Ads gain prominence in 2021. These insights provide a basis for optimising future budget allocation and strategy development.

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
