# Spartan Security
Spartan Security is a web application that provides predictive and descriptive analytics of crimes in the Baltimore city. This application is based on a machine learning model that uses expanding window forecasting technique to predict the number of crimes in upcoming week.  In this project we have used the **Victim Based Crime data** and **Census data** from the Baltimore open data website. Using Census data we calculated the population of different police districts in the Baltimore city. By combining the crime data and census data we are predicting the number of crimes per 10k population for the upcoming week.

The application provides interactive maps with filters for different crime types and CCTV camera locations. In addition, descriptive analytics section has charts and map describing crime patterns in Baltimore neighborhoods and police district. The Results page shows results of our model.


To run the web application:
> Navigate to  app folder and run 
``` 
python application.py
```
