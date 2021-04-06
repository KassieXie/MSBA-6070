# MSBA-6070
 Including class assignments and other course related work
 
# CA6 - kNN Based Recommender Engine 

*Background:* 

Given a movies data set, what are the 5 most similar movies to a movie query? 

- Let us build the core of a movies recommender system.


**Goal:** 

*Build A Recommender System*
- building your own movie recommendation website which uses your Recommendation Engine at
the back-end
    - To build this back-end Recommendation Engine specifically

*Dataset:* 
If we worked at Netflix, Hulu, or IMDb, we could grab the data from their data warehouse. Since we
don’t work at any of those companies, we have to get our data through some other means. We could use
some movies data from the UCI Machine Learning Repository, IMDb’s data set, or painstakingly create
our own. In our case, we will use a small sub-set of the data extracted from the UCI’s IMDB data set.


Data File Name: movies_recommendation_data.csv

File Location: https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv
The file location has already been inserted into the codes.

Snapshot of part of the data:
![image](https://user-images.githubusercontent.com/52426579/113661381-f8880000-9673-11eb-8bf8-ce67ecc55740.png)



## Assignment Requirements

Build A Recommender System

    - when we run the KNN algorithm on our data, similarity will be based solely on the included genres and the IMDB ratings of the movies.

    - Imagine a user is navigating your recommendation website, and he/she encounters a movie named “The Post”. The user is not sure if he/she wants to watch it, but its genres intrigue the user; he/she is curious about other similar movies. The user scrolls down to the “More Like This” section to see what recommendations your recommendation website will make, and the back-end algorithmic gears begin to turn.

    - Your website sends a request to its back-end for the 5 movies that are most similar to The Post. The backend has a recommendation data set exactly like ours. It begins by creating the row representation (better known as a feature vector) for The Post, then it runs a program similar to the one below to search for the 5 movies that are most similar to The Post, and finally sends the results back to the user at your website.

    - Information about the movie “The Post”
        - IMDB Rating = 7.2, Biography = Yes, Drama = Yes, Thriller = No, Comedy = No, Crime = No, Mystery = No, History = Yes



## Language 

The programming language: Python 3

The file format: ipynb 
- Any application that can open .ipynb file will be great, but I highly recommend using Google Colab or Ananconda Jupyter Notebook.

The comment and text language: English 

## Packages Installed 
Python packages: 
all sorts of packages including numpy, pandas, sklearn, and so on.

- The codes include installing packages are already embeded in this notebook. It shouldn't have problem if you run my code step by step. 

## Expected Outcome
The expected outcome should already be displayed in the notebook under the codes, but feel free to test the code on your own.

## Logic Behind
K Nearest Neighbor(KNN) is a very simple, easy to understand, versatile and one of the topmost machine learning algorithms. KNN used in the variety of applications such as finance, healthcare, political science, handwriting detection, image recognition and video recognition. 

KNN is a non-parametric and lazy learning algorithm. Non-parametric means there is no assumption for underlying data distribution. In other words, the model structure determined from the dataset. This will be very helpful in practice where most of the real world datasets do not follow mathematical theoretical assumptions. Lazy algorithm means it does not need any training data points for model generation. All training data used in the testing phase. This makes training faster and testing phase slower and costlier.

sklearn.neighbors provides functionality for unsupervised and supervised neighbors-based learning methods. Unsupervised nearest neighbors is the foundation of many other learning methods, notably manifold learning and spectral clustering. Supervised neighbors-based learning comes in two flavors: classification for data with discrete labels, and regression for data with continuous labels.

Other resources related to K-Nearest Neighbors provided by scikit-learn developers can be found at: https://scikit-learn.org/stable/modules/neighbors.html and https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn provided by DataCamp.

## Contributing
Apologize in advance that any pull requests other by the host might be rejected because this is an education repository for personal use. 

Still, welcome to open an issue if you have something want to discuss, or directly contact with me via my email (xxie3@lion.lmu.edu).
