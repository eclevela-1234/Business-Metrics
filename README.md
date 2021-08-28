# Final-Project
A deeper dive into business analytics at UR Dining via machine learning

###Draft Workflow
Does Weather affect sales?

Available data thus far – 
4+ years of sales data extracted from company DB.
Corresponding local weather data from that time period
Lat/longs for store location -> not sure how this works in.  
Major challenge – Sales Data is seasonal and also varies based on weekday. Data will need to be normalized. This may be a machine learning problem unto itself 
####Workflow
-	Do some EDA on Tableau – AGG by day – isolate School vs Break periods
-	Regress on isolated cleaned data by weekday – Train/Test
-	Classification – Spring/Fall, weekday/weekend
Once data has been effectively normalized – explore weather effects 
Other effects – Use machine learning to identify outliers – various inflection points throughout
####Finalizing
-	Continue building of current webpage – Migrate to Heroku if needed
####Extras
-	Add other previous planned features to page deployment if time permits 
####Timeline
-	Complete EDA and Machine learning elements by 9/1
-	Use remaining time to develop webpage deployment and Extras
####Possible models
-	Random Forest – Day of week, Weekday/Weekend, Spring/Summer, weather
-	Tableau - 

