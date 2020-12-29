# Web-Scraping-and-Sentiment-Analysis
This is the team project in which my team aims to uncover the primary hotel guest expectations and the overall feelings guests have towards their hotel stay experience during the COVID-19 Pandemic. In addition, we also fit a linear regression model to predict the hotel price as well as find the factors leading to the that price. By understanding this, hotel companies can refine their current processes and standards. Therefore, hotels will additionally improve their reviews and overall ratings and increase occupancy.

The data was collected from and contains data from over 400 hotels in Chicago, Illinois. The Selenium package and XPath Selector were used in Python to access and extract the data.

Project workflow:
1.	Data collection: Using Selenium and Xpath selector, data was extracted from  https://www.hotels.com/. Two datasets were created: hotel_listings and hotel_reviews
2.	Data cleaning: Using Numpy and Pandas to clean data and put it into csv file.
3.	Data transformation: check linear regression assumption and apply log transformation for better distribution before fitting regression. 
4.	Descriptive analysis and modelling: using Scikit-learn to build predictive model
5.	Text mining and Sentiment Analysis

Results:

•	Hotel rating, customer satisfaction rating, number of reviews and hotel capacity influence positively on hotel price.

•	Positive feedbacks related to cleanliness, staff attitudes, on-time service and location near mall and restaurant, free breakfast and parking. 

•	Negative feedbacks regarding to noisy atmosphere and small rooms, delayed services, trash or broken facilities. 

My contribution in this project:
1. Searched and checked quality of reference materials/code for web scraping part and then sent them to team to continuely work on project. 
2. Took full responsibility for listing features analysis including data collection, cleaning, statistical tests, analysis and modelling. 

