Impact of the Affordable Care Act on Health Insurance Coverage (U.S.)
This project is a bit different for me as well as little confusing initially before i actually understood what i wanted to do. It analyzes how health insurance coverage in the United States changed following the implementation of the Affordable Care Act (ACA).
Using state level data, the dashboard evaluates changes in uninsured rates, the role of Medicaid expansion, and the contribution of Marketplace tax credits.
The goal of the project is to quantify policy impact, compare outcomes across states, and clearly explain where and why coverage improvements occurred.

Dataset Description
The dataset contains state-level health insurance data before and after ACA implementation, including:
Uninsured rates (2010 vs 2015)
Changes in uninsured rates
Medicaid enrollment (2013 vs 2016)
Medicaid expansion status by state
Marketplace health insurance coverage
Marketplace tax credits and average monthly subsidy amounts
Each row represents a U.S. state, enabling direct comparison across policy choices and outcomes.

Key Questions Answered
This analysis focuses on three core questions, which are;
How did uninsured rates change across U.S. states after the ACA?
Did states that expanded Medicaid experience larger reductions in uninsured rates?
What role did Marketplace coverage and tax credits play, especially in non-expansion states?

Dashboard Structure
The dashboard was intentionally limited to three core visuals due tothe fact that i wanted to maintain clarity and avoid information overload:
National & State-Level Impact
KPI cards summarizing average uninsured rates and overall change
Ranked bar chart showing states with the largest decreases and increases in uninsured rates

Medicaid Expansion Impact
Comparison of average uninsured rate change between Medicaid expansion and non-expansion states
Clear policy-based contrast using a dedicated slicer

Marketplace & Tax Credit Analysis
Scatter plot relating average monthly tax credits to changes in uninsured rates
Marketplace coverage used to highlight the scale of impact across states
Two slicers are used across the dashboard, which for me are very vital and they are;
State Medicaid Expansion (2016) – policy-level comparison
State – state level exploration

Key Insights
States that expanded Medicaid generally experienced larger reductions in uninsured rates clearly.
Non-expansion states relied more heavily on Marketplace coverage and tax credits
Marketplace subsidies helped reduce financial barriers to insurance enrollment
Policy decisions played a measurable role in health coverage outcomes, not just demographic differences

Tools Used
Power BI – data modeling, DAX measures, and dashboard development
DAX – creation of policy-relevant measures and averages
Data visualization best practices – minimal visuals, consistent color logic, and clear labeling too.

Notes on Interpretation
Negative values in “Uninsured Rate Change” indicate improvements (reductions in uninsured rates)
All changes are expressed in percentage points, not raw percentages
Averages are used to ensure fair comparison across states

📌 Conclusion

This project demonstrates how policy analysis can be supported through clear data modeling and focused visual storytelling.
By limiting visuals and slicers to only what was necessary, the dashboard emphasizes insight over complexity, making it suitable for decision-making, presentation, and portfolio review.
