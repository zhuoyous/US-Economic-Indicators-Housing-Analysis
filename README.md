# US Economic Indicators & Housing Analysis

This repository presents a comprehensive data analysis project exploring how U.S. macroeconomic indicators such as inflation, interest rates, trade activity, and GDP influence housing prices. It was developed as part of the DSCI 550 course project at USC and demonstrates skills in data collection, preprocessing, visualization, regression modeling, and storytelling with real-world datasets.

##  Project Structure

```
DSCI550_Project/
├── code/
│   ├── Project .ipynb                      # Main analysis: scraping inflation, modeling housing prices
│   ├── Import&Export&GDP&president.ipynb   # Trade data collection via UN Comtrade API
│   ├── Lab6Code.py                         # Helper script for CSV manipulation
│   ├── scrape.db                           # SQLite database used in preprocessing
│   ├── stats.xlsx                          # Supporting Excel file with macro indicators
├── data/
│   ├── *.csv                               # Cleaned datasets (inflation, trade, interest, housing)
│   ├── *.xlsx                              # Trade and economic data in Excel format
├── Report.pdf                              # Final presentation/report summarizing key findings
```

##  Key Objectives

- Analyze how macroeconomic variables impact housing prices over time
- Build regression models to quantify relationships
- Scrape and process U.S. inflation rates and trade values from public sources
- Visualize economic trends with Matplotlib
- Evaluate model performance using statistical metrics

##  Tools & Technologies

- Python (Pandas, NumPy, StatsModels, Scikit-learn, Matplotlib)
- Web Scraping (BeautifulSoup, requests)
- SQL (SQLite)
- Data sources: UN Comtrade API, US Inflation Calculator

##  Highlights

- Built linear regression models to predict housing prices using inflation, interest rate, and import/export data
- Collected U.S. trade data from 2010–2020 via the Comtrade API and analyzed export/import trends
- Scraped and structured historical inflation rate tables using BeautifulSoup
- Created a consolidated dataset linking inflation, housing, and economic indicators
- Delivered a final report summarizing insights and model results

##  Report

See [`Report.pdf`](./DSCI550%20Project/Report.pdf) for full documentation, visuals, and conclusions.

##  Ideal For

This project is ideal to showcase:

- Data pipeline creation (scraping → cleaning → analysis)
- Applied economics and housing market insights
- Technical proficiency in Python and data storytelling
