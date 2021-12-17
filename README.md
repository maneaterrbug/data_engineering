# Building a Champion Recommender Application for League of Legends

## Abstract

The goal of this project was to build a webapp League of Legends champion recommender system on top of an end-to-end data-pipeline for continuous collection, transformation, and modelling of data.  The data pipeline collected match-data from online matches using the Riot Games API, stored said data in a SQL database, and preprocessed the data before being used for modelling.  This data was then used to train a recommender system using neural collaborative filtering (NCF). Development on a Streamlit application was then begun.

## Design

Since its initial release in 2009, the video game League of Legends (LoL) quickly became and has remained among the most popular and widely played video games in the world. With *x* number of matches played every day, a wealth of statistical data is available to the public via the Riot Games API. This data has been used and presented to end-users in many widely-used stat-tracking apps such as [op.gg](https://na.op.gg/) and [u.gg](https://u.gg/).

Many of these sites are very handy tools and excel at stat-tracking and presentation, but in using them I found myself wanting more in-depth gameplay analysis. With that in mind, I wanted to explore the potential for deep learning to provide this analysis and build a champion recommender app.

## Data

The data used in this project is collected using the Riot Games API and is composed of match-data for players in the top 4 rank divisions of the LoL ranked ladder (approximately the top 1.85% of players, or ~55,000 players). For each player, data from their 50 most recent ranked matches is collected, totalling around 2.75 million records.

## Algorithms




## Technologies

- PostgreSQL
- Google Cloud SQL server
- Python (PyTorch, PySpark)
- Streamlit


## Communication

Currently the webapp has not been deployed. 
