![image](https://i.pinimg.com/originals/86/13/02/861302679501d1c6e037fdc7d17ec756.jpg)

## Table of Contents
   =================

  1. [Background](#background)
  2. [About This Project](#about-this-project)
       - [Technologies & Methods](#technologies--methods)
       - [Preview](#preview)
       - [Results](#results)
       - [Source Data](#source-data)
  3. [Presentation](#presentation)
  4. [Contributors](#contributors)

## Background 
Making feature films is a high-risk venture. Studios invest millions of dollars creating the next blockbuster with no way of knowing up-front whether their huge investments will turn a profit. When deciding whether to fund a particular movie, what are some pieces of information that would help ensure that the film would be successful? It would help to know that you are investing in a good story, with memorable characters. Something that will connect with the audience. 

<img src="https://m.media-amazon.com/images/M/MV5BNWIwODRlZTUtY2U3ZS00Yzg1LWJhNzYtMmZiYmEyNmU1NjMzXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_.jpg" width=300 align=center>

In this project, we explored the relationship between books and movies to answer the question: do book adaptations perform as well as movies? What does the data tell us about how book adaptations perform after being released as movies, and are they reliably better than the average movie?

## About This Project
To analyze the success of book adaptations, we performed EDA on over 45,000 films from March 1910 to July 2017 using a dataset originating from the TMDB Open API. In this dataset, there were 829 films based on novels. To extract insights on the books themselves we combined this data with Goodreads data such as book publisher, page count, and book rating. Matching the two datasets on ‘title’, 105 matching movies and books resulted that were used in this analysis. 

### Technologies & Methods
- Python
     - Pandas
     - Matplotlib
     - Scipy
     - Numpy
- Data Visualization
- Statistical Inference
- Linear Regressions, One-Tailed T-tests, Shapiro–Wilk Test & ANOVA
     

### Preview
<img src="https://user-images.githubusercontent.com/75763314/132150877-986048a6-5b7a-43e4-90eb-5e7bf685cba0.png" width=500 align=center>

### Results
<details>
  <summary>Click to expand</summary>

  ##### 1. Hypothesis: Book to film adaptations have higher ratings than most films. **Result: True**
 
<img src="https://user-images.githubusercontent.com/75763314/132149924-41c355d4-b4e3-4268-ad7f-204761d4c9e2.png" width=500 align=center> <br>
Looking at the scatter plot, the sample is a good representation of the population, although the sample ratings are primarily between 5 & 10, whereas the population ratings have a much wider variance. Looking at the histogram, data is normally distributed except for a number of films that received a zero rating. The greatest frequency for sample is ~7, whereas the greatest frequency for population is closer to 6.<br>

  ##### 2. Hypothesis: Horror adaptation films have higher ratings than other film genres. **Result: False**
  
<img src="https://user-images.githubusercontent.com/75763314/132150196-c173839d-00e7-47ee-bb87-c8fa5030da48.png" width=500 align=center> <br>

The p-value is greater than .05 so no effect was observed between genres. We can infer that book to film adaptations have similar means across genres. The box plot reveals that book to film adaptations tend to be highly rated on IMBD, regardless of genre.<br>

  ##### 3. Hypothesis: The number of book reviewers and rating for adaptation films are correlated. Result: False
   
<img src="https://user-images.githubusercontent.com/75763314/132150294-87b113dc-8825-4e65-8e9a-dfab1c04f220.png" width=300 align=center> <br>
From the pattern observed from the scatterplot and regression, the low rvalue shows that there is not a relationship between the number of pages in a novel and the rating of the film adaptation. The r squared value of 1% can be interpreted as the length of the book explains 1% of the variation in film adaptation scores. The relationship between these variables is not very meaningful.<br>

  ##### 4. Hypothesis: The number of pages for adaptation films are correlated. **Result: False**

<img src="https://user-images.githubusercontent.com/75763314/132150324-fff36189-7a4b-4b1e-bed0-88bbc22af80a.png" width=300 align=center> <br>
From the pattern observed from the scatterplot and regression, the low rvalue shows that there is not a relationship between the number of goodreads reviews and the rating of the film adaptation. The r squared value of 4% can be interpreted as the book rating explains 4% of the variation in film adaptation scores. The relationship between these variables is not very meaningful.<br>
</details>
   
### Source Data
Raw Data: [Link](https://drive.google.com/drive/u/0/folders/1bF9VaI-7scQclkEFgliX6AUroOKSVfCw)

## Presentation

Presentation: [Link](https://github.com/laurenemilyto/film_adapatation_success/blob/main/presentation.pptx)

## Contributors
- [Ashley Howell](https://github.com/[ahowellgates])
- [Matthew Bishhop](https://github.com/[mabishop84])
- [Lauren To](https://github.com/[laurenemilyto])
