# Mall-Customer-Segmentation

## Problem Statement

1.	What the problem is?

One of the main task problems of stores is the categorization of their different customers into different groups or clusters. The various categories of customers impact the sales or revenue of the store, both negatively and positively. By identifying the spendthrifts from the misers, we can devise various marketing strategies for each group. We should also note that some groups occur in between this two extremes that needs to be worked on by planning out their own marketing strategy as well. The problem is the handling of influx of customers into the mall. This is a segmentation problem, we categorize the customers into different groups so as to determine which marketing strategy or strategies will apply to each unique group.
Will be applying both K means clustering and Hierarchical clustering to solve this problem.

## Data Collection

2.	How did you get the data?

The data for this project was scrapped from from kaggle and the link is given below :
https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python
It consists of the following five features of 200 customers:

•CustomerID: Unique ID assigned to the customer

•Gender: Gender of the customer

•Age: Age of the customer

•Annual Income (k$): Annual Income of the customer

•Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.

## Data Preparation

3.	How did you prepare the data?

The data preparation involves the stages, ETL – Extract, Transform and Load. Certain columns contain float point, this type of columns were scaled using the MinMaxScaler to scale the values to lie between 1 and 0. The categorical features were transformed to meaningful input using the OneHot Encoder, This is the way via our algorithm can process our data.

## Data Analysis

4.	How did you prepare the data for analysis?
![image](https://user-images.githubusercontent.com/64415804/156753706-6ef28705-a55b-4cd9-909b-e6fe9be0c148.png)

 
5.	Recommendations?
