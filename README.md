# Ecommerce-product-recommendation-system

Product Recommendation System is a machine learning-based project that provides personalized product recommendations to users based on their browsing and purchase history. The system utilizes collaborative filtering and content-based filtering algorithms to analyze user behavior and generate relevant recommendations. This project aims to improve the overall shopping experience for users, increase sales for e-commerce businesses

## Dataset

I have used an amazon dataset on user ratings for Beauty products. To avoid biases,  each product and user is assigned a unique identifier instead of using their name or any other potentially biased information.

* You can find the dataset here https://www.kaggle.com/datasets/skillsmuggler/amazon-ratings?utm_medium=social&utm_campaign=kaggle-dataset-share&utm_source=linkedin


## Approach

### **1) Rank Based Product Recommendation**
Objective -
* Recommend products with highest number of ratings.
* Target new customers with most popular products.
* Here you can see E_commerce_Product_recommendation_System.ipynb

Outputs -

 .Recommend top 5 products with 50/100 minimum ratings/interactions.
 
Approach -

.Calculate average rating for each product.
.Calculate total number of ratings for each product.
.Create a DataFrame using these values and sort it by average.
.Write a function to get 'n' top products with specified minimum number of interactions.

##*2) Similarity based Collaborative filtering*
Objective -

 .Provide personalized and relevant recommendations to users.
 
Outputs -

 .Recommend top 5 products based on interactions of similar users.

##*3) Model based Collaborative filtering*
   
Objective -

 .Provide personalized recommendations to users based on their past behavior and preferences, while also addressing the challenges of sparsity and scalability that can arise in other collaborative filtering techniques.

Outputs -
 .Recommend top 5 products for a particular user.

