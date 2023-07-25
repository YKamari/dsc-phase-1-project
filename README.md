
# Microsoft Movie Venture Analysis
## **Author**: [Yvonne Kamari](mailto:yvonne.kamari@student.moringaschool.com)


![Oscars 2023- Highlights, history makers, winners and more from Hollywood's biggest night](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/95f0a2ca-a5df-4177-b6ab-8e29822532d0)



## Overview

This project analyzes movie trends and success against various metrics such as earnings, profit, genre, and ratings. Understanding and analysis of the feature relationships indicate that while the number of movie releases is on a downward trajectory, sequels are becoming an increasingly popular way for production studios to grow their revenue. While the movie industry's massive earnings have long been attributed to success overseas, foreign markets have seemingly been affected by economic factors hampering their performance. Luckily we have seen the domestic market some in strong to try and fill in the gap. Microsoft can use this analysis to determine the category of movies to produce, markets to target, and budgetary allocation for their productions.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies.

Using data from Box Office Mojo, The Numbers, IMDB, and The Movie Database I discuss and illustrate the patterns in movie release trends, box office revenue, ratings and popular genres to aid in Microsoft's decision on what type of films to create.

## Data

This project uses data from the below sources. The data contains information on domestic and worldwide earnings, release dates genres and ratings.
1. [Box Office Mojo ](https://github.com/YKamari/dsc-phase-1-project/blob/master/zippedData/bom.movie_gross.csv.gz)
2. [The Numbers ](https://github.com/YKamari/dsc-phase-1-project/blob/master/zippedData/tn.movie_budgets.csv.gz )
3. [IMDB](https://github.com/YKamari/dsc-phase-1-project/blob/master/zippedData/imdb.title.basics.csv.gz)
4. [The Movie Database](https://github.com/YKamari/dsc-phase-1-project/blob/master/zippedData/tmdb.movies.csv.gz)

## Methods

This project uses Exploratory Data Analysis (EDA) including trends and correlation providing key insights into the movie industry to identify penetration strategies for Microsoft.

## Results

### 1. Annual Trend Analysis: Movie Releases

There appears to be a downward trend in the number of movies released yearly with the highest number of movies being released in 2010 and the least in 2018. While a slight recovery is observed in 2014, releases steep drop in 2016 and only further declines thereafter.


![movie release trend](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/7f9500d2-9731-4668-ba8a-ac8249e8a0a1)




### 2. Annual Trend Analysis: Worldwide Gross, Production Budget & Gross Profit

We note a slight year-on-year increase in the average production budget from 2010 - 2013 and 2015 - 2017 with the drop in average production budget between 2013 and 2014 may possibly be attributed to a decrease in production of blockbuster movies or challenging economic times.

Average gross profit earnings follow a similar trend to worldwide gross earnings with the average gross profit steadily increasing between 2010 and 2014, dipping in 2015, but recovering strongly from 2016 as foreign earnings reach an all-time high.



![WW Gross, Prod   GP](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/8736acb2-6492-4b5c-8139-b0f5128eab30)



### 3. Correlation between Season for Release & Earnings

The correlation between the season for release and gross earnings is very weak indicating almost no linear relationship between the season in which a movie is released. Studios are therefore free to release their productions as they wish.


![Corr Season   Releases](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/b55ab536-914e-4fc6-b3e0-c2e7b441327d)




### 4. Most Successful Movie Productions: Earnings & Profitability

The top 20 highest-earning movies from 2010 to 2018, domestically and overseas are produced by 10 studios. The animated movie, Toy Story 3 was also the only movie that is the highest earning both domestically and overseas in its release year.

The top 10 highest-earning movies worldwide each year are also the top 10 most profitable movies in their respective years. Foreign gross earnings were the major contributor to the financial performance majority of these films with the exception of 'Transformers: Dark of the Moon' and 'Jurassic World' whose earnings were mainly from domestic earnings.


![profitable movies yoy](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/2f209d64-fb2e-41ba-aed4-86ed3a07b1fb)


Looking also at the top 20 most profitable movies overall, we note that 65% are sequels inferring that they generally fetch more at the box office than stand-alone original films or original films related to a sequel (parent films) or possibly the result of higher sequel releases over the period.


![profitable movies overall](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/9c3fb448-1a36-4f08-8330-7b179656775f)



### 5. Most Profitable Studios
Having the majority of the most high-earning and profitable films, Walt Disney and Universal Studios are the two most profitable studios raking in USD 23,835,217,937.00 and USD 20,733,081,963.00 respectively over the 4 year period (2010 - 2018).


![Most profitable studios](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/5fb7e3e6-74d0-466a-acd1-d3c5186c84b9)



### 6. Movie Productions with the Highest Budgets
Studios making big bucks also often allocate hefty budgets towards their production but this doesn't always pay off as expected. We see only 4 movies among the top 20 movies with the largest budgets make it to the top 20 most profitable movies. These are, 
* Avengers: Age of Ultron
* Avengers: Infinity War
* Captain America: Civil War
* The Fate of the Furious



![movies with highest prod budgets](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/2ab9d471-3418-4162-9e73-8a9f1a807aa1)



### 7. Sequels: Comparative Analysis of Gross Profits
Analyzing sequels, we find that they are greatly profitable and are a great way for studios to earn profits by further developing existing productions. The performance between earlier and later releases varies from movie to movie likely dictated by the success of the preceding film.



![sequels](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/e4de0255-c440-46f2-bfd2-11acee1fce62)



### 8. Correlation between Vote Average (Rating) and Gross Profit
We observe a weak positive relationship between vote average and profit. Implying that on average, as the vote average increases, there is a slight tendency for the profit to increase as well. However, given the weakness of the correlation, this suggests there may be a lot of variability in profit even for movies with similar vote averages.



![vote average vs profit](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/0c8ea9de-c1a6-4abf-a517-32c871dfe8ef)




### 9. Most Popular Genres
The top 5 most highly produced genres of film in the dataset are,
* Drama - 574
* Comedy - 406
* Action - 333
* Adventure - 278
* Thriller - 193


![popular genres](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/5a5b201c-1016-4955-8b2a-953c33546ddd)


We observe a combination of these genres also associated with the genres of the top 20  most profitable movies.


![genres for profitable movies](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/dca0d9de-fb4f-4623-be44-6d3d6be6574e)



### 9. Runtime Minutes
While the average runtime for movies in the dataset is 108 minutes, we find that movie productions may far exceed the mean. A possible indication of audience demands for longer more engaging films.

![Runtime box plot](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/cf660ef0-00f4-494c-b2bd-6e5bf9c5e223)

It is observed that major box office productions will now often have movie runtimes ranging from 134 - 165 minutes. On a few occasions movies such as 'The Wolf of Wall Street' are made, pushing the limits with a runtime of 180 minutes. 


![longest runtimes](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/4c166db9-0397-42f1-8cc1-47fcbfe634f9)



## Conclusions
The movie industry is highly lucrative, earning the major studios hundreds of millions of dollars in profit. Despite the downward trend in the number of movie releases, the future of the industry remains promising as earnings continue to skyrocket.

The industry is currently dominated by 10 major studios whose movies are consistently among the highest-earning and most profitable. A portion of the success of these studios can be attributed to their ability to turn already existing stories such as comic books and movies into franchise films as well as make multiple sequels from their original creations enabling them to squeeze every last drop in earnings from those storylines.

The leading studios in the industry have done their homework, majorly focusing their productions of the most lucrative genres, Action, Adventure, Sci-Fi, Animation, and Comedy - a recipe for success. Additionally putting major focus on sequels and franchise productions enabling to capitalize on the development of one storyline.

The overseas market is critical for the success of any major film studio and thus must not be neglected.


## Business Recommendations
1. Conduct thorough market and competitor analysis as we have observed the market has been dominated by a select few studios namely, Walt Disney (BV), Universal Studios (Uni), Warner Bros (WB), Sony, and Fox. Given that numerous studios with years of experience have yet to dethrone the top 5 is an indicator of the mean feat that it is.
3. Hire talent from the top 5 studios who can guide the strategy and content creation.
4. Consider the foreign market - it has proven a major contributor to the success of the top 5 studios, especially Disney, the highest-earning studio from foreign gross earnings. 
5. Develop storylines with longevity. Franchise films developed as comic book adaptations, Sci-Fi and fantasy films have become increasingly profitable over the years and are a great contributor to the success of other major studios.
6. Investment in the right technology is key. Almost every movie being released at the moment is 3D and includes a massive amount of CGI.
7. When it comes to runtime minutes it seems that nowadays, the longer the better. Studios appear to be giving audiences longer and longer movies possibly in response to audience feedback/demands.
8. It may be a viable option for Microsoft to invest in one of the more successful studios in the industry given that it is far less risky and guarantees Microsoft a decent form of return.

## Study Limitations
1. Given the structure of the data, the correlation between genre and earnings could not be established.
2. The data did not contain all original titles to enable comparative analysis with the succeeding sequels/franchise films.
3. We are unable to establish the impact of contributions towards earnings such as marketing, cast, and crew.

## Recommendations for Future Analysis
1. Effects of streaming sites on the movie industry
2. Genre as a contributor to the success of a film
3. Impact of studio name (brand), on the success of a film.
