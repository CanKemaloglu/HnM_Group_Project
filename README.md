# On Progress ... 

# HnM_Group_Project
## Data Description
### For this challenge you are given the purchase history of customers across time, along with supporting metadata. Your challenge is to predict what articles each customer will purchase in the 7-day period immediately after the training data ends. Customer who did not make any purchase during that time are excluded from the scoring.

### Files
#### * images/ - a folder of images corresponding to each article_id; images are placed in subfolders starting with the first three digits of the article_id; note, not all article_id values have a corresponding image.
#### * articles.csv - detailed metadata for each article_id available for purchase
#### * customers.csv - metadata for each customer_id in dataset
#### * sample_submission.csv - a sample submission file in the correct format
#### * transactions_train.csv - the training data, consisting of the purchases each customer for each date, as well as additional information. Duplicate rows correspond to multiple purchases of the same item. Your task is to predict the article_ids each customer will purchase during the 7-day period immediately after the training data period.
#### * NOTE: You must make predictions for all customer_id values found in the sample submission. All customers who made purchases during the test period are scored, regardless of whether they had purchase history in the training data.

#### * link: https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data
