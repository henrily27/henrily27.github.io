---
layout: splash
title: "Introduction to Machine Learning"
excerpt: "Introduction to Supervised, Unsupervised, and Reinforcement Learning through pictures."
header:
  image: /images/ai_human_hand.jpg
  teaser: /images/ai_human_hand.jpg

---


There are three categories of Machine Learning approarches:
* Supervised Learning
* Unsupervised Learning
* Reinforcement Learning.

The tree below shows the typical business cases under each category.

<div style="width:80%; font-size:80%; text-align:center">
<img src="/images/ML/ML_example.png" style="padding-bottom:0.5em;"/>
Examples Where Machine Learning Apply
</div>  


- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Supervise Learning Process](#supervised-learning-process)
- [Supervise Learning Examples](#supervised-learning-examples)
  - [Weather Prediction](#weather-prediction)
  - [Housing Price and Spam Mail](#housing-price-and-spam-mail)
  - [It's a Bird: Regression vs. Classification](#its-a-bird-regression-vs-classification)
- [Unsupervise Learning Examples](#unsupervised-learning-examples)  
  - [Shopping Behavor: Clustering vs. Association](#shopping-behavior-clustering-vs-association)
- [Supervise vs. Unsupervised Learning Examples](#supervised-vs-unsupervised-learning-examples)
  - [Animals: Classification vs. Clustering](#animals-classification-vs-clustering)
  - [Conceptual: Classification vs. Clustering](#conceptual-classification-vs-clustering)
- [Reinforcement Learning Examples](#reinforcement-learning-examples)
  - [Training a Dog to Fetch a Toy](#training-a-dog-to-fetch-a-toy)



## Machine Learning Algorithms

The same tree shows the different algorithms associate with each category.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/ML_algorithm.png" style="padding-bottom:0.5em;"/>
</div>  


## Supervised Learning Process

In a Supervised Learning process, the model is presented with Train set (a sample input and its desired outputs), and the goal is to learn the rules that maps inputs to outputs.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/ML_process.png" style="padding-bottom:0.5em;"/>
</div>  


## Supervised Learning Examples
### Weather Prediction
Using the same dataset,
* Regression model is trying to answer the question “What is the temperature for tomorrow?” The output is an actual number.
* Classification model is trying to answer the question “Will it be hot or cold?” The output is a category.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/SL_example.png" style="padding-bottom:0.5em;"/>
</div>   
  

### Housing Price and Spam Mail
* To predict the price of a new house listed for sell in the neighborhood, we can use the prices from other houses that were sold recently. The relationship between the number of bedrooms in these sold houses and their sale prices can help predict the sale price for the newly listed house.
* To predict if an email could be spam, we can consider 2 features - Sender Anonymity and Mass Mailing - to classify if a new email could potentially be spam or not.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/SL_example2.png" style="padding-bottom:0.5em;"/>
</div>   

### It’s a Bird: Regression vs. Classification
In this example, using the same dataset, we can either
* Identify if a new image is a bird (or dog, or cat) using Regression, or
* Group these images into categories of birds, dogs, or cats, that a new image can be mapped to, using Classification.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/SL_example3.png" style="padding-bottom:0.5em;"/>
</div>


## Unsupervised Learning Examples
### Shopping Behavior: Clustering vs. Association
* In this example of Clustering, Millenials may prefer online shopping, while Baby Boomers may prefer to go to the stores.
* In this example of Association, people who use Instagram tend to also use Snapchat and Tiktok, and people who buy milk and bread also buy cheese.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/UL_example.png" style="padding-bottom:0.5em;"/>
</div>


## Supervised vs. Unsupervised Learning Examples
### Animals: Classification vs. Clustering
Using the same dataset, we can group the animals into groups of dogs, cats, and birds.
* For Classification approach, the data is labelled, and the model replicates the labeling on new data (new animal image).
* For Clustering approach, the data is not labelled and the model identifies structure as clusters where new data can be assigned to clusters.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/SL_UL.png" style="padding-bottom:0.5em;"/>
</div>

### Conceptual: Classification vs. Clustering
In this conceptual view, we compare the difference between Classification and Clustering.

<div style="width:80%; font-size:80%; text-align:center;">
<img src="/images/ML/SL_UL_2.png" style="padding-bottom:0.5em;"/>
</div>


## Reinforcement Learning Examples
### Training a Dog to Fetch a Toy
<img src="{{ site.url }}{{ site.baseurl }}/images/ML/RL_example.png" alt="RL dog example">

