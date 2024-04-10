# Gender Balance with Small Dataset

## Summary 

Measuring and monitoring gender balance is crucial for societies striving to achieve equality, equity, and sustainable development. Ongoing assessment of gender balance trends can drive meaningful progress towards a more equitable and prosperous future for all. This research study aims to provide a comprehensive understanding of gender balance in Australia by analysing labour force and overseas migration data for each state and territory. The study utilised a small dataset of 16 data points per state and territory. Becker's coefficient was applied to analyse gender opportunity trends. The researchers also proposed a new formula to predict a gender balance index, taking into consideration overseas migration and employment factors. The analysis employed descriptive statistics and visualisations to highlight key insights.
Three forecasting models were tested: ARIMA, GM(1,1), and GM(2,1). The results indicate that GM(1,1) is the optimal model for predicting the gender balance index for the next 5 years. 
This research contributes to the understanding of gender balance dynamics in Australia and provides a framework for ongoing monitoring and assessment. The findings can inform policy decisions and interventions to promote greater gender equality and equity across the country.

## Key words

Gender Balance, Overseas Migration, Australia Labour Market, Diversity in Workplace, Becker's Discrimination Coefficient (D), ARIMA model, Grey Model, MAPE.

## Problem statement 
 
Achieving Gender Balance (GB) in the Australian labour force and overseas migration is essential for fostering equality, diversity, and inclusion in workplaces and communities. Overseas migration plays a crucial role in shaping this balance, as migrants of all genders bring unique skills, experiences, and perspectives that can contribute to a more diverse and inclusive workforce. Predicting and understanding gender dynamics at the state/territory level is a significant challenge, as labour force participation and migration patterns are influenced by a complex interplay of socio-economic factors, cultural norms, and policy environments. Analyzing labor force and overseas migration data, categorized by gender and considering regional differences, reveals insights crucial for promoting equal opportunities, creating diverse and equitable workplaces, and fostering social cohesion in Australia's multicultural landscape.

## Methodoly
This research focuses mainly on predicting gender equality by sex and state/territory. Therefore, diverse factors that contribute to measuring gender equality were taken into consideration including overseas migration by state/territory classified by sex from 2004 onwards and labor Force status by sex, state, and territory from 1978 onwards. Both dataset has different periods (years). Consequently, it was considered from 2004 to 2022.

**Assumptions:** 
- It was assumed that the count of employees encompasses individuals from diverse backgrounds, including migrants, citizens, and Aboriginal peoples.

  ## Australian Bureau of Statistics: Data source
 
 - [Net overseas migration, Arrivals, departures and net, State/territory, Age and sex - Calendar years, 2004 onwards](https://explore.data.abs.gov.au/vis?tm=Migration&pg=0&df[ds]=ABS_ABS_TOPICS&df[id]=NOM_CY&df[ag]=ABS&df[vs]=1.0.0&pd=2004%2C&dq=1%2B2%2B3.TOT.1%2B2%2B3..A&ly[cl]=TIME_PERIOD&ly[rw]=REGION&ly[rs]=SEX%2CMEASURE)
  Last access= 09-April-2024
- [Labour Force status by Sex, State and Territory - Number of people employed, unemployed and not in the labour force, monthly, February 1978 and onwards](https://explore.data.abs.gov.au/vis?tm=labour%20force&pg=0&df[ds]=ABS_ABS_TOPICS&df[id]=LF&df[ag]=ABS&df[vs]=1.0.0&hc[Measure]=Labour%20Force&hc[ABS%20Topics]=LABOUR&pd=2004-01%2C2023-12&dq=M3.3%2B2%2B1.1599.30.1%2B2%2B3%2B4%2B5%2B6%2B7%2B8.M&ly[cl]=TIME_PERIOD&vw=tb)
Last access= 09-April-2024

  ## Run code
This repository contains 6 folders. 
1. A folder called `excel_data` which contains the following excel files:
    - An Excel file: `data_exclu_20-21.xlsx`
    - A folder `EDA_data` which has 2 excel files (`EDA_LABOUR.xlsx` and `EDA_MIGRATION.xlsx`
    - A folder `Result_all_models` which has 3 folders.
      - ARIMA (It has 2 files with metrics and predictions results)
      - GM11 (It has 2 files with metrics and predictions results)
      - GM21 (It has 2 files with metrics and predictions results)
      - predict_next_5years has `future_pred_GM11.ipynb` results.
2. A folder called `EDA_oversea_migration_labour_force` with a file known as `EDA_Migration_Employment_plots.ipynb`. It plots Gender Balance (GB) in overseas migration and labor force by gender and Australian State/Territory.
3. A folder called `Gender_balance_index_plot` with a file known as `gender_balance_index.ipynb`. it plots the GB index.
4. A folder called `Forecasting model` with three **ipynb** files. It contains `ARIMA_model.ipynb`, `Grey_Model_11.ipynb`, and `Grey_Model_21.ipynb`.
5. A folder called `Compare_models`. It has 2 files including `compare_metrics.ipynb` and `compare_models.ipynb`. Compare all metrics and models across all Australian States/territories. 
6. A folder called  `Prediction_next_5years` has a `prediction_next_5_years.ipynb` file. This file predict the next 5 years applying GM11. 


## Observations

Each .ipynb file includes its own set of instructions along with guidance on which Excel files should be loaded.
   
