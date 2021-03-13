# Instacart-Basket-Analysis-Prediction
![Fig1](https://github.com/hua-zeng/Instacart-Basket-Analysis-Prediction/blob/main/fig1.jpg)

Figure 1 histogram shows how many orders placed by each of the customers. Clearly, most of the customers placed <=5 orders. 

![Fig2](https://github.com/hua-zeng/Instacart-Basket-Analysis-Prediction/blob/main/fig2.JPG)

Figure 2 indicates that the center of the histogram is around 10 products in the order. The distribution of number products for each order is right skewed. 

![Fig3](https://github.com/hua-zeng/Instacart-Basket-Analysis-Prediction/blob/main/fig3.jpg)

Figure 3 shows the distribution of reorder rate for each of the product. It is left skewed, and the center is near 0.62.

![Fig4](https://github.com/hua-zeng/Instacart-Basket-Analysis-Prediction/blob/main/fig4.jpg)

To predict the market basket, a Light GBM model with a learning rate of 0.1, num_iterations of 1000, max_bin of 100, and num_leaves of 512 was implemented to train and test the data. The model achieved an accuracy of 0.83408 and a binary log loss of 0.245397 for the training dataset showed below.

