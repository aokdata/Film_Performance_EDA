# Film Performance Exploratory Data Analysis

Aidan O'Keefe

Project Notebook

Project Presentation

## Overview

Microsoft wantes to create a new movie studio. Want to know what types of films are currently doing the best at the box office? This is interpreted as what Genres have the highest ROI (and average ratings) within the last 10 years. Using data from IMDB (film details and rating information) and The Numbers.com (budget and sales data), I analyzed which Genres had high, consistent, and positive trending ROI and Average Ratings. I found the best genre in these categories to be Drama Sci-Fi Thrillers, which also seem to have low competition (fewer movies made in the genres per year). I then looked to see which director would be best by analyzing ROI and Average Ratings across directors in Drama Sci-Fi Thriller, Drama Sc-Fi, Drama Thriller, and Sci-Fi Thriller. I found the best director for this genre to be M. Night Shyamalan. Lastly, I looked at ROI by release months for Drama Sci-Fi Thriller films and found the winter, particularly January, was the best time to release such a film.

This analysis was limited by the amount of financial data I had for films. For a more accurate analysis, I would spend time increasing the size of my data by collecting missing financial data to add to the IMDB film data.


## Business Case

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

Question: what types of films are currently doing the best at the box office?

Types = Genres
Currently = last 10 years
Best = highest ROI with highest average ratings

Goal: deliver actionable insights to help decide what type of films to create.


## Data Understanding

We are going to look at data taken from IMDB and The Numbers.com

IMDB database: film details and rating information
The Numbers.com CSV: budget and sales data

Each record in the data represents a film along with variables such as genres, release year, average rating, vote counts, production budgets, and more.


### Visualizations

#### ROI over Time for Top Ten ROI Genres
![TopROI_Genres_ovr_Time](https://user-images.githubusercontent.com/120589094/215112411-7caaaca3-af83-4add-9fe6-9c7416337587.png)

#### ROI over Time for all films by Drama Sci-Fi Thriller Directors
![Top10ROI_DST_Dir_ovr_Time](https://user-images.githubusercontent.com/120589094/215112581-83c38719-e298-4f9b-a622-9726d6df3aa2.png)

#### ROI of Drama Sci-Fi Thrillers by Release Month
![DST_Release Month](https://user-images.githubusercontent.com/120589094/215112651-a504e90b-d10c-4638-9915-f77daa785666.png)

## Conclusion
Based on ROI trends in the industry, I would recommend making a Drama Sci-Fi Thriller film due to a rising ROI trend, consistently high average ratings, and low competition. As director, I would recommend M. Night Shyamalan, who is very successful when directing thrillers. Finally, I would recommend releaseing this film in January to increase our chance at success.
