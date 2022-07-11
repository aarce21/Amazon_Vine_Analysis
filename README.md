# Amazon_Vine_Analysis
# Overview
The purpose of this analysis is to evaluate reviews written by Amazon Vine members on various products, the Grocery reviews dataset was utilized for this analysis. Our goal is to determine if there is any bias in the reviews by the members who are paid to leave reviews on products. Using PySpark and Google Colab, the data was read in and we were able to determine the number and percentages of five star feviews left by Amazon Vine customers. 

# Results
The following questions were answered using the Vine dataframe created from the Grocery dataset seen below
![vine_df](https://github.com/aarce21/Amazon_Vine_Analysis/blob/main/images/vine_df.PNG)

1. How many Vine reviews and non-Vine reviews were there?
![total_reviews](https://github.com/aarce21/Amazon_Vine_Analysis/blob/main/images/total_reviews.PNG)

* There were 61 Vine reviews and 28,287 non-Vine reviews 

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? 
![five_star_reviews](https://github.com/aarce21/Amazon_Vine_Analysis/blob/main/images/five_star_reviews.PNG)

* Out of the paid Vine reviews, 20 of them were five stars
* Out of the unpaid Vine reviews, 15,689 were five stars

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![percentage_fivestars](https://github.com/aarce21/Amazon_Vine_Analysis/blob/main/images/percentage_fivestars.PNG)

* 32.8% of the paid Vine reviews were five star reviews 
* 55.5% of the unpaid Vine reviews were five stars 

# Summary 
According to this analysis, bias was not shown by Amazon Vine members when they left their reviews for various grocery products. Out of the total number of reviews, 28, 287 of them were left by non_Vine members and only 61 reviews were left by Vine members. A higher percentage, 55.5%, of the five star reviews were left by non-Vine members while only 32.8% of the Vine members reviews were five star ratings. To further support this, we could run the same analysis on various other catagories to see if Amazon Vine members are more inclined to review and show bias when reviewing other products or if the members just do not find it worth their time to review grocery products. 
