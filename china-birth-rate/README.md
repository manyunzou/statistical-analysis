<h3>China Birth Rate</h3>

<p align="left">In 2023, China reached a record low birth rate, and its population also fell for a second consecutive year.</p>

<p align="left">Born and raise in China, I was surprised to observe such a news in China. Hence, I am trying to look into the birth rate change and the possible causes behinde the decrease.</p>

<p align="left">Here are all the features I put into my model and where they come from:</p>

- 📄 GDP: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
- 📄 GDP per capita: https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?locations=CN
- 📄 Fertility rate: https://ourworldindata.org/grapher/fertility-vs-child-mortality?time=1962
- 📄 Mortality rate: https://ourworldindata.org/grapher/fertility-vs-child-mortality?time=1962
- 📄 Population: https://ourworldindata.org/grapher/fertility-vs-child-mortality?time=1962
- 📄 Wage and Salaried workers, male %: https://data.worldbank.org/indicator/SL.EMP.WORK.MA.ZS
- 📄 Wage and Salaried workers, female %: https://data.worldbank.org/indicator/SL.EMP.WORK.FE.ZS
- 📄 Labor force participation, %: https://data.worldbank.org/indicator/SL.TLF.ACTI.FE.ZS?locations=CN
- 📄 Birth rate: https://data.worldbank.org/indicator/SP.DYN.CBRT.IN
- 📄 Parental Paid Leave: https://genderdata.worldbank.org/indicators/sh-leve
- 📄 Mean age at first marriage: https://genderdata.worldbank.org/indicators/sp-dyn-smam/
- 📄 Educational attainment: https://genderdata.worldbank.org/indicators/se-cuat-zs/?education=At%20least%20Bachelor%27s%20or%20equivalent
- 📄 GDP inflation prices: https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?view=chart
- 📄 Contraceptive prevelance: https://data.worldbank.org/indicator/SP.DYN.CONU.ZS?view=chart
- 📄 Country Income Classification: https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups

<p align="left">Note that through feature engineering, I notice that many of these features too many missing data to be performed well in the model. I have to eliminate them because of that :( Please let me know if you have found some related datasets! I will keep updating this notebook.</p>