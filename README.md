# About the Dataset
The dataset is part of Mercari Price Suggestion Challenge in Kaggle.

There are ~1.5Mil observations in the data set with multiple features. 

# About the challenge
Mercari is like ebay for Japan. Mercari wants a process to predict a price for someone who wants to sell the items on the Mercari ecommerce platform.

# Main features
 - <b>Observation</b> : free text, describing the item sold.
 - <b>brand_name</b> : brand of the item sold
 - <b>category_name</b> : Category of the item sold. these have muliple sub categories under the same feature name.
 - <b>shipping</b> : Whats the shipping cost associated with the item sold.
 - <b>price</b> : label feature. Price of the item sold.

# Approach taken for analysis
Categories were split into sub categories.\
Used NLP on the Description to find the correlation to the price.

# Model used
NLP based

# Visualizations 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/1_price_dist.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/2_brand_name.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/2_1_brand_name_cate.png" height="300" width="500"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/3_category1_bar.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/3_1_main_cate_pie.png" height="300" width="600"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/3_2_item_condi_pie.png" height="300" width="600"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/4_cat1_compar_bar.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/5_cat2_price_bar.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/6_cat2_compare.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/7_name_freq.png" height="300" width="1000"> 

<img src="https://github.com/manoharpavuluri/mercari-NLP/blob/master/photos/8_desc_word_freq.png" height="300" width="1000"> 





