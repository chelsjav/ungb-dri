# Tracking U.S. Global Alignment in the United Nations General Assembly

# 📁 Description
This project analyzes long-term trends in how countries align with U.S. positions in the United Nations General Assembly (UNGA). Using roll-call vote data and ideal point estimates from 1946 to 2023, it builds a Diplomatic Risk Index (DRI) to quantify and visualize changes in international alignment over time. The project includes exploratory data analysis, trend visualization, and a predictive XGBoost regression model to forecast future U.S. alignment by country based on historical voting behavior, volatility, and ideological distance.

# 🔍 Key Features:
- Exploratory Data Analysis (EDA) of country voting trends and alliance structures
- Diplomatic Risk Index (DRI): combines alignment decline, volatility, and ideological distance
- Machine Learning Forecasting using XGBoost to predict future diplomatic alignment
- Visualizations highlighting top allies, most volatile countries, and shifting geopolitical patterns

# 🛠️ Utility Belt
- Python (Pandas, Seaborn, Matplotlib, Scikit-learn, XGBoost, Statsmodels)
- Data from Voeten UN Voting Dataset
- Designed for applications in political risk analysis, foreign policy, and multilateral strategy planning

# 🔬 Key Findings
- Global U.S. Alignment is Falling: Average UNGA agreement with U.S. votes has declined steadily since the 1950s, especially among non-NATO countries.
- NATO Countries Remain More Aligned: NATO members show more consistent support for U.S. positions, while non-members exhibit sharper and sustained declines.
- Ideological Distance Predicts Alignment: Countries ideologically closer to the U.S. vote more in line with it; those farther away show lower agreement scores.
- Top Diplomatic Risks Identified: Nicaragua, Iran, Venezuela, and Cuba rank highest on the Diplomatic Risk Index due to declining, volatile, and ideologically distant behavior.
- Alignment is "Sticky": Most countries show high autocorrelation in voting patterns, indicating persistent alignment over time.
- Predictive Model Performs Well: An XGBoost model achieved strong predictive accuracy (R² = 0.831), showing that future alignment is largely shaped by past behavior and volatility.
- Actionable Insight: The index helps policymakers and analysts monitor shifting alliances and anticipate geopolitical risk.
