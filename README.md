# datasets
Sample datasets

### US-Covid-Cases.csv
Source: JHU
Data update: Following query in BigQuery

```
SELECT
    province_state,
    fips,
    date,
    confirmed,
    deaths
FROM `bigquery-public-data.covid19_jhu_csse.summary`
WHERE country_region = 'US'
```

### us_state_vaccinations.csv
Source: https://ourworldindata.org
Data update: Downloaded from [Kaggle](https://www.kaggle.com/paultimothymooney/usa-covid19-vaccinations)
