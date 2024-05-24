# OnlineShoppingPurchaseIntention_ML_Model
## 1) Dataset Name :
Online Shoppers Purchasing intentions dataset.
## 2) Business Objective: 
The client is facing the problem of low rate of sales conversion and seeks to increase revenue from its online shopping platform on the basis of the customer’s online activities. Our Main Business objective is to build a predictive model which predicts whether customer intends to make product purchase or not based on his/hers web activity.Real-time predictions in this context can be used to personalize the user experience on the website, if the model predicts that a visitor is likely to make a purchase, the website can offer targeted promotions or recommendations to encourage the visitor to complete a purchase. Conversely, for visitors not likely to make a purchase, the website can provide other relevant content to improve the overall user experience.
## 3) Description of data : 
The dataset has information about the performance of the websites and also all the activities carried out by the customer in the process of purchasing or not purchasing a product, eventually giving the client with a 'Revenue' prediction of true or false. The dataset has 12330 unique sessions collected over a year and 18 features (10 numerical and 8 categorical). Features include "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" which represent the number of different types of pages visited by the visitor in that session and the total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g., moving from one page to another. The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. The value of the "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. The value of "Exit Rate" feature for a specific web page is calculated as as for all pageviews to the page, the percentage that were the last in the session. The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. The "Special Day" feature indicates the closeness of the site’s visit time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with a transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.
## 4) Plan :
My goal is to create a Predictive machine learning model using the dataset to predict whether a potential customer intends to make a purchase or not (predicting 'Revenue' as True or False).
   - Project Steps:  
•	Identifying Best Evaluation metric based on the Business Objective  
•	Data Preprocessing  
•	Developing various machine learning models  
•	Deploying models on test data  
•	Hyperparameter tuning  
•	Selecting the best model based on evaluation metrics  
This predictive model can be deployed in future for real time data to identify potential customers in similar business fields.The predictions from this model can further be used for customer segmentation, Inventory management,Fraud detection and competetive market research.
## 5) Core Source: 
UC Irvine Machine Learning Repository
## 6) Data Provenance: 
The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.  The creators of the dataset are C. Sakar and Yomi Kastro.Dataset was collected by monitoring the website activity of different users from several regions through Google analytics software.
## 7)LinktotheDataset: 
https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset
## 8) Relevant Paper: 
Sakar, C.O., Polat, S.O., Katircioglu, M. et al. Neural Comput & Applic (2018). Link to the paper - https://link.springer.com/article/10.1007/s00521-018-3523-0
