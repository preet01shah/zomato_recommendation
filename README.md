# Zomato Recommendation System
Welcome to my repository for **Zomato Recommendation System**. Below listed are some steps that we did in this project:

## 1. Pre-processing:
The first step began with data preprocessing which included removing non-useful columns, eliminating NA values and changing data types of some useful data according to our needs. An average ratings column was calculated according to the user ratings for each restaurants.

## Model 1
With model 1 we tried to implement a recommeneder according to the price range of the user and recommended it in order of decreasing user rating i.e. higher rated restaurants first.

## Model 2
With model 2 we implemented the algorithm to suggest restaurants based on the dish preference of the user. The dish entered by the user was looked up in all the restaurants where that particular dish was liked. The restaurant was given preference in accordance with the ratings.

## Model 3
The model 3 includes application of NLP concepts. The textual reviews provided by the user were used to extract the similarity between the reviews of one restaurant with the other. This enables user to enter the name of a restaurant of his choice and get recommendations based on it. This step included removing stopwords and urls and creating a *TF-IDF vectorizer* with the help of which the *similarity score* is calculated.

The code present in this repository was implemented on web with the help of a cloud platform ***Heroku*** using open source pyhton famework ***Streamlit***. Below are the snapshots of our deployment:

### Snapshot 1 of first page:
![issue tab](https://github.com/preet01shah/zomato_recommendation/blob/main/ss_deploy/img1.jpeg)

### Snapshot 2 of dropdown menu:
![issue tab](https://github.com/preet01shah/zomato_recommendation/blob/main/ss_deploy/img2.jpeg)

### Snapshot 3 of final recommendations for 'Dhokla':
![issue tab](https://github.com/preet01shah/zomato_recommendation/blob/main/ss_deploy/img3.jpeg)
