# Demographic_Prediction

## Objectives 
to build a model predicting users’ demographic characteristics based on their app usage, geolocation, and mobile device properties. Doing so will help millions of developers and brand advertisers around the world pursue data-driven marketing efforts which are relevant to their users and catered to their preferences.

## File descriptions (just sample data, the full data is too big)
### gender_age_train.csv, gender_age_test.csv 
- the training and test set group: this is the target variable you are going to predict.
### events.csv, app_events.csv 
- when a user uses TalkingData SDK, the event gets logged in this data. Each event has an event id, location (lat/long), and the event corresponds to a list of apps in app_events.
### timestamp: 
when the user is using an app with TalkingData SDK.
### app_labels.csv 
- apps and their labels, the label_id's can be used to join with label_categories
### label_categories.csv 
- apps' labels and their categories in text
### phone_brand_device_model.csv 
- device ids, brand, and models
### phone_brand: 
note that the brands are in Chinese (translation courtesy of user fromandto) 
