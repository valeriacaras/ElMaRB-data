# Electoral Malpractice, Cyber-security, and Political Consequences in Russia and Beyond Project

## Data on cross-regional Electoral Malpractice in Russia

*Release: 1.3 version*

*Date: 26 May 2022*

*Added: Overall numbers of messages in regional media during the electoral campaigns. The variables cover periods six months before elections, three months before elections, on the electoral day and one day after, one month after elections*

*Release: 1.2 version*

*Date: 21 February 2022*

*Added: Messages on electoral violations in the regional media were split in the four separate variables: number of messages in media six months before elections, number of messages in media three months before elections, number of messages in media on election day and the following day, number of messages in media one month later elections*


*Release: 1.1 version*

*Date: 12 February 2022*

*Added: percent of voting for the main political parties in the State Duma elections and percent of voting for candidates in the Presidential elections*

*Release: 1 version*

*Date: 15 November 2021*

[![DOI](https://zenodo.org/badge/427669912.svg)](https://zenodo.org/badge/latestdoi/427669912) 

*[Electoral Malpractice, Cyber-security, and Political Consequences in Russia and Beyond Project](url) is funded by the University of Helsinki and is based in Aleksanteri Institute, Helsinki, Finland*

### Project team:
1. Margarita Zavadskaya, Project Leader, Postdoctoral Researcher
2. Elena Gorbacheva, Project Planner, Doctoral Student
3. Valeria Caras, Research assistant

#### About the dataset

The data covers socioeconomic characterisics of Russian regions, as well as variables on TV and Internet coverage in the each subject of the Russian Federation. The dataset contributes with the new variables on electoral coverage during both Presidentional and State Duma electoral campaigns which capture the amount of messages on elections in Russian regional media sources and amount of messages on electoral fraud. Data covers the 2007, 2011, 2016, 2021 State Duma elections and 2008, 2012, 2018 Presidential elections. 

| Variable Name | Variable Label and Variable Description | Scale and timeframe of coverage | Source|
| --- | --- |--- |--- |
| fad_id | ID of the federal administrative district |Numeric |
| cec_id | ID of region | numeric | [Central Electoral Commission](url) |
| id | Number of Federal district and ID of the region | Numeric | [Central Electoral Commission](url) |
| r_name | Name of a region in English | Text | [Wikipedia/Road signs romanization of Russian](url) |
| r_translit | Name of a region in Russian | Text | [Wikipedia](url) | 
| iso_id  | ISO country code 3166-2 Russia | Text | [Wikipedia](url) |
| is_nat_republ | The status of the national republic: 1 – National republic, 0 – Other types (Kray, oblast’, avtonomnaya oblast’, avtonomny okrug | dichotomous | [Wikipedia](url) |
| perc_urban | Share of the urban population in total population | Interval (share), 2007 - 2020 | [Federal State Stastics Service](url) |
| share_non_work_pop | Age composition of the population over working age | Interval, 2010 - 2020 | [Federal State Stastics Service](url) |
| grp_capita | Gross regional product per capita (rubles) | Interval, 2007 - 2019 | [Federal State Stastics Service](url) |
| gini | The Gini coefficient is calculated as the ratio of the incomes of the richest and the poorest segments of the population | Interval, from low to high (0-1), 2010 - 2017 | [Federal State Stastics Service](url) |
| lab_educ_p | Percent of people working in the education sector | Interval, 2013 - 2019 | [Federal State Stastics Service](url) |
| ratio_msal_educ_gen | The ratio of mean salary in education to mean salary in general | Interval (share), 2013 - 2019 | [Federal State Stastics Service](url) |
| share_sbenefits | Share of income from social benefits | Interval (share), 2010 - 2019 | [Federal State Stastics Service](url) |
| investments_cap_fbudg_p | Percent of capital investments by federal budget | Intervel (percent), 2010 - 2019 | [Federal State Stastics Service](url) |
| govern_app | Is the head of the region appointed or elected: 1 – is appointed; 0 - elected | dichotomous, 2011 - 2021 |  [Wikipendia/Elections of the heads of the regions in the Russian Federation](url) |
| turnout_gd | Regional turnout for the State Duma elections calculated as: (valid+invalid votes)/people having the right to vote | Interval, years: 2007, 2011, 2016, 2021 | [Central Electoral Commission](url) |
| turnout_presd| Regional turnout for the presidential elections calculated as: (valid+invalid votes)/people having the right to vote | Interval, years: 2008, 2012, 2018 | [Central Electoral Commission](url) |
| deyr_crude | Number of falsifications filed during the day of elections | Numeric, years: 2012 Presidential Elections, 2016 State Duma Elections, 2018 Presidential Elections, 2021 State Duma Elections | [Violation map (Karta narusheniy)](url)|
| tv_cov_pervy | TV and radio coverage ratio: First Channel (Pervy kanal) | Interval (share), 2008 - 2017 | [Federal State Stastics Service](url) |
| tv_cov_rossiya | TV and radio coverage ratio: Rossiya Channel | Interval (share), 2008 - 2017 | [Federal State Stastics Service](url) |
| tele_cov_mobile | Coverage by mobile/wireless networks. The number of connected subscriber devices of mobile radiotelephone communication per 1000 population | Interval (share), 2010 - 2020 | [Federal State Stastics Service](url) |
| tele_cov_internet | Coverage by Internet.  Number of active subscribers of fixed broadband Internet access | Interval (share), 2011 - 2020 | [Federal State Stastics Service](url) |
| npapers_1000pep | Publication of newspapers per 1000 people | Numeric, 2007 - 2020 | [Federal State Stastics Service](url) |
| mess_fals_presid_year | Coverage of electoral fraud by regional mass media. The results for query “(выборы and (президент Россия)) and (фальсификация or фальсифицировать or вбросы or махинация)”. Search was filtered for the dates of the electoral campaign and regional media | Numeric, years: 2008, 2012, 2018 | [Integrum World Wide. Electoronic Portal of Russia and the CIS](url) |
| elect_mess_pres_year | Coverage of elections by regional media. The result for query “(выборы and (президент Россия))”. The search was filtered for the dates of the electoral campaign and regional media| Numeric, years: 2008, 2012, 2018 | [Integrum World Wide. Electoronic Portal of Russia and the CIS](url) |
| per_violmess_all_pres_year | Percent of mentions of falsifications in media from the total number of messages covering the electoral campaign | Interval (share, years: 2008, 2012, 2018 | [Integrum World Wide. Electoronic Portal of Russia and the CIS ](url)|
| crude_fals_parl_year | Coverage of electoral fraud by regional mass media. The results for query “(выборы and (государственная and дума)) and (фальсификация or фальсифицировать or вбросы or махинация)”. The search was filtered for the dates of the electoral campaign and regional media. | Numeric, years: 2007, 2011, 2016, 2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elect_mess_parl_year | Coverage of elections by regional media. The results for query “(выборы and (государственная and дума))”. The search was filtered for the dates of the electoral campaign and regional media | Numeric, years: 2007, 2011, 2016, 2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| per_violmess_all_parl_year | Percent of mentions of falsifications in media from the total number of messages covering the electoral campaign |  Interval (share), years: 2007, 2011, 2016, 2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| ur_voting_year | Percent of vote for the United Russia party at the regional level | Interval (percent), years: 2007, 2011, 2016, 2021 | [Central Electoral Commission](url) |
| kprf_voting_year | Percent of vote for the Communist Party of the Russian Federation party at the regional level | Interval (percent), years: 2007, 2011, 2016, 2021 | [Central Electoral Commission](url) |
| ldpr_voting_year | Percent of vote for the Liberal Democratic Party of Russia at the regional level | Interval (percent), years: 2007, 2011, 2016 | [Central Electoral Commission](url) |
| sr_voting_year | Percent of vote for the A Just Russia — For Truth at the regional level | Interval (percent), years: 2007, 2011 | [Central Electoral Commission](url) |
| pre_candidatesurname_year | Percent of vote for candidate at the regional level in the Presidential elections| Interval (percent), years: 2008, 2012,2018 | [Central Electoral Commission](url) |
| elections_year_viol6m | Number of messages on electoral violations in regional media six months prior to elections. The results for query “(выборы and (президент Россия)) and (фальсификация or фальсифицировать or вбросы or махинация)”.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_viol3m | Number of messages on electoral violations in regional media three months prior to elections. The results for query “(выборы and (президент Россия)) and (фальсификация or фальсифицировать or вбросы or махинация)”.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_day_viol | Number of messages on electoral violations in regional media on elections day and the following day. The results for query “(выборы and (президент Россия)) and (фальсификация or фальсифицировать or вбросы or махинация)”.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_1mlater_viol | Number of messages on electoral violations in regional media one month after elections. The results for query “(выборы and (президент Россия)) and (фальсификация or фальсифицировать or вбросы or махинация)”.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_6mo_all | Number of all messages in regional media six months prior to elections. The results for the blank query were filtered for the electoral campaign period and regional media.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_3mo_all | Number of all messages in regional media six months prior to elections. The results for the blank query were filtered for the electoral campaign period and regional media.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_day_all | Number of all messages in regional media six months prior to elections. The results for the blank query were filtered for the electoral campaign period and regional media.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |
| elections_year_1mo_all | Number of all messages in regional media six months prior to elections. The results for the blank query were filtered for the electoral campaign period and regional media.| Numeric, years: 2007,2008, 2011,2012,2016,2018,2021 | [Integrum World Wide. Electronic Portal of Russia and the CIS](url) |



 








