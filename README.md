# Predicting the Next Big Book-to-Film Adaptation

# Description
This project predicts the likelihood of books becoming films and finding success on the big screen. 

We answered the question, “Which characteristics of books are strongly correlated to highly grossing, and positively rated book-to-movie adaptations?” The book characteristics that we explored, and hoped would be associated with film success, were book ratings, page counts, book genres, book audiences, and publisher type. 

Overall, we analyzed 45,000 movies released from March 1910 to July 2017, to find that 835 movies were based on novels during that time period. We then performed EDA on 11,128 books via the Goodreads. In our final dataset, we were able to join 105 books and movies based on title. This cleaned dataset was then used for our analysis.

In the movies dataset, film ratings are based on 26 million ratings from 270,000 users from the Official GroupLens website (scale 1-5). In the Goodreads dataset, ratings are based on reviews from the Goodreads API (scale 1-5). Multiple reviews are provided for each book so we calculated ‘average rating per book’ to compare book ratings to movie ratings in our cleaned dataset.


# Team Members
- Ashley Howell Gates (PM)
- Matthew Bishop
- Lauren To
