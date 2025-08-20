# finance-interest-rates-analysis
# This project examined how changes in U.S. interest rates and inflation influence the performance of six major stock market sectors: Technology, Financials, Healthcare, Energy, Utilities, and Real Estate. Using weekly data from 2015 to 2025, we built a structured empirical framework that combined macroeconomic indicators with sector-level ETF returns.

# We sourced weekly sector data from CRSP and macroeconomic variables (Federal Funds Rate and CPI) from FRED. After aligning the datasets, we computed weekly excess returns and ran Ordinary Least Squares (OLS) regressions to estimate sector sensitivities to interest rate and inflation changes. Each regression quantified both the economic magnitude (beta) and statistical significance of these macro factors.

# The results revealed that interest rate changes have a consistently strong and negative impact on all six sectors. Healthcare and Technology were the most sensitive, with interest rate coefficients of -0.44 and -0.30, respectively, while Energy showed the weakest sensitivity (-0.15). CPI was statistically significant in some regressions but had very small coefficients—indicating little economic influence.

# To ensure robustness, we conducted control regressions replacing interest rate changes with CPI. These models showed significantly lower explanatory power (R² < 7% vs. >30% with interest rates), confirming that monetary policy—not inflation alone—is the primary driver of sector returns.

# We visualized sector beta comparisons using heatmaps and annotated bar charts, highlighting the variation in sensitivity across sectors. The findings align with economic intuition: capital-intensive and growth sectors are more rate-sensitive due to their reliance on future cash flows and borrowing costs.

# This project showcased advanced skills in Python (pandas, statsmodels, matplotlib), financial modeling, and macroeconomic interpretation. It also delivered clear portfolio-level insights relevant to asset allocation and rate-driven market cycles.
