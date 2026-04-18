# ACC102_Individual_task
## Firm_Performance_Analysis

## 1. Introduction
This project focuses on a business question: How do firm size and leverage affect profitability of Chinese listed companies? Which analyses the relationship between firm size, financial leverage, and profitability using financial data from CSMAR. The objective is to provide data-driven insights that can support investors in evaluating firm performance and making more informed investment decisions.

Profitability is assessed using multiple indicators, including Return on Assets (ROA), Return on Equity (ROE), and profit margin, allowing for a comprehensive evaluation of asset efficiency, shareholder returns, and operational performance.

---

## 2. Data Source
The data is obtained from the CSMAR database, which provides financial information on Chinese listed companies.

Key variables include:
Net Profit
ROA (Return on Assets)
ROE (Return on Equity)
Leverage
Profit Margin

For analytical clarity, Firms are grouped into four size categories based on their scale, using total size indicators (e.g., total assets or net profit) to classify companies into “Low”, “Medium-Low”, “Medium-High”, and “High” groups.

The grouping is designed to simplify the analysis and allow for clearer comparison of financial performance across different firm sizes. By aggregating firms into size-based categories, the study highlights general patterns in profitability, efficiency, and financial risk.

---

## 3. Methodology

### Data Visualisation

Bar charts are used to compare financial performance across firm size groups.
A dual-axis chart is used to compare ROA (profitability) and leverage (financial risk) across firm size groups. ROA is presented as a line, while leverage is shown as a bar chart on a secondary axis to highlight their relationship.

### Regression Analysis

An Ordinary Least Squares (OLS) regression model is applied to examine the relationship between profitability (ROA) and key financial factors such as leverage and profit margin.

---

## 4. Key Insights for Investors
Larger firms generate significantly higher net profits, indicating strong economies of scale and more stable earnings potential.
Profitability (ROA and ROE) improves with firm size, suggesting that larger firms are more efficient in utilizing assets and delivering returns to shareholders.
Leverage increases with firm size, implying that higher profitability may be accompanied by greater financial risk.
Smaller firms exhibit negative or volatile profit margins, indicating potential operational instability and higher uncertainty.

These findings highlight an important trade-off between profitability and financial risk, which investors should consider when evaluating investment opportunities.

---

## 5. Investment Implications
* Investors seeking stable returns may prefer larger firms due to their higher profitability and efficiency.
* Investors with higher risk tolerance may explore smaller firms for potential growth opportunities, but should be cautious of financial instability.
* The increasing leverage among larger firms suggests the need to carefully assess debt levels when evaluating investment risk.

---

## 6. Project Structure

README.md ： Project documentation

individual task.ipynb ： Main analysis notebook

---

## 7. Limitations

This analysis has several limitations that should be considered when interpreting the results.

First, although the original dataset contains extensive firm-level observations, the data is aggregated into four firm size groups for analytical clarity. This aggregation significantly reduces the number of observations and limits the statistical power of the regression model.

Second, grouping firms may mask important variations within each category. Firms within the same size group can differ substantially in terms of profitability, risk, and operational characteristics, which are not captured in this analysis.

Third, the regression model includes only a limited number of explanatory variables, such as leverage and profit margin. Other important factors, including industry effects, firm-specific characteristics, and macroeconomic conditions, are not considered, which may lead to omitted variable bias.

In addition, the analysis is based on cross-sectional data and does not account for changes over time. Therefore, it cannot capture dynamic trends in firm performance.

Finally, the findings are based on Chinese listed companies, which may limit the generalisability of the results to other markets.

Overall, these limitations suggest that the results should be interpreted with caution, and further research using more detailed and longitudinal data is recommended.


---

## 8. Conclusion

The analysis shows that larger firms achieve higher profitability and efficiency, as reflected in increasing ROA and ROE. However, they also rely more on leverage, indicating higher financial risk. Smaller firms demonstrate more unstable performance, with negative profit margins in some cases. Although regression results suggest a positive relationship between leverage and profitability, the findings are not statistically significant due to the small sample size. Overall, investors should consider the trade-off between profitability and risk when making investment decisions.

---
