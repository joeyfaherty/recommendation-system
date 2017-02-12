# recommendation-system

Uses the grouplens 1 million data set [contains 1,000,209 anonymous ratings of approximately 3,900 movies 
made by 6,040 MovieLens users]
https://grouplens.org/datasets/movielens/

To run the recommender on a Spark cluster on AWS EMR:
* package the jar using sbt
* upload the jar and data set to your AWS s3 bucket
* create an EMR cluster including Spark
* copy the jar file and movies.dat to your running EMR cluster you created.
* run the jar using spark-submit MOVIE_ID

** for example Star Wars MOVIE_ID is 260
