# Recommendation-System-for-Reordered-Products
Most e-commerce websites are for products with a longer shelf life. Thus, the algorithms used to recommend these types of products differs from the ones that are used to recommend frequently purchased products like FMCG Products. The frequently purchased products have a tendency of reoccurring in multiple purchases of a user. This project is aimed at building a recommendation system for these types of reoccurring products. 

The algorithms used are Weighted Basket Method and Product Transition Probability. The Weighted Basket(Order) Method finds the importance of the user interacted products based on which order number the product was purchased in. If the product was purchased multiple times, the weightage is given according to the recency of the order it was purchased in. The Product Transition Probability calculates the probability of a product reoccurring in the next order given that it was purchased in the previous order. These algorithms together provide a user-specific product recommendation list. This project is conducted on Instacart Online Shopping Dataset.

The algorithms are biuld and tested on 2 datasets:

Dataset 1: The Instacart Online Grocery Shopping Dataset 

Link: https://www.instacart.com/datasets/grocery-shopping-2017

Dataset 2: The Dunnhumby Let’s Get Sort-of-Real Grocery Dataset

Link: https://www.dunnhumby.com/careers/engineering/sourcefiles

These datasets are fit for this project because not only they have multiple user orders and are of high volume but also they have products that
have been reordered multiple times by the users.
