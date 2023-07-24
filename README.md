# Microsoft Movie Venture Analysis

**Author**: [Yvonne Kamari](mailto:yvonne.kamari@student.moringaschool.com)

## Overview

This project analyzes movie trends and success against various metrics such as earnings, profit, genre and ratings. Understanding and analysis of the feature relationships indicates that while the number of movie releases is on a downward trajectory, sequels are becoming and increasingly popular way for production studios to grow their revenue. While the movie industry's massive earnings have long been attributed to success overseas, foreign markets have seemingly been affected by economic factors hampering their performance. Luckily we have seen the domestic market some in strong to try and fill in the gap. Microsoft can use this analysis to determine the category of movies to produce, markets to target and budgetary allocation for their productions.

## Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies.

Using data from Box Office Mojo, The Numbers, IMDB and The Movie Database I discuss and illustrate the patterns in movie release trends, box office revenue, ratings and popular genres to aid in Microsoft's decision on what type of films to create.

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

There appears to be a downward trend on the number of movies released yearly with the highest number of movies being released in 2010 and the least in 2018. While a slight recovery is observed in 2014, releases steeply drop in 2016 and only further declining thereafter.



![declining movie trend](https://github.com/learn-co-curriculum/dsc-project-template/assets/133201112/0d6c1bf9-f97e-47d8-b0b6-04305052f2a8)




### 2. Annual Trend Analysis: Worldwide Gross, Production Budget & Gross Profit

We note a slight year on year increase in average production budget from 2010 - 2013 and 2015 - 2017 with the drop in average production budget between 2013 and 2014 may possibly be attributed to a decrease in production of blockbuster movies or challenging economic times.

Average gross profit earnings follows a similar trend to worldwide gross earnings with the average gross profit steadily increasing between 2010 and 2014, dipping in 2015, but recovering strongly from 2016 as foreign earnings reach an all time high.



![earnings vs profit vs budget](https://github.com/learn-co-curriculum/dsc-project-template/assets/133201112/072e16a4-52f5-43a1-8620-52b696155d7a)


### 3. Correlation between Season for Release & Earnings

The correlation between season for release and gross earnings is very weak  indicating almost no linear relationship between the season in which a movie is released. Studios are therefore free to release their productions as they wish.



![worldwide gross seasonal correlation](https://github.com/learn-co-curriculum/dsc-project-template/assets/133201112/ce4cb4ff-7670-4301-8917-45b5ae5e5b3f)


### 4. Most Successful Movie Productions: Earnings & Profitability)

The highest earning movies worldwide each year are also appear to be the most profitable movies in their respective years. Foreign gross earnings was the major contributor to majority of these films with the exception of 'Transformers: Dark of the Moon' and 'Jurassic World' whose earnings were mainly from domestic earnings.

Toy Story 3 was also the only movie that is the highest earning both domestically and overseas in its release year.



![most profitabe movies per year](https://github.com/learn-co-curriculum/dsc-project-template/assets/133201112/f6cb697c-3de8-42e7-96a2-a189438aab25)



Looking at the top 20 most profitable movies overall, we note that 65% are sequels inferring that they generally fetch more at the box office than stand alone original films or oiginal films related to a sequel (parent films) or possibly the result of higher sequel releases over the period.



![top 20 profitable movies per studio use also ww](https://github.com/learn-co-curriculum/dsc-project-template/assets/133201112/c9b13514-e770-46f6-a366-11926d4f430c)



Having the majority of the most high earning and profitable films, Walt Disney and Universal Studios are the two most profitable studios raking in USD 23,835,217,937.00 and USD 20,733,081,963.00 respectively over the 4 year period.



![top 10 highest profit plus earning studios](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/5f1b9d76-7a72-442a-b87e-cfcaf356f884)


Studios making big bucks also often allocate hefty budgets towards their production but this doesn't always pay off as we see only 4 movies among the top 20 movies with the largest budgets make it to the top 20 most profitable movies. These are, 
* Avengers: Age of Ultron
* Avengers: Age of Ultron
* Captain America: Civil War
* The Fate of the Furious


![movies with largest production budgets](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/8d5e3519-42d5-4943-a774-17d44eabf153)



Analyzing sequels, we find that they are greatly profitable and are a great way for studios to earn profits by further developing existing produtions. The performance between earlier and later releases varies from movie to movie likely dictated by the success of the preceeding film.



![sequels gross profit](https://github.com/YKamari/dsc-phase-1-project/assets/133201112/177ec7ad-0c3a-4419-8926-da605853e8df)


