# Movie Recommendation Engine
Recommendation engines are now a one of the most common Machine Learning project that can be seen now-a-days.
In fact, some biggest brands are build around one, like  Netflix, Amazon, Google, etc. Thirty-five percent of purchases on Amazon come from product recommendations.

### What Is a Recommendation Engine?

A recommendation engine is a data filtering tool which uses machine learning algorithms to recommend the most relevant items to a user.

It operates on the principle of finding patterns in consumer behavior data, which can be collected implicitly or explicitly.
Netflix uses a recommendation engine to present viewers with movie and show suggestions. Amazon,uses a product recommendation engine to present customers with product recommendations.

In the past, recommendations would come from a salesperson or friends and family.
But today,this is done with the help of algorithms.

### Types of Recommendation Engines

There are three main types of recommendation engines: 
#### 1) Collaborative filtering: 

It focuses analyzing data of user behavior, activities, and preferences, to predict what a person will like, based on their similarity to other users.

#### 2) Content-Based filtering 

It works on the principle that if you like a particular item, you will also like this other item. To make recommendations, algorithms use a profile of the description of an item (genre, product type, color, word length) to work out the similarity of items using cosine and Euclidean distances.  

##### a) Vector based approach
##### b) Classification based approach


#### 3) Hybrid above of the two

A hybrid recommendation engine includes both the collaborative and the content-based data. Because of this, it outperforms both.

#### Will we be discussing content-based filtering vector approach on which this project is based on.

### How does Recommendation Engine (project) works?

#### Step 1) Preprocessing and converting the text to vectors:

##### 1) The primary step is to pre-process dataset to remove stopwords, punctuations, and perform lemmatization to avoid redundancy in data.

##### 2) Now, the available in string format and needs to converted to vectors for generating similarities. For that, pre-trained embeddings of tensorflow are used with suitable dimensions.

#### Step 2) Mathematical measures to determine how similar is a vector to a given vector.
Now, the correlation or similarities between the vector are to be calculated using mathematical algorithms.

Mathematical Similarity metrics used:
1) Cosine Similarity: The Cosine angle between the vectors.
2) Dot Product: The cosine angle and magnitude of the vectors also matters.
3) Euclidian Distance: The elementwise squared distance between two vectors

Using above algorithms, the indices of the vectors sorted on the bases of highest similarity are returned.
These indices are stored in a seperate file .pkl (pickle).

#### Step 4) API Creation (using Flask):

For deployment, API need to be created using Flask or Django.

#### Step 5) Deployment:

The API can be deployed on cloud server like AWS, Heroku, etc. For deployment on Heroku refer to the following link:

https://devcenter.heroku.com/articles/getting-started-with-python#deploy-the-app

## Conclusion:

We have taken a look at the types of filtering mechanisms and their features. 
Also, a complete talk about content-based vector approach of filtering applications with a complete implementation of 
movie recommendation engine.


## Authors

- [Rachit R Jindal](https://github.com/rachitjindal56)

## Tech Stack

**Server:** Python, Pandas,Tensorflow, Sklearn

