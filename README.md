
Data was scraped from the official website of  Nigeria centre for disease control via https://covid19.ncdc.gov.ng/ .
This data was analysed to get some insights from it, from the data , the top ten states in terms of confirmed cases are: Lagos , FCT , Kaduna , Plateau , Oyo , Rivers , Edo , Ogun , Kano and Delta. 
The maximum infection rate for a day is 6158 cases , it happened on 22nd December , 2021. 
A regression plot between the Number of cases confirmed and the population density has a Positive slope, this shows that there exist a positive relationship between Number of cases confirmed and the population density. This means that the higher the population ,the higher the number of cases. 
Another regression plot between the Number of cases confirmed and the number of deaths has an almost perfect Positive slope, this means a high degree of relationship exist between the Number of cases and the number of deaths, i.e the higher the number of cases , the higher will be the number of deaths.
An inverse relationship between number of deaths and status of health system, this means that the number of deaths reduces when the health system is better.
Comparing the Q2 GDP of 2019 with Q2 of 2020 , there is a drastic reduction of GDP between the two quarters. Also, Q3 GDP of 2019 and Q3 GDP of 2020 shows that there is reduction in GDP. Since GDP is affected by the rate of overall economic activities in a the country, The Covid-19 pandemic , coupled with the imposition of lockdown and restriction of international and domestic travel, has caused a decrease in GDP between the second quarter of 2019 and third quarter of 2020, this implies that Covid-19 pandemic have negative effect on the GDP of Nigeria.
Summary from the dataframe merged_covid after some columns were calculated and added to it
Considering "the percentage number of confirmed cases" and "the percentage number of deaths" , A new column was created to calculate the percentage confirmed cases of each state to the total number of state, while another column was created for the percentage number of deaths to the total number of death.
•	Lagos State has about 39% of the total confirmed cases , 25%[quarter] of the total deaths.
•	Abuja has about 11% of total confirmed cases and about 8% of the total deaths.
•	Other states also followed a similar trend of having percentage of confirmed cases higher than the percentage death, however , some states such as Rivers , Edo , kano ,Delta,Katsina and some few states have a higher percentage of deaths than percentage confirmed cases.
Also, a new column was created to calculate the number of confirmed cases per million people.
•	Lagos lead with about 7101 confirmed cases per one million persons.
•	Abuja has about 5889 confirmed cases to one million person
•	Plateau followed with 2151 confirmed cases per million,
•	This makes Lagos , Abuja and Plateau state the highest interms of cases confirmed per million.
•	While Kogi state has 1 confirmed case per million , the least confirmed-cases-per-milion

•	The regression plot of number of cases confirmed and the number of deaths shows a positive relationship. That is , The higher the number of cases, the higher the number of deaths. However the lineplots of "percentage number of confirmed cases to total number of confirmed cases" and "Percentage number of death of each state to the overall number of deaths" on the same axis shows a similar trend, but some states such as Oyo , Edo have a disturbing outlier spike in the percentage number of deaths, Kano ,Osun , Imo , Borno also showed spikes in the percentage number of deaths, this is expected to be caused by some other factors.
Insight from Budget Data
The negative impact of Covid-19 on all states in Nigeria is much to the extent that the state with the least decrease in budget, Katsina state, has a reduction in budget to the extent of 31 billion Naira, that is about 13 percent decrease. The list of the first five states most affected by budget reduction due to covid-19 are: Cross-river , Lagos ,Akwa Ibom , Rivers and Ogun State
•	Cross-River was reduced by 952.9 billion Naira ,which is about 87% budget reduction ,
•	Lagos State downwardly revised its budget by 759.5 billion Naira , that is 45.2%reduction,
•	Imo state's budget was reduced by 231.73 billion Naira , which amount to 38.76 % reduction in their budget.

