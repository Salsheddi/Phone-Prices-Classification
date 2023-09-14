---
title: "predict phone price |data mining project G3 "
output: html_notebook
---
## Goal :
The objective of this dataset is to leverage data mining techniques such as classification and clustering to develop a predictive model. This model will categorize and estimate the price range of popular phone brands based on their distinctive features. Specifically, the aim is to classify phones into categories such as "expensive," "affordable," or "cheap," taking into account their ongoing manufacturing and the wealth of information contained in the dataset


## Dataset Source :
we took the dataset from kaggle its an online platfrom for data science competitons and collaboration ,offering datasets,computing resources,and a community of data scientists

Dataset URL : https://www.kaggle.com/datasets/berkayeserr/phone-prices

## Dataset Describtion :
The dataset consists of 22 columns(attributes) and 1512 rows


| Attributes name | Describtion | Data type | possible values |
|-----------------|-------------|-----------|-----------------|
|phone_name       |name of the phone|character|1496 possible unique values|
|brand            |brand of the phone|character|Xiaomi Oppo Samsung Vivo Realme|
|os               |operating system of the phone|character|Android 11 Android 10 Android 12 Android 9.0 Android 13|
|inches           |size of the phone screen |numeric |3.5 - 10.5  |
|resoultion       |resoultion of the phone screen|character           |1080x2400 720x1600 1080x2340 1080x2408 720x1520         |
|battery          |battery capacity of the phone|numeric|1500 - 7500| 
|battery_type     |battery type of the phone|character| Li-Po Li-Ion |
|ram(GB)          |ram of the phone as gigabyte|numeric |0 -24                 |
|announcement_date |the date of the announcement of the phone             |character           |1 sep 2016 - 31 Aug 23 |
|weight(g)         |weight of the phone in grams |numeric           |100-500                 |
|storage(GB)      |storage capacity of the phone as GB             |numeric           |0-550                 |
|video_720p       |does phone camera has 720p feature|boolean|TRUE , FALSE                 |
|video_1080p      |does phone camera has 1080p feature       |logical           |TRUE , FALSE                 |
|video_4K         |does phone camera has 4K feature             |logical           |TRUE , FALSE                 |
|video_8K         |does phone camera has 8K feature|logical           |TRUE , FALSE                |
|video_30fps       |does phone camera has 30fps feature             |logical           |TRUE , FLASE                 |
|video_120fps       |does phone camera has 120fps feature             |logical           |TRUE , FALSE                 |
|video_240fps       |does phone camera has 240fps feature             |logical           |TRUE , FALSE                 |
|video_480fps|does phone camera has 480fps feature|logical|TRUE , FALSE|
|video_960fps|does phone camera has 960fps feature|logical|TRUE , FALSE|
|price(USD| price of the phone as USD|numeric |0 - 2400|



.
