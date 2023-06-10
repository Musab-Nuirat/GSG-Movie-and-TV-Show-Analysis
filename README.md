# GSG-Movie-and-TV-Show-Analysis
Explore and analyze a dataset of top movies and TV shows using pandas. Clean, preprocess, and extract insights such as the most popular genre and the director with the most top-rated movies/TV shows. Gain valuable insights into the dataset and showcase the power of pandas for data manipulation and exploration.


# Analysis Report: Top Movies and TV Shows
# Data Cleaning and Preprocessing

We began by cleaning and preprocessing the data. We removed unnecessary columns, such as Poster_Link, Released_Year, Certificate, Runtime, Overview, Meta_score, Star1, Star2, Star3, Star4, No_of_Votes, and Gross. These columns were not relevant to our analysis. We also handled missing values by dropping rows with missing values.

# Most Popular Genre

To identify the most popular genre of movies and TV shows, we analyzed the Genre column. As some entries had multiple genres separated by commas, we split the column to separate the genres. We then used the value_counts() function to count the occurrences of each genre. The genre with the highest count was determined to be the most popular genre.

# Insight

The most popular genre among the top movies and TV shows in the dataset is Drama.

# Director with the Most Top-rated Movies/TV Shows

We further analyzed the Director column to identify the director with the most top-rated movies/TV shows. We counted the occurrences of each director and found the director with the highest count.

# Insight

The director with the most top-rated movies/TV shows among the dataset is Sidney Lumet.

# Findings and Conclusion

Based on our analysis, we discovered that Drama is the most popular genre among the top movies and TV shows in the dataset. This indicates a strong preference for dramatic storytelling among the audience. Additionally, Sidney Lumet stands out as the director with the most top-rated movies/TV shows, showcasing his exceptional talent and contribution to the film industry.

It is important to note that this analysis is based on the provided dataset, and the findings are limited to the scope of the dataset itself. Further analysis and exploration can be done to gain deeper insights into other aspects of the data, such as ratings, cast, and release years.

Overall, this analysis provides valuable insights into the top movies and TV shows, highlighting the popularity of drama as a genre and recognizing the outstanding work of Sidney Lumet as a director.
