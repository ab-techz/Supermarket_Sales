# Supermarket Sales Analysis 

![image_processing20210208-19345-v1dkjh](https://github.com/ab-techz/Supermarket_Sales/assets/142206534/1123dd89-5f42-4960-bdc8-39c8ade86566)



## Introduction

For business proprietors aiming to enhance their sales performance, this initiative holds the potential for significant benefits. The project entails a comprehensive analysis of sales data obtained from a supermarket, with the objective of furnishing recommendations to optimize sales and revenue for the store. These recommendations are systematically organized based on gender and product categories, offering valuable insights into specific areas that can be enhanced to drive improved performance.




## About the Dataset:

- *Invoice ID:* Unique identifier for each invoice.
- *Branch:* The branch where the transaction took place (e.g.,Branch A, Branch B). 
- *City:* The city where the transaction occurred.
- *Customer type:* Indicates whether the customer is a member or a regular.
- *Gender:* The gender of the customer (e.g., Male, Female).
- *Product line:* The category or type of product purchased. 
- *Unit price:* The price of a single unit of the product.
- *Quantity:* The number of units purchased.
- *Tax 5%:* The tax amount (5% of the total price). 
- *Total:* The total amount including tax.
- *Date:* The date of the transaction. 
- *Time:* The time of the transaction. 
- *Payment:* The payment method used for the transaction. 
- *cogs:* Cost of Goods Sold, representing the total cost of the products sold.
- *Gross Margin Percentage:* The gross margin percentage for the transaction. Gross Income: The gross income for the transaction. 
- *Rating:* The customer's rating or satisfaction score for the transaction. These descriptions provide an overview of the information each column contains.








## Insights

![download](https://github.com/ab-techz/Supermarket_Sales/assets/142206534/049fd3c8-e70f-4d6f-86cd-611a7d908890)






- Ratio of Male/Female customers is almost 50-50.
- Branch A has the best performance. Branch C is in the middle almost at power with A. Branch B has the lowest rating among all the branches.
- Average rating of all the branches altogether is around 7. Which is a pretty decent rating and there is scope of improvement.
- Sales by the hour in the company: Most of the items were sold around 14:00 hrs local time followed by 11:00 hrs and 19:00 hrs local time.
- Health and Beauty,Electronic accessories, Home and lifestyle, Sports and travel have a better average quantity sales than Food and beverages as well as Fashion accessories.
- Well, In Health & Beauty, Males are spending much more than Females whereas in Fashion accessories , Food & beverages and Sports & Travel Females are more interested and in the rest there is not much significant difference.
- Fashion accessories & Electronics accessories have less sales as compared to other categories.
- Food and Beverages have the highest average rating
- Home & lifestyle , Fashion accessories have mid ratings
- While Sports and Travel & Electronic accessories the lowest.
- we can see that food and beverages sales usually high in all three branches at evening especially around 19:00
- Most of the customers pay through the Ewallet and Cash Payment while under 40 percent of them pay with their credit card.
   
  E-wallet payment is the most common in Branch A
 
  Cash payment is the preferred in Branch C
 
  Credit card is often used in Branch B
  
- It can be observed that Members are spending more as compared to Normal Customers. Primarily because Members are more regular to shopping and often purchase in bulk. And they are obviously reaping benefits of their membership
- Members have a better average rating.
- Well, Yangon leads at Home & Lifestyle and Electronic accessories.
  
  Naypyitaw leads at Food & Beverages and Fashion accessories.

  Mandalay leads at Sports & Travel and Health & Beauty.


## Recommendations 
![a-guide-to-animated-gifs-in-email-13](https://github.com/ab-techz/Supermarket_Sales/assets/142206534/003fb697-8bc1-4c8a-b4cc-41aa78831903)

- Sales reach maximum at 11:00 hrs, 14:00 hrs and 17:hrs these timings are before work/lunch/after work hours. By offering special offers on Food & Beverages could help boost sales.
- Fashion accessories surprisingly have low sales, new offers can be instilled to attract customers and clear up the stocked up inventory. If there is still no improvement the inflow of these goods should be reduced.
- Ratings for Electronics accessories & Sports travel items are lowest(below 7). Product Quality check could be done for these segments. Accordingly if there are any issues the vendors for these segments could be reconsidered.
- Members spend more as compared to normal customers and have given better ratings. Membership registration could be promoted on a higher rate as this would benefit overall sales and ratings as well.
- For a more Customer centric improvement, The superstore can collect Customer feedback. This would help in improving the overall experience in a better and constructive way.



### Additionally 

I've also applied a Linear Regression model to forecast the ratings. Feel free to review the associated ipnyb file for a more in-depth exploration.



