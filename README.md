# Comprehensive-Analysis-of-Yelp-Trends-and-Recommendations

## Executive Summary
This Yelp analysis notebook provides a comprehensive evaluation of the situation and trends, with a particular focus on businesses, users, and reviews spanning from 2005 to 2022. The analysis covers various dimensions, including business categories and rating distributions, offering insights into customer satisfaction and business performance. Towards the end of the project, we delved into key findings using Machine Learning techniques in Big Data and presented explanatory visualizations. Based on these findings, it was concluded that classifying businesses and users into various segments can aid Yelp's recommendation system. Additionally, conducting LDA and sentiment analysis on reviews can help businesses improve themselves, leading to the attraction and retention of users.

## Introduction & Motivation
In today's competitive business landscape, customer feedback plays a crucial role in shaping the success of businesses. However, managing tremendous volumes of data poses challenges in extracting actionable insights to enhance services. By leveraging Big Data techniques, our objective is to provide valuable insights for businesses in several ways. Firstly, we aim to identify businesses that are either liked or disliked by customers by analyzing features such as 'stars' and 'review_count'. Secondly, we aim to discern common compliments and complaints from users by conducting sentiment analysis on reviews. Lastly, we will offer suggestions on how businesses can attract more customers and increase brand exposure.

## Data Description + Data Source
The Yelp dataset consists of 5 JSON files: buiness, checkin, review, tip, and user, covering 150,346 businesses and 6,990,280 reviews. Of particular interest is the business table, which contains over 1.2 million business attributes including hours, parking availability, and ambience. Upon merging with the review table, the resulting table will comprise roughly 6 million rows and require about 8 GB of storage space.

Source: https://www.yelp.com/dataset/documentation/main
