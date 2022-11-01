# MOVIE-RECOMMENDATION-SYSTEM-USING-ML

### This is an Machine Learning project based on reinforcement learning. The motive is to recommend movies to users based on the movies they have liked or previously watched.
There are two ways to see handle this project.
--> Content Based Recommendation System - Recommending movies based on the content(genre,storyline,plt,etc.)
--> Popularity Based Recommendation System - Recommending movies based on the popularity count among other    &emsp &emsp &emsp &emsp viewers
## WORKFLOW OF THE PROJECT:
![workflow](https://user-images.githubusercontent.com/80580833/199283931-e0b6139d-263b-41f8-add5-2fdd97bd1bcb.png)

## METHODOLOGIES:
For this project, I have used TfidfVectorizer module for feaature engineering and cosine similarity algorithm as the model.
The model works by finding the similarity score of the movie that user had watched with all other movies in the dataset i.e. a CSV file dataset.The movies with high similarity score are then recommended to the user.
![Screenshot 2022-11-01 221913](https://user-images.githubusercontent.com/80580833/199289983-1af57e46-e723-45e1-a96a-76c1930fa618.png)
