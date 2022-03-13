# Kalman-Filter-Covid19-Cases-Prediction

              Team Members: Prateek Kakkar, Aishwarya Saibewar, Swathi Kolar Ravikumar


### Problem Statement

Coronavirus (COVID-19) has recently caused a paramount worldwide concern. As the number of coronavirus cases reportedly increases, the spread of COVID-19 is a pressing threat to global health. As of January 30, 2021, more than 74.2 million people across every state in the United States and its four territories had tested positive for COVID-19.

In this project, we'll try to predict the spread of coronavirus for each of the infected regions by fitting a time series analysis and statistical algorithm to produce the best short term and long-term predictions. An adaptive Kalman filter would be a good approach for one-day prediction for each region as it doesn’t require historical values like a batch estimator and hence it is a recursive estimator. 

The Kalman filter is an algorithm for efficiently performing exact inference in a linear dynamic system where the state space of the latent variables is discrete and all latent and observed variables have a Gaussian distribution. With the assumption that the time series is linear and Gaussian, we will be applying the Kalman Filter to predict the covid 19 spread across US and Washington State counties.


### Data Source:
We’ll use the data set from the COVID-19 GitHub Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. This repository is updated daily and consists of daily case reports – confirmed, deaths and recovery from each country/region in the US.
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series


### Data Files:

This data files used contists of daily time series summary, including confirmed cases and deaths.

*confirmed_cases_us.csv :* US confirmed cases reported at the county level.

*deaths_us.csv :* US confirmed deaths reported at the county level.


### Citations :

Jain, T. (n.d.). Retrieved from OpenGenus IQ: https://iq.opengenus.org/basics-of-machine-learning-image-classification-techniques/

Singh, K. K. (2021). Kalman filter-based short-term prediction model for COVID-19 spread. Appl Intell 51. https://doi.org/10.1007/s10489-020-01948-1, 2714–2726.

Islam et al(2020) Integration of Kalman filter in the epidemiological model: a robust approach to predict COVID-19 outbreak in Bangladesh doi: https://doi.org/10.1101/2020.10.14.20212878

