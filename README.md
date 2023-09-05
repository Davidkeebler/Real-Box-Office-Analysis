# Real-Box-Office-Analysis
## Overview
This project analyzes data from IMDB, TheMovieDB, and The Numbers to create business insights for American investors looking to open a new movie studio. The data used in this project includes the profit, aggregate review scores, genres, and number of markets that each movie was released in. Film industry investors can use this analysis to guide their decisions as they decide what kind of movies to create.
## Business Problem
Film industry investors may be able to use this analysis to determine which genres of movie to create in order to create the most successful movie, with profit being the main indicator of success. I also provide mathematical recommendations for their investment based on patterns I observed in the data. The purpose of this project is to provide guidelines for investors on how much to invest, where to invest it, and how to invest it in order to make the most profitable movie.
## Data
The data used in this project comes from multiple sources that were joined together to create the set of data most useful for the analysis. The data includes production budgets, gross profits, aggregate review scores as well as the number of reviews from multiple different sources, the genre of the movies, and the markets which the movies were released in.
## Methodology 
This project uses descriptive analysis and linear regression to predict the relationship between production value and profit, as well as the relationship between the number of markets and profit. It also provides an overview of the average profitability of different genres.
## Results
There is a strong correlation between the initial investment of the movie and the ratings the movie recieves. It was also found that the ratings are highly correlated with the profit of the movie. This corellation can be seen in the following graph:

![](https://github.com/Davidkeebler/Real-Box-Office-Analysis/blob/main/img-src/score%20vs%20profit.png?raw=true)

 The more you invest, the more profitable your movie is likely to be - if it proves to be popular. It was also shown that the number of markets a movie is released in is an excellent predictor of its profitability, as seen in this graph:

 ![](https://github.com/Davidkeebler/Real-Box-Office-Analysis/blob/main/img-src/markets%20vs%20profit%20.png?raw=true)

The analysis of genres found that Animation, Adventure, and Sci-Fi movies tend to be significantly more profitable than other genres of movies. 

![](https://github.com/Davidkeebler/Real-Box-Office-Analysis/blob/main/img-src/genres.png?raw=true)
## Conclusions
My analysis has created three conclusions about how investors should invest in new movies:
- **Maximize film production budget.** Film production budget is correlated with an increase in aggregate user ratins, which in turn are highly correlated with a large increase in profit per point of rating. There is effectively an exponential relationship between production budget and profit, so it is very important to invest as much as possible in the production of each individual movie, instead of churning out many low-budget movies. 
- **Maximize the number of markets that each film is released in.** This increases the size of the audience that the movies can be marketed to. My study also found that movies produced in English as the first language tended to perform much better than movies produced in other languages primarily. 
- **Produce movies in the Animation, Adventure, and Sci-Fi genres**. My analysis shows that these genres are significantly more profitable on average than other genres of movie.
## Next Steps
There are more analyses that could potentially help investors narrow in on the best practices for consistently creating successful movies:
- **Create a multiple linear regression model of all the different factors that may contribute to aggregate movie scores.** It is very likely that my simple linear regression model's prediction of the relationship between initial investment and user ratings is missing out on several other factors that contribute to better scores. Investors could further increase their profits by finding and maximizing these other factors.
- **Determine which markets contribute the most to the profit of a movie and spend more money on advertising to those markets.** My analysis predicts a linear increase for each additional market that a movie is released in, but not all markets are created equal. Investors could further increase their profit by determining which markets contribute the most to sales and focusing advertising efforts on those markets.
## Repository Structure
├── images  
├── data  
├── .gitignore  
├── box office analysis presentation.pdf  
├── readme.md  
└── index.ipynb  


