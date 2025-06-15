# 🇮🇳 Macroeconomic Analysis of India
A comprehensive macroeconomic analysis of India using data science tools. This project explores the relationships between various economic indicators and critically examines classical economic models in the Indian context.

## 📚 Data Sources
The data used in this project has been sourced from credible Indian government and international websites, including:
- MOSPI (Ministry of Statistics and Programme Implementation)
- RBI (Reserve Bank of India)
- World Bank Open Data
- Trading Economics
- UNData

## 🎯 Aim
To evaluate the Indian economy using key macroeconomic variables and assess the relevance of classical economic theories such as Okun's Law, Phillips Curve, and the relationship between GDP and inflation in the Indian context.

## ✅ Objectives
- Collect and clean macroeconomic data relevant to India.
- Conduct exploratory data analysis (EDA) on selected indicators.
- Visualize trends and correlations using Python.
- Evaluate the applicability of macroeconomic models.
- Derive actionable economic insights from the data.

🧾 Dataset Columns
The analysis involves the following 17 economic indicators:
- year
- population
- inflation
- gdp_per_capita
- gdp_growth_rate
- unemployment
- life_expectancy
- trade_balance
- personal_remittance
- lending_interest
- gov_debt
- fdi_inflows
- fdi_outflows
- labour_force_participation
- external_balance_of_goods_and_services
- current_acc_balance
- exchange_rates
- fiscal_data
Each column represents time-series data for the Indian economy over multiple years.

## 🛠️ Technologies Used
- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib & Seaborn for data visualization
- Jupyter Notebook for interactive analysis

## 📸 Visualizations
### Trend analysis

<img width="300" alt="Screenshot 2025-06-15 at 8 37 01 PM" src="https://github.com/user-attachments/assets/1daf1dc6-7ae3-4dc7-8a95-3fe8bef5d326" />

<img width="300" alt="Screenshot 2025-06-15 at 8 36 27 PM" src="https://github.com/user-attachments/assets/6630fe3c-0657-4907-b959-6c5aaac2d5d4" />

<img width="300" alt="Screenshot 2025-06-15 at 8 36 05 PM" src="https://github.com/user-attachments/assets/ee9293ad-9cdf-46ad-9461-0355dfbbeb94" />

<img width="300" alt="Screenshot 2025-06-15 at 8 35 51 PM" src="https://github.com/user-attachments/assets/d7be286b-b7b5-449b-b8f5-560311f81b30" />

<img width="300" alt="Screenshot 2025-06-15 at 8 35 40 PM" src="https://github.com/user-attachments/assets/8d225d69-7b1e-4512-9043-81faf8664fce" />
<img width="300" alt="Screenshot 2025-06-15 at 8 35 05 PM" src="https://github.com/user-attachments/assets/19cfa5f4-f7fc-4d90-9db9-591dd25be542" />

<img width="300" alt="Screenshot 2025-06-15 at 8 34 54 PM" src="https://github.com/user-attachments/assets/8ce7cd75-2e4e-46af-ab5e-ff066a28f44b" />

#### Inflation
- Inflation shows a **cyclic** trend.
- Significant peaks occured in
    - **1991**: The Indian Economic crisis and India was still recovering from The great inflation 1965 to 1982.
    - **1998**: due to a sharp increase in the prices of agricultural products.
    - **2009** and **2013** : due to the great depression which caused a spike in international oil prices and rise in prices of primary commodities.
    - **2020** and **2022**: due to COVID-19 pandemic.
- Significant dips occuring in
    - **1993**: India recovering from The great inflation with decreasing prices of primary commodities.
    - **1999 to 2005**: Due to abundant agricultural harvest and increased import competition.
    - **2011**: Due to decrease in international crude oil prices and primary commodities.
    - **2015**: Decrease in prices of manufactured products due to the Launch of **Make in India** campaign.
    - **2017**: Introduction of Goods and Service Tax (GST)
    - **2021**: Post pandemic there wa a focus on improving supply chain efficiency and the government also released buffer stocks to relieve the prices.
    - **2023**: Drop in energy and commodity prices.
      
#### GDP Per Capita
- Per Capita GDP shows a **moderate upwards** trend from 1991 to 2002 and a **linear** trend from 2003 to 2023.
- The spike from 2003 was influenced by increased private investment, rising savings, and substantial foreign capital inflows.
- India experienced a slight dip in 2020 due to COVID-19 pandemic

#### GDP Growth Rate
- GDP growth rate also follows a **cyclic** trend with a drastic dip in 2020.
- spike in growth rate occured in
    - **1996**: due to recovery in agricultural and industrial sectors.
    - **1999**: due to strong performance across several key sectors, including manufacturing, electricity, gas & water supply, etc. that were fueled by agricultural recovery.
    - **2003 to 2007**: was fueled by a capital expenditure (capex) boom.
    - **2010**: due to strong growth in the services sector.
    - **2016**: strong domestic demand and consistent government spending.
    - **2021**: due to government policies like "Make in India" and "Production Linked Incentive (PLI)" scheme and increased foreign direct investment.
- Dips in growth rate occured in
    - **1997**: the Asian financial crisis.
    - **2000 to 2003**: due to the Asian financial crisis, a drought, the Pay Commission award, the IT bust, and the global recession of 2001.
    - **2008**: The great Recession.
    - **2011**: Weak manufacturing activity, rising costs and higher than bugdeted expenditure.
    - **2020**: COVID-19 pandemic.

#### Unemployment
- Unemplyoment has a relatively stable trend over the years 1991 to 2018.
- In 2018, the labour force participation increased and the govenment also implemented various schemes like Pradhan Mantri Kaushal Vikas Yojana (PMKVY), Craftsmen Training Scheme at ITIs, and PM Vishwakarma to promote decrease in unemployment.
- In 2020, due to the pandemic there was a rise in unemplyment, but India recovered and unemployment continued to decrease from 2021.

#### Life Expectancy
- Life expectancy mostly followed a linear trend, except for a decrease in 2020 due to COVID-19 pandemic.

#### Government Debt
- Government debt significantly increased during
    - The Indian economic crisis(1991)
    - energy crisis (2003 - 2009)
    - the COVID-19 recession.

### Bivariate Analysis
#### Development vs Growth
<img width="935" alt="Screenshot 2025-06-15 at 8 46 49 PM" src="https://github.com/user-attachments/assets/3d755539-cc79-417f-9430-4c7e99e76353" />

Life Excpectancy vs gdp per capita and Population vs Gdp per capita have a positive correlation which means with growing population gdp and life expectancy also grows.
On the other hand, with the rise in labour force participation the gdp decreases for India.

#### Investment And Capital Flow
<img width="937" alt="Screenshot 2025-06-15 at 8 46 07 PM" src="https://github.com/user-attachments/assets/aba700ff-f67f-4ac6-9d49-bf9bb7fde312" />

India has increasing foreign direct investment inflows and outflows with the increase in GDP which helps the growth of long-term inverstments.
However, the increasing foreign direct investments affect the conversion rate from INR to USD, reducing the INR currency value in the international market.

#### Fiscal & Monetary Dynamics
<img width="934" alt="Screenshot 2025-06-15 at 8 46 27 PM" src="https://github.com/user-attachments/assets/347eb14c-3d43-4a41-a656-cc3ecf25fbb7" />

the governmet debt shows high volatitly, which shows significant spikes at times of crisis.
inlfation has a high dispersion and has a slight positive relation with fiscal data however it is not enough to derive any insights.

#### External Sector Health
<img width="935" alt="Screenshot 2025-06-15 at 8 47 24 PM" src="https://github.com/user-attachments/assets/be4d8733-5f0e-4364-b0d1-e777fff55eb3" />

external balance of goods and service is slightly negatively correlated to the gdp growth rate of the country.
exchange rates have a linear relationship with personal remittance, that means the higher the currency exchange rate the more profit India will make gettting USD back to INR.


### Multivariate Analysis
<img width="937" alt="Screenshot 2025-06-15 at 8 59 14 PM" src="https://github.com/user-attachments/assets/2de08d66-4adf-428f-a405-f50804604296" />

Strong Positive Correlations (r ≥ 0.7):
- year - gdp_per_capita: 0.97
- year - life_expectancy: 0.98
- gdp_per_capita - life_expectancy: 0.94
- gdp_per_capita - exchange_rates: 0.93
- gdp_per_capita - fiscal_data: 0.93
- fdi_inflows - fdi_outflows: 0.81
- life_expectancy - personal_remittance: 0.72

Strong Negative Correlations (r ≤ -0.7):
- year - lending_interest: -0.89
- year - labour_force_participation: -0.80
- gdp_per_capita - labour_force_participation: -0.86
- life_expectancy - lending_interest: -0.88
- exchange_rates - lending_interest: -0.85
- gdp_per_capita - lending_interest: -0.79
- personal_remittance - lending_interest: -0.73

Moderate Positive Correlations (0.5 ≤ r < 0.7):
- year - personal_remittance: 0.69
- gdp_per_capita - fdi_inflows: 0.52
- personal_remittance - exchange_rates: 0.59

 Moderate Negative Correlations (-0.7 < r ≤ -0.5):
- year - unemployment: -0.52
- year - trade_balance: -0.50
- year - external_balance_of_goods_and_services: -0.50
- population - lending_interest: -0.90
- inflation - lending_interest: -0.50
- life_expectancy - trade_balance: -0.54
- life_expectancy - labour_force_participation: -0.79
- personal_remittance - external_balance_of_goods_and_services: -0.68

### Empirical And Theoretical Models
#### Okun's Law
<img width="200" alt="Screenshot 2025-06-15 at 9 01 44 PM" src="https://github.com/user-attachments/assets/2b45e935-1c9a-45b6-9646-2f6cbb471d88" />
<img width="200" alt="Screenshot 2025-06-15 at 9 02 04 PM" src="https://github.com/user-attachments/assets/6979d023-cdac-4aaa-9c7d-a1c023d7a3ba" />
<img width="200" alt="Screenshot 2025-06-15 at 9 02 18 PM" src="https://github.com/user-attachments/assets/a7706317-f311-4869-ad35-585057cfda0c" />
<img width="200" alt="Screenshot 2025-06-15 at 9 02 31 PM" src="https://github.com/user-attachments/assets/77a79b3f-ea04-43e1-8125-8ed471119b4c" />
<img width="200" alt="Screenshot 2025-06-15 at 9 03 03 PM" src="https://github.com/user-attachments/assets/dab22cfa-cea5-4aaf-bce3-5b3426c64b3a" />

Okun's law states that growth rate and unemployment rate have a high negative correlation i.e. When unemployment falls, GDP tends to rise — and vice versa.
- For India's case the validity of okun's law goes as follows:
    - 1991-1996: negative correlation (follows)
    - 1997-2002: near to no correlation (does not follow)
    - 2003-2008: negative correlation (follows)
    - 2009-2014: near to no correlation (does not follow)
    - 2015-2020: negative correlation (follows)

Hence we conclude that Okun's Law is only partially valid for Indian economical trends.

#### Phillips Curve
<img width="200" alt="Screenshot 2025-06-15 at 9 03 37 PM" src="https://github.com/user-attachments/assets/8dedbb62-6e74-4d02-9ebd-b919d63e3733" />
<img width="200" alt="Screenshot 2025-06-15 at 9 03 48 PM" src="https://github.com/user-attachments/assets/cee713ad-b925-4b7d-9372-2643b7de8377" />
<img width="200" alt="Screenshot 2025-06-15 at 9 03 59 PM" src="https://github.com/user-attachments/assets/aefe2f80-1b22-4c7a-be28-8374af1d1268" />
<img width="200" alt="Screenshot 2025-06-15 at 9 04 10 PM" src="https://github.com/user-attachments/assets/f365841f-eada-4c32-bb07-fc777d18fd63" />
<img width="200" alt="Screenshot 2025-06-15 at 9 04 22 PM" src="https://github.com/user-attachments/assets/1f81b3dc-366e-4059-9795-ca7ffeea99fb" />

The Phillips curve states that inflation and unemployment have an inverse relationship; higher inflation is associated with lower unemployment and vice versa.

- For India's case the validity of Phillips Curve goes as follows:
    - 1991-1996: weak negative correlation (follows)
    - 1997-2002: weak positive correlation (does not follow)
    - 2003-2008: weak negative correlation (follows)
    - 2009-2014: positive correlation (does not follow)
    - 2015-2020: positive correlation (does not follow)

Hence we conclude that Phillips Curve is only weakly and inconsistently valid for Indian economical trends.

#### Aggregate supply curve
##### SRAS
<img width="200" alt="Screenshot 2025-06-15 at 9 04 56 PM" src="https://github.com/user-attachments/assets/2a42c010-5eb8-4c3c-b61f-e4b2ffd55517" />
<img width="200" alt="Screenshot 2025-06-15 at 9 05 12 PM" src="https://github.com/user-attachments/assets/740fcb69-a207-450f-9579-ce21155a331f" />
<img width="200" alt="Screenshot 2025-06-15 at 9 05 24 PM" src="https://github.com/user-attachments/assets/fff49735-8336-4d14-9e86-83536f96c9ff" />
<img width="200" alt="Screenshot 2025-06-15 at 9 05 35 PM" src="https://github.com/user-attachments/assets/e0182e01-2e0d-432d-84fe-748a5885e894" />
<img width="200" alt="Screenshot 2025-06-15 at 9 05 47 PM" src="https://github.com/user-attachments/assets/b6a5e261-65be-416c-8158-58cfd53bdced" />

##### LRAS
<img width="350" alt="Screenshot 2025-06-15 at 9 06 24 PM" src="https://github.com/user-attachments/assets/7846d181-bfe0-409e-a500-f055afc69560" />

Aggregate supply is the total amount of goods and services produced at a specific price point for a particular period. 
GDP and inflation are usually positively correlated.
**Short-term** 
- 1991-1996: slight positive correlation (follows)
- 1997-2002: negative correlation (does not follow)
- 2003-2008: positive (follows)
- 2009-2014: slight positive correlation (follows)
- 2015-2020: negative correlation (does not follow)

**Long-term**
- slight negative correlation

In conclusion, Aggregate supply curve is weakly valid for short term but not valid for long term.


## 📌 Key Insights
- GDP per capita is strongly correlated with life expectancy, exchange rates, and fiscal indicators.
- Lending interest rates show strong negative correlations with multiple development metrics.
- Inflation is weakly correlated with most other indicators, suggesting complexity in policy outcomes.
- Classical models such as Okun’s Law and Phillips Curve have limited predictive power in India.

## 🧠 Theoretical Background
### 🔸 Okun’s Law
A macroeconomic theory that postulates an inverse relationship between unemployment and GDP growth. If GDP rises, unemployment falls.
Finding: The relationship is weak in India, possibly due to structural unemployment and informal labor.

### 🔸 Phillips Curve
Suggests an inverse relationship between inflation and unemployment.
Finding: This trade-off is not clearly observed in India’s data, indicating influence from supply-side and external factors.

### 🔸 GDP vs Inflation
Typically, moderate inflation is considered a byproduct of a growing economy, especially demand-pull inflation.
Finding: In India, inflation and GDP show weak to no correlation, hinting at non-demand factors like cost-push inflation and fiscal inefficiencies.

## 📌 Conclusion
This project provides a quantitative lens to understand India's economic dynamics. The findings reveal that while some classical theories hold ground in certain periods, India’s economic landscape is nuanced and driven by multiple, often non-linear, forces. 
