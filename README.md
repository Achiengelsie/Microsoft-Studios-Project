# Microsoft Movie Studio Project
**Author:** Elsie Ochieng
***
![budget v. revenuet]('Images/filmstudio.jpg')

## Project Overview

Therefore, an anlysis was conducted on various datasets to help understand the Movie business better and obtain key business recommendations to help the Microsoft Movie Studio enter the market and deliver the best content possible.
The questions answered through understaning and analysing the data are:

    1. Why should Microsoft consider getting into the movie making business?
    2. What kind of movies should Microsoft focus on and why?
    3. WHo should Microsoft work with to produce the best?
  
The questions are answered by looking into various datasets and anlysing different trends over a period of time.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a movie studio, but possess little to no knowledge on what factors to consider.
Currently the movie industry is saturated and extremely competitive. Many of the industry players do more than just producing content. They also offer streaming services where the consumers are able to easily access the content.

To ensure that Microsoft has the information needed to successfully enter the market exploratory data anlysis was carried out on various datasets to retrieve key business recommendations. First, budgeting and rvenues were looked into because the main goal of entering into any buiness is of course to make profit. Secondly,  movie properties and features such as runtime and popular genres were investigated as these are what separate a hit movie from others. Third was to look into who to work with in the industry as well as who the competition is. This will help Microsoft set itself apart from the rest and find unique ways to ensure they standout from the rest.

***

## Data

The data used came from three different sources.

**1. The Numbers**

A website that tracks box office revenue using algorithms to also forecast incomes of film projects. The specific dataset used contains information on movies, release dates, production budgets, domestic and worldwide income all of which were target variables.

**2. Rotten Tomatoes**

Contains aggregates of movie reviews from critics and audiences. Implements a Tomatometer system to rate movies thus giving people information on what different critics think of a movie. The data used includes movie reviews, genres, runtimes and studios.

**3. Internet Movie Database(IMDb)**

An online database that contains information about movies, tv shows, actors, directors and other aspects of the entertainment industry. The dataset used contained tables about movies, directors, writers and other personnel related to the movies. Also contained average movie ratings and number of votes received for the ratings.
***


## Results

###  Budgets and Profits

**Question:** Do budgets correlate with high returns?

![budget v. revenuet]('images/Correlation btwn Production Budget and Revenue.jpg')

There is a positive correlation between production budget and revenue. This means that there in a tendency for movies with higher production budgets to return higher profits.

![Top 20 profits]('images/Production Budget and Revenue for Top 20 Movies.jpg')

The higher the production budget, the more likely revenue will be high


### Genres and Runtime

**Question:** Important movie properties to consider?

![genre ratings]('images/Genre Popularity by Ratings.jpg')

The most popular genres from the data analysed is Drama. Other genres like Comedy, Documentary, Thriller and action are also popular but not as much. It is however important to note that most movies tend to have more than one genre therefore it is important that a movie have the right mix of genres for it to be good.

![Runtime distribution]('images/Histogram Showing Runtime Distribution.jpg')



### Competition and collaborators

**Question:** Who are the best writers in the industry?

![Top 5 directors]('images/Top 5 directors.jpg')


From this analysis we identified the top 5 writers that Microsoft can consider working with to produce good content

**Question:** Who is the competition?

![Studio Ratings]('images/Studio Ratings.png')

To compete with some of the top studios Microsoft needs to aim for an average RT rating of 10. We have also identified some of the studios to look out for.


## Conclusion

This analysis leads to three recommendations for Microsoft's entry in the film industry:

 **1. Invest in high budget**
 
For high returns, Microsofy should plan to invest ... in a film. The higher the budget the higher the quality of film which will attract higher profits
     
 **2. Produce movies within Drama, Action, Comedy, Thriller and Documentary genres**
  
This is because from the nalysis we saw that these genres are the most popular. Microsoft also needs to ensure that the movies they produce have a runtime in the 90 - 100 minute range as this is what viewers prefer.
     
 **3. Work with the best in the industry and observe competition**
 
There are several directors Microsoft can collaborate wth to ensure that they produce some of the best content that will enable them compete with other movie studios. We have also noted that to compete with some of the top studios Microsoft needs to aim for an average RT rating of 10. We have also identified some of the studios to look out for
   
There is further analysis required to provide even more insight on the Movie industry. Areas such as offering streaming services is an example of a key area that needs looking into to ensure that Microsoft gets into the industry armed with the best info.


## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
