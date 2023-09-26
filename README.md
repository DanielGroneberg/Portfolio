# Data Scientist

#### Technical Skills: Python, SQL

## Education
- Data Science Immersive | General Assembly (_September 2023_)</br>								       		
- B.S., Physics	| Western Washington University (_December 2021_)

## Projects
### Timeseries Forecast of Federal Reserve Interest Rates
[Repository](https://github.com/DanielGroneberg/DSI-Project-5)

Developed a timeseries forecast for key economic metrics including Federal Reserve interest rates using **Python**. Scraped 50 years of [Federal Reserve Beige Book transcripts](https://www.minneapolisfed.org/region-and-community/regional-economic-indicators/beige-book-archive) using **BeautifulSoup** and applied natural language processing to engineer sentiment feature from text data. Used a Vector Autoregression model to forecast interest rates.


### Timeseries Forecast of Soil Moisture
![SARIMA Model](/portfolio_assets/img/Sarima_overall.png)

Used **Python** to forecast soil moisture in the United States using 64 years of climate data. Observed distinct shift from stationary soil moisture to decreasing moisture over time around year 2010. This shift took place close to original 80/20 train/test split resulting in an assesment of data as stationary overall which did not hold for test set and subsequent overestimation of soil moisture in the test set. SARIMA and Holt-Winters models both performed poorly with a best R2 score of .42. Applying Holt-Winters additive seasonality model did not see an improvment in performance. Forecasting using only section of data with downward trend (after 2010) resulted in much improved best R2 score of .76

![Bike Study](/assets/img/Sarima_overall.png)


## Work Experience
**Data Scientist @ Toyota Financial Services (_June 2022 - Present_)**
- Uncovered and corrected missing step in production data pipeline which impacted over 70% of active accounts
- Redeveloped loan originations model which resulted in 50% improvement in model performance and saving 1 million dollars in potential losses

**Data Science Consultant @ Shawhin Talebi Ventures LLC (_December 2020 - Present_)**
- Conducted data collection, processing, and analysis for novel study evaluating the impact of over 300 biometrics variables on human performance in hyper-realistic, live-fire training scenarios
- Applied unsupervised deep learning approaches to longitudinal ICU data to discover novel sepsis sub-phenotypes


![Bike Study](/assets/img/bike_study.jpeg)

## Talks & Lectures
- Causality: The new science of an old question - GSP Seminar, Fall 2021
- Guest Lecture: Dimensionality Reduction - Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2021
- Guest Lecture: Fourier and Wavelet Transforms - Scientific Computing (PHYS 5315), Fall 2020
- A Brief Introduction to Optimization - GSP Seminar, Fall 2019
- Weeks of Welcome Poster Competition - UTD, Fall 2019
- A Brief Introduction to Networks - GSP Seminar, Spring 2019

- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA)
