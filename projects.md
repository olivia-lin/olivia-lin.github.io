---
layout: page
title: Projects
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---

### Unlabeled Documents Clustering and Topic Modeling
University of British Columbia, March 2019 - April 2019 <br/>
- Applied unsupervised learning models to cluster unlabeled documents into groups and identified latent topics
- Trained classification models by K-Means clustering and Latent Dirichlet allocation (LDA)
- Tokenized, stemmed and removed stop-words, and extracted features by term frequency-inverse document frequency method for text preprocessing

### AWS Text Data Analytics
University of British Columbia, March 2019 - April 2019 <br/>
-	Applied text analytics on Google Books Ngram dataset to obtain the number of occurrences of specific words by year 
-	Created S3 bucket and used Amazon elastic map reduce (EMR) cluster to reduce the running time of this analysis

### Stock Information Web Scrapping
University of British Columbia, March 2019 - April 2019 <br/>
-	Obtained the time series of stock prices, volume, and technical indicators and created daily, weekly, and monthly plots
-	Created a wrapper in Python to handle the Alpha Vantage API requests to retrieve information of a given stock, which makes working with the API easier

### Course Prerequisite Diagram Web Scrapping
University of British Columbia, March 2019 - April 2019 <br/>
-	Retrieved prerequisite information of each course in MDS program from UBC website using a BeautifulSoup object
-	Created a diagram of all courses with direction arrows pointing from prerequisites to give an overall picture of courses

### Image Processing Package Development
University of British Columbia, February 2019 - March 2019 <br/>
- Developed a Python and an R package that can be used to emboss, compress images, and return dimensional information
-	Applied git version control to manage multi-person project with Agile method and wrote comprehensive test suites
- These packages are open sourced on GitHub that can be found at [BeautyPy](https://github.com/olivia-lin/BeautyPy) and [BeautyR](https://github.com/olivia-lin/BeautyR).

### Handwritten Digits Image Classification
University of British Columbia, January 2019 - February 2019 <br/>
-	Built a supervised model to classify handwritten-digit images from MNIST dataset
-	Implemented a 5-layer convolutional neutral network (CNN) using Keras with 55 million pixels of training data and achieved validation accuracy over 97%

### American IMDB Movie Recommender System and Score Prediction
University of British Columbia, January 2019 - February 2019 <br/>
-	Built a supervised engine to predict scores for unreleased movies and an unsupervised engine to recommend movies
-	Applied linear regression, and multivariate inference to predict movies’ scores, selected and modified predictors by combining stepwise method and Box-Cox transformation and used absolute error for evaluation 
-	Implemented k-Nearest Neighbors (KNN) to find the most similar movies for recommendation, using and comparing both Euclidean distance and cosine similarity 

### Transfer Learning Dog Breed Classification
University of British Columbia, January 2019 - February 2019 <br/>
- Applied a pre-trained animal classification convolutional neural network (CNN) as a starting point, fine-tuned the original CNN, and further built a model to classify dog breed using Keras
-	Increased the model accuracy from 22% to 76% comparing to a scratch CNN model without using transfer learning

### Crime Data Interactive Visualizer
University of British Columbia, January 2019 - February 2019 <br/>
-	Designed and implemented R Shiny app to allow users to interactively use the interface to select a state or city to visualize trends and patterns of different types of crime over time
-	Implemented hover feature, which allows users to hover over the graph to see more details about each data point
-	Published this app online for everyone to use, which can be found [here](https://olivia-lin.shinyapps.io/crime_visualizer/)

### Face Image Dimensionality Reduction
University of British Columbia, January 2019 - February 2019 <br/>
-	Implemented and tuned parameters of principal component analysis (PCA) to extract information from face images under different lighting conditions
-	Reduced dimensionality of each face image from 1024 components to 10 components while still capturing 85% of the information in the image
