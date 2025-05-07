# Movie Recommendation System

This is a content-based movie recommendation system using TMDB 5000 Movies and Credits datasets. The model recommends similar movies based on movie content features like genres, keywords, cast, and crew.

## Dataset

- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset  
(Sourced from Kaggle)

## Methodology

- Merged movie and credit data
- Created a new feature by combining important content fields
- Processed text using stemming and literal evaluation
- Converted text to vectors using CountVectorizer
- Calculated cosine similarity between vectors to find similar movies

## Sample Output

 
 Top 5 Recommended Movies for 'Avatar':
- Aliens vs Predator: Requiem
- Aliens
- Falcon Rising
- Independence Day
- Titan A.E. 

## Note

This project was done for learning purposes using a Jupyter Notebook environment and focuses only on model building for a movie recommendation system
