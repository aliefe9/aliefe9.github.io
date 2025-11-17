## Education
- B.A. in Mathematics & Statistics (Major)  
- Economics (Minor)  

## Work Experience
- Financial Analysis Intern, Seva Holding, Turkey, June 2023 - July 2023, June 2024 - August 2024
  - Conducted technical analysis of stocks and market trends using a variety of indicators, resulting in
accurate predictions and informed trading decisions. Utilized strong mathematical methods to perform risk
assessments and optimize portfolio allocation, resulting in a well-balanced investment approach.

## Projects
- **Where's Schueller** – Cleaned and visualized multi-year Google location traces in Python/Plotly to infer a professor’s routine, important locations, and questionable conclusions about their habits  
  _Tools: Python (Google Colab), pandas, Plotly, SciPy, geopy, JSON_  
  - Tested whether Schueller goes to the gym more often on weekdays than on weekends in 2025 using location history
  - Aggregated visits by day of week, plotted weekday vs. weekend gym visits, and ran a two-sample t-test (t = 3.39, p = 0.02), showing Schueller visits the gym significantly more on weekdays (≈13.4 visits) than weekends (7 visits)
  Visual:

<iframe
  src="/location_data_by_day_of_week.html"
  width="100%"
  height="600"
  style="border:none;"
>
  <p>Your browser does not support iframes.</p>
</iframe>

## Above & Beyond: Privacy and Inference
- Even from a limited subset of geolocation data, we can infer daily routines, gym habits, and important locations. In real-world settings, app developers could combine this with other data (purchases, social media, etc.) to build very detailed profiles of people. However, these inferences can also be misleading because of missing days or gaps can hide key parts of someone’s routine, GPS errors can misplace visits, and context (injury, vacation, schedule change) is not visible in the raw data.

- In conclsuion, this project shows how a single person’s location history can be turned into testable hypotheses about daily habits, supported by both visualization and basic statistical analysis. At the same time, the work highlights that any pattern we “discover” is shaped by gaps, noise, and missing context, so responsible data analysis need to pair quantitative results with careful interpretation.

## Data Sources and Project Ideas
- [Basketball Players Stats Extended analysis](https://www.kaggle.com/code/isaienkov/basketball-players-stats-extended-analysis/input)
  - Could do a statistical search on how successfull nba teams had been with their number 1 draft
- [AI Workforce & Automation Dataset (2015–2025)](https://www.kaggle.com/datasets/emirhanakku/ai-workforce-and-automation-dataset-20152025)
  - Could analyze how the recent advancements in AI effected employment rate, average salary, productivity, etc and even compare with differrent countries.
- [ESPN Soccer Data](https://www.kaggle.com/datasets/excel4soccer/espn-soccer-data)
  - I want to find the prime soccer player age by looking at their stats and achievements their whole career. Need to use merge.
- [Athlete Overtraining Prediction Dataset](https://www.kaggle.com/datasets/yuanchunhong/athlete-overtraining-prediction-dataset)
  - Find the optimal training load, rest time etc for the max output. 
- [Cristiano Ronaldo All Club Goals](https://www.kaggle.com/datasets/azminetoushikwasi/cr7-cristiano-ronaldo-all-club-goals-stats)
  - Find the best goalscoring minute by using Cristiano Ronaldo's club goals stats and also find the worst minute.
