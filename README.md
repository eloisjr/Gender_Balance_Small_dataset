# Gender Balance with Small Dataset

## Summary 

Measuring and monitoring gender balance is crucial for societies striving to achieve equality, equity, and sustainable development. Ongoing assessment of gender balance trends can drive meaningful progress towards a more equitable and prosperous future for all. This research study aims to provide a comprehensive understanding of gender balance in Australia by analysing labour force and overseas migration data for each state and territory. The study utilised a small dataset of 16 data points per state and territory. Becker's coefficient was applied to analyse gender opportunity trends. The researchers also proposed a new formula to predict a gender balance index, taking into consideration overseas migration and employment factors. The analysis employed descriptive statistics and visualisations to highlight key insights.
Three forecasting models were tested: ARIMA, GM(1,1), and GM(2,1). The results indicate that GM(1,1) is the optimal model for predicting the gender balance index for the next 5 years. 
This research contributes to the understanding of gender balance dynamics in Australia and provides a framework for ongoing monitoring and assessment. The findings can inform policy decisions and interventions to promote greater gender equality and equity across the country.

## Key words

Gender Balance, Overseas Migration, Australia Labour Market, Diversity in Workplace, Becker's Discrimination Coefficient (D), ARIMA model, Grey Model, MAPE.

## Problem statement 
 
Achieving gender balance in the Australian labour force and overseas migration is essential for fostering equality, diversity, and inclusion in workplaces and communities. Overseas migration plays a crucial role in shaping this balance, as migrants of all genders bring unique skills, experiences, and perspectives that can contribute to a more diverse and inclusive workforce. Predicting and understanding gender dynamics at the state/territory level is a significant challenge, as labour force participation and migration patterns are influenced by a complex interplay of socio-economic factors, cultural norms, and policy environments. Analyzing labor force and overseas migration data, categorized by gender and considering regional differences, reveals insights crucial for promoting equal opportunities, creating diverse and equitable workplaces, and fostering social cohesion in Australia's multicultural landscape.

## Methodoly
This research focuses mainly on predicting gender equality by sex and state/territory. Therefore, diverse factors that contribute to measuring gender equality were taken into consideration including overseas migration by state/territory classified by sex from 2004 onwards and labor Force status by sex, state, and territory from 1978 onwards. Both dataset has different periods (years). Consequently, it was considered from 2004 to 2022.

**Assumptions:** 
- It was assumed that the count of employees encompasses individuals from diverse backgrounds, including migrants, citizens, and Aboriginal peoples.

  ## Dataset source
 
  [Net overseas migration, Arrivals, departures and net, State/territory, Age and sex - Calendar years, 2004 onwards](https://explore.data.abs.gov.au/vis?tm=Migration&pg=0&df[ds]=ABS_ABS_TOPICS&df[id]=NOM_CY&df[ag]=ABS&df[vs]=1.0.0&pd=2004%2C&dq=1%2B2%2B3.TOT.1%2B2%2B3..A&ly[cl]=TIME_PERIOD&ly[rw]=REGION&ly[rs]=SEX%2CMEASURE)
  last access= 09-April-2024
