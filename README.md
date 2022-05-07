# Ensemble-Project
TalkingData mobile advertisements solution

data = talking_data.csv


Detailed data dictionary:
- ip: ip address of click.
- app: app id for marketing.
- device: device type id of user mobile phone (e.g., iphone 6 plus, iphone 7, huawei mate 7, etc.)
- os: os version id of user mobile phone
- channel: channel id of mobile ad publisher
- click_time: timestamp of click (UTC)
- attributed_time: if user download the app for after clicking an ad, this is the time of the app download
- is_attributed: the target that is to be predicted, indicating the app was downloaded

The project: 
- Explores the dataset for anomalies and missing values 
- Encodes date feature
- Divides dataset into training and testing subsets
- Applys XGBoost, Gradient booster and Bagging classifers
- Evaluats the predictions made by the model what is the AUC/ROC score
