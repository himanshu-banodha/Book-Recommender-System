# Book Recommender System
Welcome to the Book Recommender System! This application provides personalized book recommendations using collaborative filtering and cosine similarity. Additionally, it features a popularity-based recommender system that suggests the top 50 books based on the highest ratings. The front end is built using Flask.

## Demo
![](https://github.com/himanshu-banodha/Book-Recommender-System/blob/main/static/styles/imgs/website.jpeg)

## What is a Recommender System?
A recommender system is a type of information filtering system that seeks to predict the rating or preference a user would give to an item. These systems are widely used in various domains such as movies, music, news, books, research articles, search queries, social tags, and products in general.

## Types of Recommender Systems
1. **Content-Based Filtering:** This approach recommends items similar to those that a user has liked in the past. It uses item features and user preferences to make recommendations. For example, if a user likes movies with certain actors or genres, the system will recommend similar movies.

 2. **Collaborative Filtering:** This method makes recommendations based on the preferences of other users. It assumes that if user A has a similar interest to user B, then items liked by user A might also interest user B. Collaborative filtering can be:

    - **User-Based:** Recommendations are made based on similar users' preferences.
    - **Item-Based:** Recommendations are made based on the similarity between items.

3. **Hybrid Methods:** These combine both content-based and collaborative filtering approaches to improve recommendation accuracy. By leveraging the strengths of both methods, hybrid systems can mitigate the weaknesses of each individual approach.

## About This Project

## Features
* **Collaborative Filtering:** Personalized book recommendations based on user preferences and cosine similarity.
* **Popularity-Based Recommendations:** Suggests top 50 books with the highest ratings.
* **Search Books:** Look up information about any book.
* **User-Friendly Interface:** Simple and intuitive UI built with Flask.

## Recommender System Details
### Collaborative Filtering:
Collaborative filtering recommends books by identifying users with similar preferences. It uses cosine similarity to measure the similarity between users' rating vectors.

* **Cosine Similarity:** Measures the cosine of the angle between two vectors in a multi-dimensional space. In this context, it measures the similarity between users based on their ratings.

### Popularity-Based:
This system suggests the top 50 books with the most ratings. It is a straightforward approach that recommends books based on their popularity.

## Dataset
The book data used in this application is sourced from [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset/data) 

## Installation
To run this project locally, follow these steps:

Clone the repository
```
git clone https://github.com/himanshu-banodha/book-recommender-system.git
cd book-recommender-system
```

Install the required dependencies
Make sure you have Python 3.7+ and pip installed. Then, run:
```
pip install -r requirements.txt
```

Run the app
```
python app.py
```

## Usage
- Open your web browser and go to `http://localhost:5000`
- Enter your book preferences or search for a specific book.
- Get your personalized book recommendations or view the top 50 books.

## Thank You
----

