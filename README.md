![image](https://i.pinimg.com/originals/86/13/02/861302679501d1c6e037fdc7d17ec756.jpg)

## Table of Contents
   =================

  1. [Background](#background)
  2. [About This Project](#about)
       - [Technologies & Methods](#technologies)
       - [Preview](#preview)
       - [Results](#results)
       - [Source Data:](#source)
  3. [Presentation](#presentation)
  4. [Contributors](#contributors)

## Background 
Making feature films is a high-risk venture. Studios invest millions of dollars creating the next blockbuster with no way of knowing up-front whether their huge investments will turn a profit. When deciding whether to fund a particular movie, what are some pieces of information that would help ensure that the film would be successful? It would help to know that you are investing in a good story, with memorable characters. Something that will connect with the audience. 

<img src="https://m.media-amazon.com/images/M/MV5BNWIwODRlZTUtY2U3ZS00Yzg1LWJhNzYtMmZiYmEyNmU1NjMzXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_.jpg" width=300 align=center>

Our team loves reading, and we also enjoy films. In this project, we explored the relationship between books and movies to answer the question: do book adaptations perform as well as movies? What does the data tell us about how book adaptations perform after being released as movies, and are they reliably better than the average movie?

## About This Project
To analyze the success of book adaptations, we performed EDA on over 45,000 films from March 1910 to July 2017 using a dataset originating from the TMDB Open API. In this dataset, there were 829 films based on novels. To extract insights on the books themselves we combined this data with Goodreads data such as book publisher, page count, and book rating. Matching the two datasets on ‘title’, 105 matching movies and books resulted that were used in this analysis. 

## Technologies & Methods
- Python
     - Pandas
     - Matplotlib
     - Scipy
- Data Visualization
- Statistical Inference
- Linear Regressions, One-Tailed T-tests, Shapiro–Wilk Test & ANOVA
     

## Preview


## Results

   1. Book to film adaptations have higher ratings than most films - True
 
<img src="https://user-images.githubusercontent.com/75763314/132149924-41c355d4-b4e3-4268-ad7f-204761d4c9e2.png" width=500 align=center>
Looking at the scatter plot, the sample is a good representation of the population, although the sample ratings are primarily between 5 & 10, whereas the population ratings have a much wider variance. Looking at the histogram, data is normally distributed except for a number of films that received a zero rating. The greatest frequency for sample is ~7, whereas the greatest frequency for population is closer to 6.

   2. Horror adaptation films have higher ratings than other film genres - True
  
<img src="https://user-images.githubusercontent.com/75763314/132150196-c173839d-00e7-47ee-bb87-c8fa5030da48.png" width=500 align=center>

   3. The number of book reviewers and rating for adaptation films are correlated - False
   
<img src="https://user-images.githubusercontent.com/75763314/132150294-87b113dc-8825-4e65-8e9a-dfab1c04f220.png" width=500 align=center>

   4. The number of pages for adaptation films are correlated - False

<img src="https://user-images.githubusercontent.com/75763314/132150324-fff36189-7a4b-4b1e-bed0-88bbc22af80a.png" width=500 align=center>

## Source Data
Raw Data: [Link](https://drive.google.com/drive/u/0/folders/1bF9VaI-7scQclkEFgliX6AUroOKSVfCw)

## Presentation

Presentation: [Link](https://github.com/laurenemilyto/film_adapatation_success/blob/main/presentation.pptx)

## Contributors
- [Ashley Howell](https://github.com/[ahowellgates])
- [Matthew Bishhop](https://github.com/[mabishop84])
- [Lauren To](https://github.com/[laurenemilyto])
