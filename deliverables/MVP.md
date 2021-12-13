# MVP
Matt Ryan



For my MVP, I have created a rough prototype data pipeline for my project. The pipeline is composed of a series of API calls to the Riot Games API in the form of a series of custom functions, which ultimately output a dictionary object composed of online-player-name as keys and list-type objects of in-game characters played over the last 20 games as values. The functions will ultimately collect records for all players in the Challenger, Grandmaster, Master, and Diamond ranks on the leaderboard (totalling around 15,000-16,000 players/records).

With this dataset, I am currently building a recommender system that will accept the user's League of Legends in-game name and finds players on the leaderboard with a similar list of in-game characters (or champions) played (also known as a champion pool) and recommends new champions for the user to try.

Currently I am limited in my scale of data collection by hard limitations on frequency of API calls, and am only working with a development dataset of around 300 records. The end goal, however, is to apply for a product key after demonstrating a functioning recommender system, which will allow for much quicker collection of data using the API, and adjust the pipeline accordingly to house/process the larger scale of data (ie use of PySpark for better scalability than pandas, storage of data on AWS, etc). 
