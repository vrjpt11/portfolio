---
title: "Recommender System Development through Collaborative Filtering"
date: 2023-05-16 00:00:00 -0500
categories: [Projects]
tags: [Big Data]
---
I developed a recommender system using the ListenBrainz dataset as a final project for my coursework in __DS-GA 1004 Big Data__, which consisted of 10,258 users and 50 million songs. To create the recommendations, I utilized a popularity baseline model and collaborative-filtering techniques. To improve the system's performance, I employed Spark's ALS (Alternating Least Squares) method, which helped me learn latent factor representations for both users and items. This optimization led to a notable 5.7% increase in recommendation precision.

I incorporated LightFM and fast search techniques to enhance the system's efficiency. By comparing single-machine execution with cluster-based execution, I achieved significant improvements. Specifically, I achieved a remarkable 20.6% reduction in model fitting time and a 30.1% reduction in accuracy calculation time.

Overall, my work on this recommender system involved leveraging the ListenBrainz dataset, utilizing various techniques such as popularity baselines, collaborative filtering, ALS, LightFM, and fast search. These efforts resulted in both improved recommendation precision and reduced execution time, enhancing the overall performance of the system.