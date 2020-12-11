# LightGBM-model-for-gift-price-prediction-hackerearth
# Problem statement
One of the main goals of online retailers is to increase the desirability and the value of the products. To achieve this goal, various promotional techniques are planned. Among these techniques, offering promotions and special offers to the customers is an effective method of driving ancillary traffic to the site, acquiring new customers, and growing the revenue. These advancements can likewise be utilized to encourage new visitors to become loyal customers.  

An online retailer has launched a special sale of gifts for the Good Friday event. They have approached you to build a model that helps them to set the prices for their gifts. The data provided is a combination of multiple categories and dates related to gifts.  

However, based on these certain features you are required to build a model that can predict the prices of the different packages.  

# Data
The dataset consists of the following columns:  

# Data description    # Column	Description  
gift_id	                Unique ID of gift  
gift_type	             Type of gift (clothes/perfumes/etc.)  
gift_category	          Category to which the gift belongs under that gift type  
gift_cluster	          Type of industry the gift belongs  
instock_date	          Date of arrival of stock  
stock_update_date	      Date on which the stock was updated  
lsg_1 - lsg_6	           Anonymized variables related to gift  
uk_date1, uk_date2	     Buyer related dates  
is_discounted	           Shows whether the discounted is applicable on the gift  
volumes	                 Number of packages bought  
price	                    The total price  
The data folder consists of the following two .csv files:  

train.csv - ()  
test.csv - ()  
The sample_submission is described as follows:  

gift_id,price  
GF_11156,175.54  
GF_11157,90.4  
GF_11158,102.0  
GF_11159,130.05  
Note: To avoid any discrepancies in the scoring, you must ensure that all the gift_id column values in the submitted file match the values in test.csv provided.  
