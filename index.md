## Ali Efe Isik
## Data Analyst | Mathematics-Statistics & Economics | Whitman College '26

## Education
- B.A. Mathematics-Statistics (Major), Economics (Minor) — Whitman College, Walla Walla, WA — Graduating May 2026
- Whitman International Student Scholarship Recipient; 2026 Whitman Standout Senior
- **Relevant Coursework:** Statistical Modeling, Design & Analysis of Experiments, Econometrics, Probability Theory, Foundations of Machine Learning, Intro to Data Science, Statistical Theory, Linear Algebra, Multivariate Statistics

## Skills
- **SQL:** Complex joins, data cleaning, aggregation, and transformation
- **Tableau:** KPI dashboards, trend analysis, automated reporting
- **Python (pandas):** Data cleaning, exploratory analysis, and visualization
- **R & SAS:** Statistical modeling, regression, hypothesis testing
- **Excel & MATLAB:** Quantitative modeling and structured analysis

## Work Experience

**Data Analyst** — City of Walla Walla, Water Consumption & Rate Analysis | January 2026 – May 2026 *(Ongoing)*
- Working with the City of Walla Walla to analyze municipal water consumption data and evaluate conservation strategies while maintaining required revenue targets
- Analyzing usage patterns across customer classes and modeling 5%, 10%, and 20% reduction scenarios to develop equitable, conservation-focused rate recommendations

**Financial Analysis Intern** — Seva Holding, Bursa, Turkey | June 2023 – July 2023 / June 2024 – August 2024
- Conducted technical analysis of equities and market trends using multiple indicators (support/resistance, volume, moving averages, RSI, MACD) to support trading decisions and portfolio allocation
- Used R and Python to clean market data, compute indicators, and evaluate strategy performance

**Member** — Whitman Investment Club, Walla Walla, WA | September 2022 – May 2026
- Built SQL pipelines integrating 10+ years of macroeconomic datasets (employment, inflation, GDP, interest rates) into analysis-ready tables; developed Tableau dashboards tracking YoY and long-term trends by region and timeframe
- Conducted quantitative analysis on market shifts and structural relationships; translated findings into executive-ready visual summaries and written insights

## Leadership & Activities
**Whitman College Men's Basketball Team** | August 2022 – Present
- Four-year starter and senior team captain; back-to-back league championships; 3-time All-Conference selection; 7th all-time leading scorer in program history (1,200+ career points)

**Green Park Elementary School Volunteering** | August 2022 – Present
- Mentored elementary students in math and academic support, building one-on-one relationships with students 
  to strengthen foundational skills and confidence in the classroom.

### Projects

- **[Where's Schueller?](https://aliefe9.github.io/Where-s-Schueller/)** – Analyzed real Google location history data from a Whitman College professor to test whether gym visits were more frequent on weekdays than weekends using geospatial filtering and hypothesis testing  
  _Tools: Python (Google Colab), pandas, Plotly, SciPy, geopy, JSON_
  - Filtered 71,000+ location data points to a 30-meter radius around Baker Ferguson Fitness Center; resampled to daily visits and visualized by day of week
  - Ran a two-sample Welch's t-test (t = 3.39, p = 0.02), finding significantly more weekday gym visits (≈13.4) than weekend visits (7.0)

<br>

- **[Evaluating NBA Lottery Picks Using Career Performance](https://aliefe9.github.io/Evaluating_NBA_Lottery_Picks_Using_Career_Performance/)** – Cleaned and analyzed ~20 years of NBA top-10 draft picks to quantify career success and identify which teams most often drafted underperforming players  
  _Tools: Python (Google Colab), pandas, Plotly, scikit-learn (k-means)_
  - Computed PIR and career-level metrics (avg PIR, MPG) from a multi-season Kaggle NBA stats dataset, then clustered top-10 picks into low, medium, and high performance tiers
  - Counted low-PIR ("bust") picks by drafting team, finding Sacramento with 8 underperforming top-10 picks (vs ≈2.9 average)

<br>

- **[Does Test Prep Improve Math Test Scores?](https://aliefe9.github.io/Does_Test_Prep_Improve_Math_Test_Scores/)** – Analyzed Kaggle's "Students' Performance in Exams" dataset (n = 1000) to estimate the math score difference between students who completed test prep vs. those who did not using bootstrap resampling  
  _Tools: R, RStudio, R Markdown, tidyverse (dplyr/ggplot2), bootstrap/resampling_
  - Defined D = X − Y across prep and no-prep groups; ran a nonparametric bootstrap to build 95% confidence intervals
  - Results suggest test prep is associated with a positive average math score advantage of approximately 5–6 points

<br>

- **[Kansas City vs. National Unemployment: A Statistical Analysis](https://aliefe9.github.io/Kansas_City_vs_National_Unemployment-_Statistical_Analysis/)** – Used FRED data to test whether Kansas City's unemployment rate is statistically lower than the national average, with yearly breakdowns and trend analysis  
  _Tools: Python (Google Colab), pandas, Plotly, SciPy, FRED_
  - Merged monthly KC and national unemployment data (2020–2025); ran a two-sample Welch's t-test across the full dataset and per year
  - Full dataset: t = −5.612, p < 0.0001; KC was significantly lower than national every year from 2021–2025, with the gap narrowing from −2.00% in 2020 to −0.37% in 2025

<br>

- **[Education Level and IQ](https://aliefe9.github.io/Education_Level_and_IQ/)** – Investigated the relationship between education level and IQ scores using a stratified sample of 60 individuals, applying ANOVA and post-hoc analysis  
  _Tools: R, RStudio, R Markdown, tidyverse (ggplot2)_
  - Conducted a one-way ANOVA (F = 9.352, p = 0.0003) rejecting the null hypothesis that average IQ scores are equal across education groups
  - Post-hoc analysis revealed the medium education group scored significantly lower than both the low and high groups; R² = 24.7%
