# Exploratory Data Analysis - Global Terrorism Dataset

The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland. We will analyze the data and draw a meaningful conclusions.

## Dataset Overview
- The dataset has 1,81,691 rows and 135 columns.
- There are no duplicates in the dataset.
- There are many null values in the dataset.
- The values in columns named - Killed, US_CitizensKilled and Wounded which were Null, have been filled with 0.
- The values in columns named - State, TargetSubType, Nationality which were Null, have been filled with Unknown.
- Created a new column named TotalFatalities which is obatained by adding the columns - Killed and Wounded.

## Exploratory Data Analysis
- In the initial years, terrorist activities had been low. It has gradually picked up pace after 2000's.
- Middle Eastern countries, North African countries and South Asian countries are more prone to terrorist activities.
- Private Citizens and their properties followed by military properties are most affected by acts of terrorism.
- Most terrorist activities are done with the help of explosives and firearms.
- Taliban, ISIS or ISIL are responsible for most terrorist activities aorund the world.
- Terrorist groups like Taliban, ISIL, Al-Shabaab became active only after 2000's.
- J&K followed by Assam and Manipur has more terrorist activities than any other state.
- South India(5.9%) is relatively less prone to terrorist activities compared to North India(61.6%).
