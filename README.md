# Online-Shoppers-Purchasing-Intention
Data Science Assignment to aid complete analysis of online Shopping behavior
---

# Background:
The goal is to develop Machine Learning Models to present a complete analysis for online shopping behavior data set.
We will:
1. Build a predictive classification model (ensuring optimal features and classifier). Train the model on data entries corresponding to the months of June-Dec, and test the model on data entries corresponding to Feb-March.
2. Generate user-bahavior clusters based on the purchasing behavior data for the complete dataset.
3. Build a semi-supervised self labelling model to estimate 'Revenue' for the missing records and then fit our classifier. We will assume that for all records from Oct-Dec, the 'Revenue' attribute is missing. 

# Method:
## Dataset:
The data set is from "Online Shoppers Purchasing Intention Dataset Data Set" https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

The goal is to develop Machine Learning Models to present a complete analysis for online shopping behavior data set.
Description of data set:
The data set is "online_shoppers_intention.csv". This data set represents skewed data, such that 84.5% of user journeys did NOT result in a purchase (Revenue=False)

1. The dataset consists of 10 numerical and 8 categorical attributes.
2. The 'Revenue' attribute can be used as the class label.
3. "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. 
4. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another. 
5. The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 
6. The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. 
7. The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page and it represents the percentage that the page was seen in the last session. 
8. The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 
9. The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. 
10. The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.


# Result and discussion:



# Conclusion: