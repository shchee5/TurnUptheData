# TurnUptheData

## Team Members:

Anna Chee, Jorge Daniel Atuesta, Dan Waehner, Domenic Padulo, Nabila Rizvi

As a team we want to recognize the time and effort that Will Wright, Erin Willis and Dwight Theieme put in to help us achive our final goal.

## Background:

![Music](Images/data.jpeg)

Turn Up the Data Co. has hired our team of experts to get a better understanding of how music trends have been changing over the years. They want to make data-driven decisions on what types of music they should invest in as they do budget planning for the upcoming years. Using the Spotify dataset, our team will analyze how popularity of music have changed in the US based on song components and make recommendations to the company based on our findings.

## Introduction:

What are music lovers listening to nowadays? How has music changed over the years? How do the various music variables correlate to popularity of the songs, if at all? These are all valid questions to consider when planning future budgets. Our team will investigate these questions using the Spotify dataset and provide insights that will help Turn Up th Data strategize on where they should allocate their funds.

Dive into and join us in this exciting journey across data trends in the music industry!

![Music](Images/music.jpg)

## Final Results

Here is our teams recommendation for Turn Up The Data Co. to create the next musical hit.

Ideally the song should have the following components as a starting point:

* Acousticness should be greater than 0.5 range after a crisis. Less than 0.5 if there are no major events during that year.
* Energy should be in the from 0.6 to 0.8 range
* Instrumentalness should be in the 0.1 to 0.2 range
* Key should be in the 0.4 range
* Loudness should be in the -0.5 to 0.25 range
* Speechiness should be in the 0.2 range

As a team, we found out that there is sufficient statistical evidence that proves there is a relationship bewteen this song components and the songs popularity.

If the company decides to go with a more conservative approach (wanting their song to be in the 65% to 75% popularity ratings) they can have these starting points for the song components:

* Acousticness 0.5
* Energy 0.5
* Instrumentalness 0.08
* Key 4.7
* Loudness -9.91
* Speechiness 0.06

## Results & Analysis

As a team we focused on cleaning up the data at the beginning to try to establish our data trend through out the years. After this step was done, we had the chance to look over all the song components to find which of them had relationships with the popularity of the song.

We then establish a general question to be answered: Is there a relationship between variable x (independent song component) and the popularity of the song?

After we had the question set we created both out hypothesis and null hypothesis:

Hypothesis – There is a relationship between variable x and the popularity of the song

Null hypothesis- There is no relationship between variable x and the songs popularity

After our hypothesis were created, we ran a Pearson correlation test to see if there was sufficient statistical evidence to reject the null hypothesis for each independent variable that was being tested against the popularity index. We established our alpha value to be 0.05.

With the Pearson correlation test results, we found out that the following song components were the only ones that had enough statistical evidence to prove that they do have a relationship with the songs popularity:

* Acousticness

* Energy
* Instrumentalness

* Key
* Loudness

* Speechiness

The other song components ('Danceability', 'Duration_Min', 'Explicit', 'Liveness', 'Tempo' & 'Valence') did not have enough statistical evidence to reject the null hypothesis, therefore stating that there is no relationship to the variable and the popularity of the song.

To see if the data trends found made sense, we than tested the individual song components bewteen the most popular songs and the least popular songs. We found out that the in general the least popular song data set did have differences in the ranges for each of the song components that have a direct relationship with the popularity of the song. 



### Complementry Figures:

The first set of line graphs show us the trends in music based on the highest popularity for each song compoennt over the time period 1920 -2021:

The first set of line graphs show us the trends in music based on the lowest popularity for each song compoennt over the time period 1920 -2021:

The correlation heatmap allows us to visually see if there are correlations bewteen the variables and the song popularity index. If the square is green it means there is a positive correlation, yellow no correlation and red negative correlation. This is based out of the pearsons correlation matrix. 


## Conclusion:

## Data Source:

- Kaggle Spotify datasets (https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks)
