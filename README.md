# Sardar Patel Institute of Technology  
## Project Report  
### Python for Data Science  

**Submitted by**:  
1. Shivsharan Sanjawad (2023300194)  
2. Sai Rane (2023300183)  
3. Piyush Rathi (2023300186)  
4. Sania Rakhangi (2023300180)  

**Division**: C  
**Batch**: C3  

## Exploratory Data Analysis on the COVID-19 Pandemic  
**A.Y. 2024-25**  

---

## Abstract  
This study explores the widespread impact of the COVID-19 pandemic across various sectors:  

- **Public Health**: Trends in COVID-19 cases, testing rates, and positivity ratios.  
- **Economy**: Disruptions in stock markets, inflation trends, and oil-dependent economies.  
- **Environment**: Reduction in pollution and global trade disruptions.  
- **Education**: Transition to online learning, digital divide, and its societal effects.  

### Key Insights:
- Leveraged publicly available datasets for holistic analysis.
- Used sentiment analysis on social media to understand public opinions.
- Analyzed economic and environmental trends to assess recovery strategies.  

![COVID-19 Trends Overview](images/covid_trends.png)

---

## Introduction  

### Problem Statement  
The COVID-19 pandemic caused disruptions in public health, the global economy, and education systems. Understanding these impacts is crucial to forming strategies for future crises.

### Objectives  
1. Analyze the pandemic's impact across different sectors:
   - Economic indicators  
   - Environmental data  
   - Educational disruptions  
   - Public sentiment.  
2. Provide actionable insights for policymakers and stakeholders.  

### Motivation  
The pandemic's global disruption offers a unique opportunity to apply data analysis techniques and understand cascading effects across multiple sectors.

---

## Dataset  

### Sourcing the Dataset  
The dataset was sourced from Kaggle, World Health Organization, and other credible platforms.

### Description  
Key features of the dataset include:
- **COVID-19 Case Data**: Confirmed cases, recoveries, and fatalities across countries.  
- **Testing and Positivity Rates**: Number of tests conducted and positivity ratios.  
- **Vaccination Rates**: Information on vaccine distribution and public sentiment.  
- **Economic Indicators**: GDP, inflation rates, and stock market data.  
- **Environmental Metrics**: Air quality, CO2 levels, and temperature changes.  
- **Educational Statistics**: Transition to online learning and its challenges.  

![Dataset Description](images/dataset_description.png)

### Data Preprocessing  
1. Handled missing values using median/mean imputation.  
2. Normalized datasets for consistency.  
3. Engineered new features like a **COVID Impact Index** to assess regional vulnerabilities.  

---

## Exploratory Data Analysis (EDA)  

### Public Health Trends  
We analyzed patterns in testing rates, positivity ratios, and vaccination rates:  

- **Key Observation**: Positivity rates were initially high due to limited testing.  

![Positivity Rates vs New Cases](images/positivity_rate_vs_cases.png)

### Economic Impact  
- **GDP Decline**: Significant negative correlation between GDP growth rates and COVID-19 case numbers.  
- **Stock Market Impact**: Major indices like Nifty 50 and Sensex dropped during the pandemic's peak.  

![Economic Indicators](images/economic_impact.png)

### Environmental Changes  
- **Air Quality**: Lockdowns led to reduced pollution in urban areas.  
- **Temperature Variations**: Changes in weather patterns were observed globally.  

![Environmental Impact](images/environmental_impact.png)

### Education Sector Disruption  
- Shift to online learning caused disparities between high-income and low-income countries.  

![Online Learning Trends](images/online_learning_trends.png)

---

## Sentiment Analysis  

### Methodology  
- Collected tweets related to COVID-19 using hashtags.  
- Used **VADER (Valence Aware Dictionary and Sentiment Reasoner)** for sentiment scoring.  
- Categorized sentiments as **Positive**, **Negative**, and **Neutral**.  

### Observations  
- Sentiment towards vaccines varied widely across regions.  
- Public sentiment aligned with major news events during the pandemic.  

![Sentiment Analysis Results](images/sentiment_analysis.png)

---

## Challenges  

1. **Data Quality Issues**: Missing and inconsistent data required extensive preprocessing.  
2. **Handling Missing Data**: Imputation techniques like interpolation were used cautiously.  
3. **Data Integration**: Merging datasets with differing formats was challenging.  
4. **Visualization**: Creating intuitive, meaningful visualizations to convey insights.  

---

## Conclusion  

This project provided a detailed analysis of the COVID-19 pandemic's impact on education, public health, the economy, and the environment. Key findings include:  

1. **Public Health**: Effective measures like lockdowns and vaccination programs significantly reduced case severity.  
2. **Economy**: Economic recovery patterns varied across countries based on resource availability.  
3. **Education**: Online learning highlighted disparities in access to technology.  
4. **Environment**: Lockdowns led to temporary improvements in air quality.  

### Key Takeaway:  
Data-driven decision-making is crucial for managing crises and building resilient systems.

---

## Sources  
1. [Kaggle COVID-19 Dataset](https://www.kaggle.com)  
2. [World Health Organization (WHO)](https://www.who.int)  
3. [OECD Data](https://www.oecd.org)  
4. [Indian Government COVID-19 Data](https://data.gov.in)  
