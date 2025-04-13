# World-Bank-API
## Worldbank API - Research

The World Bank API provides access to a vast collection of global development data, including indicators related to economics, health, education, environment, and more. It allows users to retrieve up-to-date data from the World Bank's extensive database, which includes information from over 200 countries. This API is a valuable tool for researchers, analysts, and developers who want to explore global trends, perform statistical analyses, and create visualizations based on reliable and comprehensive data from the World Bank.
Diarrhea Prevalence for children

For this project, we explored global health data using the World Bank API to uncover interesting trends and patterns. The goal was to apply what we’ve learned in the Practical Introduction to Programming in Python course to analyze real-world data. We chose the World Bank API because of its rich collection of health-related indicators, which allowed us to investigate meaningful global health topics.

### We focused on the following research question:

To what extent does the gap in diarrhea prevalence for children under the age of 5 between the poorest and richest quintiles vary across countries in different income groups (low income, lower middle income, upper middle income)? How do the treatment of the diarrhea cases correlate with the income group and the quintile looked at?

To answer these questions, we retrieved and cleaned the data using Python, tackled missing or inconsistent values, and created visualizations to make the findings more accessible. We also included interactive features, like ipywidgets, so users could engage with the data and explore different aspects dynamically.

## Conclusion

There is a marked difference in diarrhea prevalence between the poorest and richest quintiles in lower-middle-income (LMC) and upper-middle-income (UMC) countries, where the gap is statistically significant (p-value < 0.05). This suggests growing inequality in access to clean water and sanitation as countries develop, leaving the poorest quintile behind.

In contrast, this gap is not significant (p-value > 0.05) in low-income countries (LICs), indicating that both the poorest and richest quintiles face similarly high rates of diarrhea. This can be attributed to widespread underdevelopment, where even the wealthiest households lack consistent access to clean water and sanitation.

Treatment rates for diarrhea show no significant correlation with wealth quintiles in any income group. Contrary to expectations, the p-values in all income groups (LIC, LMC, UMC) indicate no statistically significant difference between the poorest and richest quintiles. However, the high variability in both income-groups (LMC, UMC) shows that the data is difficult to statistially evaluate. This is the reason why the research cannot be answered cleary and further investigations need to be done.
