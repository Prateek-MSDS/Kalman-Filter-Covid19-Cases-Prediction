# Kalman-Filter-Covid19-Cases-Prediction

                               Team Members: Prateek Kakkar, Aishwarya Saibewar, Swathi Kolar Ravikumar
	
Problem Statement: Coronavirus (COVID-19) has recently caused a paramount worldwide concern. As the number of coronavirus cases reportedly increases, the spread of COVID-19 is a pressing threat to global health. As of January 30, 2021, more than 74.2 million people across every state in the United States and its four territories had tested positive for COVID-19.

In this project, we'll try to predict the spread of coronavirus for each of the infected regions by fitting a time series analysis and statistical algorithm to produce the best short term and long-term predictions. An adaptive Kalman filter would be a good approach for one-day prediction for each region as it doesn’t require historical values like a batch estimator and hence it is a recursive estimator. 

The Kalman filter is an algorithm for efficiently performing exact inference in a linear dynamic system where the state space of the latent variables is discrete and all latent and observed variables have a Gaussian distribution. With the assumption that the time series is linear and Gaussian, we will be applying the Kalman Filter to predict the covid 19 spread across US and Washington State counties.
