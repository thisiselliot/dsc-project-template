# Major Motion Picture Box Office Analysis

**Authors:** Billy Lopez, Elliot Macy


## Overview

This project analyzes 20 years of movie data and offers strategic insights for Microsoft to launch a financially sucessful film studio.


## Business Problem

We answer three questions relating to box office profit and revenue for major motion pictures from the past 20 years.

1. How does the correlation between runtime and revenue vary between different MPAA ratings?
2. Which months of the year and days of the week are the optimal releases dates?
3. Do the optimal release dates differ from foreign to domestic audiences?

Descriptive analysis of the relationshipes between profit and revenue, on the one hand, and release dates and runtimes, on the other, points toward very different approaches depending on MPAA rating and audience.

Namely, revenues increase with strciter MPAA ratings from G to PG-13 but fall dramtically for R and NC-17 ratings. Optimizing runtimes for maximum revenue depends on the target rating: longer movies do better with stricter ratings.

Moreover, profits peak yearly for movies released in June and December and peak weekly for Tuesday and Wednesday releases. However, upon further analysis, we found that movies intended for international audiences peak monthly in July only and weekly on Mondays.


## Data

Our analysis utilizes data obtained from Rotten Tomatoes (RT) and The Movie Database (TMDB). The combined dataset represents the profit, revenue, and other key features of all 21st century major motion pictures. We focus on release date, audience, rating, and runtime, and how these features relate with profit and revenue as well as each other.


## Methods

To prepare our data for analysis we dropped the unrelated columns and engineered several new features. After selecting our features, we dropped movies missing quantitative values. For missing categorical values, we either dropped the movie in question or replaced the value with 'None'.


## Results

We began by modeling the relationship between revenue and runtime as well as profit and release date. Finding these results insightful, we expanded our analysis to include additional features: runtime, in relation to revenue and rating, and audience, in relation to profit and release date.


### Visual 1
![graph1](./images/viz1.png)

## Conclusions

As demonstrated, revenues increase with strciter MPAA ratings from G to PG-13 but fall dramtically for R and NC-17 ratings. Optimizing runtimes for maximum revenue depends on the target rating: longer movies do better with stricter ratings.

Moreover, profits peak yearly for movies released in June and December and peak weekly for Tuesday and Wednesday releases. However, upon further analysis, we found that movies intended for international audiences peak monthly in July only and weekly on Mondays.

Our analysis leads to several reccomendations for Microsoft to maximize their film studio's profit and revenue.

Look for projects likely to receive pg-13 ratings while ensuring they are not rated R.
Restrict G and PG rated movies to shorter durations than movies rated PG-13 and R.
Plan domestic release dates for Tuesdays and Wednesdays in June and January. For interntational markets, plan releases for Mondays in July.


## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact Billy and Elliot.

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
