# Recommendation-System-for-Ecommerce-websites
This recommendation system uses a dataset of productId of products bought by a particular customer and based on the dataset recommends similar product to another customer.
The principle used here is Item-Item collaborative filtering

This algorithm first finds the similarity score between two items. Based on this similarity score, it then picks out the most similar item and recommends products to the users which have liked or bought the product previously.

1. For predictions we need the similarity between the item u and v.  Here we make use of Cosine Similarity.
2. First we find the items bought by both the users and based on the productID and frequecy of each product, correlation between the Items is calculated.

3. The predictions can be calculated using the similarity values. This algorithm, first of all calculates the similarity between each item and then based on each similarity calculates the predictions. Users having higher correlation will tend to be similar.

![model working](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/05/1skK2fqWiBF7weHU8SjuCzw-768x606.png)
