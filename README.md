# ACC102_Individual_task
## Firm_Performance_Analysis

## Project Overview

This project investigates the relationship between firm size, leverage, and profitability using financial data from Chinese listed companies obtained from the CSMAR database.

The objective is to understand how firm characteristics influence performance and to provide insights that can support investment decision-making.

---

## Dataset

The dataset is sourced from the CSMAR financial database and includes key financial indicators such as:

* Firm Size (proxied by total assets)
* Net Profit
* Return on Assets (ROA)
* Return on Equity (ROE)
* Leverage
* Profit Margin

To facilitate analysis, firms are grouped into four categories (Low, Medium-Low, Medium-High, High) based on quartiles of firm size. This grouping enables comparison of financial performance across different scales of operation.

---

## Methodology

The analysis is conducted in three main stages:

### 1. Data Cleaning

* Converted variables to numeric format
* Removed missing values
* Ensured consistency across financial indicators

### 2. Data Visualization

Several visualizations are used to explore patterns:

* Bar charts to compare financial indicators across size groups
* Line plots (normalized) to examine trends
* Boxplots to analyze the distribution of firm size
  
### 3. Regression Analysis

An Ordinary Least Squares (OLS) regression model is applied:

ROA = β₀ + β₁(Leverage) + β₂(Profit Margin) + ε

This model evaluates how leverage and operational performance affect firm profitability.

---

## Key Insights

The analysis reveals several important patterns.

First, firm size is strongly associated with performance. Larger firms generate significantly higher net profits and demonstrate improved efficiency, as reflected in higher ROA and ROE.

Second, profit margin increases across size groups, indicating that larger firms benefit from better cost control and operational efficiency.

Third, leverage rises consistently with firm size, suggesting that larger firms rely more heavily on debt financing.

Fourth, regression results show that leverage has a statistically significant negative impact on ROA, indicating that higher financial risk may reduce profitability. In contrast, profit margin has a relatively weak positive effect.

Overall, the findings highlight a trade-off between performance and financial risk, where larger firms achieve stronger results but also take on greater leverage.

---

## Limitations

Several limitations should be considered when interpreting the results.

Although the dataset is large, grouping firms into size categories reduces firm-level detail and may mask variation within groups. In addition, the data exhibits skewness and extreme values, particularly among larger firms, which may influence both visualizations and regression results.

The regression model is relatively simple and does not include other potentially important variables such as industry effects or macroeconomic conditions. Furthermore, the assumptions of the OLS model may not fully hold due to non-normality in the data.

These factors suggest that the results should be interpreted with caution.

---

## Conclusion

This project demonstrates that firm size plays a significant role in shaping profitability and financial structure. Larger firms tend to achieve higher profitability and efficiency, but this is accompanied by increased reliance on leverage.

For investors, the findings emphasize the importance of evaluating both return and risk. While larger firms may offer stronger performance, their higher leverage levels introduce additional financial risk that should be carefully assessed.

---

## Investment Implications

Based on the analysis, several practical insights can be drawn for investors.

First, larger firms tend to deliver stronger profitability, as reflected in higher net profit, ROA, and ROE. This suggests that investing in larger firms may provide more stable and consistent returns.

However, the results also show that leverage increases with firm size, and regression analysis indicates that higher leverage has a negative impact on profitability. This implies that excessive reliance on debt may weaken firm performance and increase financial risk.

Therefore, investors should not focus solely on firm size or profitability indicators. Instead, it is important to evaluate a firm’s capital structure and assess whether its level of leverage is sustainable.

In addition, while profit margin contributes positively to performance, its effect is relatively limited compared to leverage. This suggests that financial risk management plays a more critical role than operational efficiency in determining overall profitability in this context.

Overall, investors are advised to adopt a balanced approach by considering both return and risk. Firms with strong profitability but moderate and well-managed leverage may offer more attractive long-term investment opportunities.

---

## Repository Contents

* `LiuyingChen2470403-checkpoint.ipynb` – Full data analysis and visualization
* `README.md` – Project documentation

---

## How to Run

1. Open the Jupyter Notebook
2. Run all cells in order
3. Review visualizations and regression results

---

## Author

LiuyingChen
2470403
---

## AI Usage Disclosure

Tool: ChatGPT (OpenAI, GPT-5.3)
Access Date: April 2026

AI was used to assist with code debugging, improving workflow structure, and refining explanations of analysis results. All analytical decisions, interpretations, and final outputs were reviewed and adjusted by the author.


---
