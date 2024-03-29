# Business Metrics
A deeper dive into business analytics at UR Dining via machine learning

### Link to page
https://eclevela-1234.github.io/Business-Metrics/

### Draft Workflow
Does Weather affect sales?

Available data thus far – 
4+ years of sales data extracted from company DB.
Corresponding local weather data from that time period
Lat/longs for store location -> not sure how this works in.  
Major challenge – Sales Data is seasonal and also varies based on weekday. Data will need to be normalized. This may be a machine learning problem unto itself 
#### Workflow
-	Do some EDA on Tableau – AGG by day – isolate School vs Break periods
-	Regress on isolated cleaned data by weekday – Train/Test
-	Classification – Spring/Fall, weekday/weekend
Once data has been effectively normalized – explore weather effects 
Other effects – Use machine learning to identify outliers – various inflection points throughout
#### Finalizing
-	Continue building of current webpage – Migrate to Heroku if needed
#### Extras
-	Add other previous planned features to page deployment if time permits 
#### Timeline
-	Complete EDA and Machine learning elements by 9/1
-	Use remaining time to develop webpage deployment and Extras
#### Possible models
-	Random Forest – Day of week, Weekday/Weekend, Spring/Summer, weather
#### Tableau Public Link
- https://public.tableau.com/app/profile/eliot.cleveland/viz/Final-Project_16301719319900/Dailysalesbylocation

#### Works Cited
Machine Learning with Datetime Feature Engineering: Predicting Healthcare Appointment No-Shows
- https://towardsdatascience.com/machine-learning-with-datetime-feature-engineering-predicting-healthcare-appointment-no-shows-5e4ca3a85f96 

Pandas Fiscal Year – Get Financial Year with Pandas
- https://datagy.io/pandas-fiscal-year/

Feature Engineering — deep dive into Encoding and Binning techniques
- https://towardsdatascience.com/feature-engineering-deep-dive-into-encoding-and-binning-techniques-5618d55a6b38
