# Read me template
## INTRODUCTION	 

Our team was recruited to help our client, Computing Vision, figure out a business plan to have a successful launch into the movie making industry. We were charged with exploring the types of films currently doing the best at the box office using different samples of data. Through statistical analysis we were able to translate our findings into actionable insights that the head of Computing Vision’s new movie studio can use to help decide what type of films to create. 

 

## Business Problem 

Computing Vision (a made-up company for the purposes of this project) sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t have much background in creating movies. You are charged with exploring what types of films are currently doing the best at the box office using different samples of available data. You then will translate those findings into actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create. 

 

## Data Sets Information (Sources) 

We decided to use data from the sources indicated below to help perform our data analysis. The sources we have chosen are widely recognized within the movie industry and well known as being credible, which is important when trying to make sure your data has integrity.  

IMDB: IMDb: Ratings, Reviews, and Where to Watch the Best Movies & TV Shows 

The-Numbers: The Numbers - Where Data and the Movie Business Meet (the-numbers.com) 

## Seasonality 

#### Intro into specific point of study: 

For our analysis, we are going to look at the effect of seasonality on gross domestic revenue. We think that the summer months will perform the best because students are out of school and families will be looking for ways to entertain their children. School is out in the US during June, July, and most of December. With heat waves in full effect, we think the summer months will perform the best. We're only interested in domestic gross revenue to keep seasonality consistent.  

Our question: Are gross revenue sales from summer months greater than that of other seasons as a whole? 

#### Data Exploration: 

We decided to go with the Numbers Dataset because it contains the release dates and gross revenue of each movie. The dataset has no null values, however there are lots of movies with zero domestic gross revenue. Since we are only interested in successful movies, we are going to filter our dataset to only include "above average" movies. Also, since the movie industry has changed over the years, we are only going to include movies that were created during or after 2010. 

#### Data Analysis: 

Our goal is to plot out the following: 

- Count of movies by season 

- Total revenue by season 

- Average revenue by season 

 

We had to categorize the months as seasons, and we did this as follows: 

- Summer: June, July, August 

- Fall: September, October, November 

- Winter: December, January, February 

- Spring: March, April, May 

 

We are interested in what the average gross domestic revenue is, so we created a histogram of domestic gross revenue. 

 

 

The histogram is shown in the hundreds of millions. This shows that the data is highly skewed, so we decided to use the median instead of the mean. The median revenue is 93,526,665.  

 

Now, we looked at the number of movies released per season. 

 

By this bar chart, we can see that summer releases the greatest number of movies. This shows us evidence that summer movies are successful, if other companies are continually releasing movies in the summertime.  

 

Now that there is some background knowledge, we can look at what we're interested in. The average revenues per season. 

 

Seeing this is a little shocking that spring does slightly better than summer. We want to take this a step further and break it down by months to see if one month is outperforming the others. 

 

 

 

This bar chart shows us that June performs the best of the months, with May coming as a close second. This now makes the Seasons bar chart make sense, since May and June were broken down into different seasons. We notice peaks in May/June and November/December; all of these months are times of the year when children are out of school.  

 

#### Conclusions: 

In conclusion, we would recommend releasing a movie in the month of June because it has the highest average revenue of all of the months. Children are out of school, so it is a great time to have entire families gather together to see a movie. 

## Run Times 

#### Intro into specific point of study:  

Our Question: “Does the length of a movie(runtime) affect movie earnings?” 

For our analysis, we decided to investigate how the length of a movie affects the movie’s earnings. From the data, the team looked at movies that made above the median gross domestic revenue and sorted them by run times to see the relationship between the two.  

 

#### Data Exploration: 

When analyzing the data, the team used the two datasets mentioned above to gather the domestic gross revenue, and the runtime (in minutes). The runtimes from IMDb were correlated to specific movie titles, so the team had to join the two datasets on “primary title” to have runtimes and domestic gross revenue in the same table. While exploring “The Numbers” data, it showed that the average movie made around 44 million dollars in revenue, so in order to make a successful movie, the team focused on movies that grossed above the 44 million mark, in the last decade. 

 

#### Data Analysis: 

Our goal is to plot out the following: 

- Each movies’ run time in relation to its domestic revenue 

- The average domestic revenue of movies made in 30min sections 

 

The Team categorized the runtimes in 30min intervals: 

- 30 - 60 Minutes 

- 61 - 90 Minutes  

- 91 - 120 Minutes 

- 121 - 150 Minutes

- 151 - 180 Minutes

 

#### Visualizations:  

 

Scatterplot showing the 931 movies that grossed above the average 44 million dollars, correlated with their runtimes. 

 

The Bar chart shows the average domestic gross revenues, correlated with their runtimes in 30-minute increments. 

 

#### Conclusions: 

Based off of the above analysis and visualizations, we suggest making movies between 151 and 180 minutes in length to maximize profits. Taking into account the top 931 grossing movies that are between 30 and 180-minutes length. 

 

## Genre 

#### Intro into our specific point of study: 

For our first business insight, we will be researching and exploring how genre affects domestic revenue. This is relevant as very costly resources are allocated to creating movies and it is important to understand what genres perform the best prior to making a decision as to what kind of movies Computing Vision will make. Let's start by looking at our movie data. 

#### Hypothesis test: 

We decided to delve further into the genre category and test our hypothesis that family genre movies do better than other genres, revenue wise. We posed this hypothesis with the reasoning that family movies reach a wider audience. 

 

##### Null Hypothesis: Family movies have a lower or equal average gross domestic revenue than the rest of movies 

##### Alternate Hypothesis: Family movies have a significantly greater gross domestic revenue than the rest of movies 

 

#### Analysis: 

Our goal is to plot out the following: 

- Number of movies by genres 

- Mean revenue by genre 

- Regions of rejection for t test hypothesis

 


  

#### Visualizations: 

 

Our bar plot shows how many movies of each genre are represented in the dataset. We can observe some saturation in the drama and action categories. So much of the data lays in these categories because of how many movies of this genre have been made in the past decade. This notion is going to contribute to our hypothesis test 

 

 

According to our bar plot, the genres with the greatest performing movies in terms of average gross domestic revenue are of the family, musical, fantasy, and adventure genres. It is to be noted that often times action, family, and adventure movies are typically marketed towards and consumed by a wider group of people due to age appropriate ratings as opposed to horror, for example, which is often times rated PG-13 or R and cannot be seen by a large group of people. This notion will guide our hypothesis test that is later to come. Let's see what the top family movies are called! 

 

 

Our sample contains 20 observations, with a mean of 108128333.55 and a standard deviation of 71722959.9 with 19 degrees of freedom. The difference between the sample and population mean is 67254039.6. 

This means that family movies should be about $108,128,333 higher than the population mean. 

The p-value came out to 0.00024629, which is less than the alpha, therefore we must reject the null hypothesis. 

 

#### Conclusions:  

We reject the null and conclude that family movies have a significantly greater gross domestic revenue than the rest of movies. 

 

## Overall Recommendations / Conclusions 

For maximum success and potential revenue, the team recommends Computing Vision to focus on: 

- Family genre movies 

- Movie Lengths between 151 –180 minutes 

- Releasing a movie in the Month of June 

 
