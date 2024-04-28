# Final Project Proposal

## Project title

Analysis of Amazon Marketplace Products

### Authors

Annie Lu al0907@uw.edu
### Date

May 1
Spring 2024
## Abstract

Our main question is "How are the ratings of a product on Amazon correlated with the price of the product?" This question is important because as consumers generally prefer lower priced items, we want to determine if there is any correlation between items with a lower price point and the satisfaction of consumers, whether it be due to quality, uses, and so on. To address the question, we will conduct research in RStudio using R in order to see if there are any relationships between a product and its rating.

We are concerned with how customers rate products, because a rating determines essentially what the customers liked and disliked about a specific product. To address this concern, we plan to take the ratings of the products, and through our findings, uncover the reviews behind the rating for these products, to get a deeper insight into why customers rated the product the way they did (looking for keywords). Then, to tie this information back to the research question, we will be making inferences about the ratings and the price point of the items based off the reviews.

Consider that the data only has ratings of products, and the ratings are averaged for each product. This is important because we do not know the spread of the ratings for the products, and we are missing key words that reviews would give us regarding what customers think about the product. Accordingly, we plan to do our analysis by first separating the products by category, then investigating the correlation between price and rating, and then, looking up the product given the URL in order to observe the distribution of the ratings and do more analysis regarding the distribution and the keywords from the reviews of the product.

## Keywords

Keywords: Amazon, online marketplace, ecommerce, business, product sales

## Proposal

1. Introduction  

This study aims to investigate the relationship between the price of a product sold on Amazon, and its rating. The results from this study will be used to drive design decisions for what types of products businesses on Amazon should release in order to leave consumers satisfied with both price and condition/usefulness/durability of a product.

1. Which categories have the best selling Amazon products?
- This question is asked in order to find out which categories have the highest number of sales and best-selling products (denoted by a boolean).This question is important because we want to find out which categories have a lot of sales first, so we can compare ratings and their prices within each category to narrow our research scope.

2. Which Amazon product(s) have the most sales?
- This question is asked in order to find which Amazon products overall have the highest number of sales. This question is important because after finding the categories with the best selling Amazon products, we want to find individual products in order to research them specifically and read reviews to connect them to the rating the reviewer gave.

3. What are the cheapest/most expensive products sold on Amazon?
- This question is asked in order to gauge pricing of a product on Amazon. This question is important as it is an exploratory glimpse into what items are priced higher or lower, so we can research the individual products and read reviews to connect them to the rating the reviewer gave.

4. What is the average price of products in per category on Amazon?
- This question is asked in order to gauge pricing of a product within a category on Amazon. This quesiton is important because we want to get a sense of which categories of products will have cheaper items, and which will have more expensive items.

5. How are ratings of a product on Amazon correlated with the price of the product?
- This question is asked as our main research question. This question is important because we want to investigate the products where the price of an item where it is cheap enough to satisfy consumers, yet also good enough to encourage the customer to leave a good review, in order to give insights for businesses on Amazon on how they should design their products to reach this balance point between price and satisfaction.


2. Related Work  

> Describe your topic and related work in this space. You must include 3 citations to related work (URLs to similar work, high quality articles from the popular press, research papers, etc. ) Please use a standard citation style of your choice. (at least 200 words)

There has been a lot of research done for what products are best-selling on Amazon.

This first research project on Kaggle (https://www.kaggle.com/code/ksevta/best-products-to-sell-on-amazon) is...

This second... (https://www.helium10.com/blog/top-selling-items-on-amazon/)

Finally... (https://www.sellerapp.com/blog/best-selling-products-on-amazon/)

While these three articles covered, this project proposal aims to uncover a new scope...

3. The Dataset

I found the data on Kaggle. It was one of the recommended datasets when I looked for datasets related to e-commerce. The dataset can be found at https://www.kaggle.com/datasets/asaniczka/amazon-products-dataset-2023-1-4m-products/data?select=amazon_products.csv.

The person that collected the data was a user named ASANICZKA.

The data from the csv files were scraped from Amazon.com.

The data was collected in order to get an in-depth idea of what products sell best, which SEO titles generate the most sales, the best price range for a product in a given category, and much more.

Rows: 1426337

Columns: 11 in amazon-products.csv

Ethical questions: What permissions are needed to use this dataset for analysis? What permissions did the owner get to scrape this data from Amazon? Are there are permissions that must be obtained before proceeding with this analysis?

The limitations/problems with this dataset are that first, it does not have the reviews of a product given, only the rating. The reviews would be very useful for this project as they have key words that, when analyzed, could discover issues and satisfactory parts of the product that the customer bought, depending on if they left a good or bad review. Second, the rating appears to be averaged, as there is only one rating for each product, and not a distribution of 1-5 star ratings, so this has to be accounted for because the average may not account for, a 1-star rating when majority are 5-stars for example.

4. Implications

The implications of this project will be that business owners on Amazon can use these guidelines in order to determine what products to sell and if they are currently selling items, they can use the results of this project to determine how to improve the designs of their products to make customers satisfied. Designers of these products can take into account how the ratings and price points of the products relate in order to meet business needs. These business needs may involve changing the features of a product, lowering cost, etc., all which industrial designers play a part in. Companies will have to consider how to create balance between cost and functionality in order to not only keep their existing customers, but encourage new ones to buy their product. The findings from this project may help drive that. Overall, the results of this project mainly aim to improve business on Amazon for sellers and their products. 

5. Limitations & Challenges
>What challenges or limitations might you need to address with your project idea more broadly? Briefly discuss. (at least 150 words)

While this project covers...