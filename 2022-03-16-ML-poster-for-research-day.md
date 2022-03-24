Introduction:
Based on the background of information explosion on the Internet, filtering users' preferred content from the content library is becoming a more and more critical topic. "content recommendation system" is built for this demand. Here is my developed instance of content recommendation system. It uses the dataset "TMDB 5000 Movies" and a bundle of algorithms to provide a movie recommendation system. Although it has a low complexity structure, its performance is remarkable.

Methods and Materials:
This program extract features from the dataset "tmdb_5000_movies.csv", conduct the prepossessing procedure on every selected feature column. Then merge all the feature of one movie into one line, after that apply algorithm tf-idf to vectorize all the merged feature.