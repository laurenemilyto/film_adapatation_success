# Do Book Adaptations Perform Well as Movies?

# Description
Making feature films is a high-risk venture. Studios invest millions of dollars creating the next blockbuster with no way of knowing up-front whether their huge investments will turn a profit.  When deciding whether to fund a particular movie, what are some pieces of information that would help ensure that the film would be successful?  It would help to know that you are investing in a good story, with memorable characters.  Something that will connect with the audience.  Our project explores the relationship between books and movies to answer the question: do book adaptations perform well as movies?  What does the data tell us about how book adaptations perform after being released as movies, and are they reliably better than the average movie?


Overall, we analyzed 45,000 movies released from March 1910 to July 2017, to find that 835 movies were based on novels during that time period. We then performed EDA on 11,128 books via the Goodreads. In our final dataset, we were able to join 105 books and movies based on title. This cleaned dataset was then used for our analysis.  The book characteristics that we explored, and hoped would be associated with film success, were book ratings, page counts, book genres, book audiences, and publisher type.  Using a one-sample t-test, we will test whether movie ratings are significantly different for book adaptations.


In the movies dataset, film ratings are based on 26 million ratings from 270,000 users from the Official GroupLens website (scale 1-5). In the Goodreads dataset, ratings are based on reviews from the Goodreads API (scale 1-5). Multiple reviews are provided for each book so we calculated ‘average rating per book’ to compare book ratings to movie ratings in our cleaned dataset.  


# Team Members
- Ashley Howell Gates (PM)
- Matthew Bishop
- Lauren To
