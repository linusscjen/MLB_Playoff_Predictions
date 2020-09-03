# MLB Playoff Predictions
Predicting which MLB teams will make the playoffs

Hi everyone, and welcome to my first project!

The conglomeration of files may seem daunting at first, but this explanation will hopefully cover all your questions.

This project first came about when Samuel In (https://linktr.ee/samuelin?fbclid=IwAR1HS47i7sVsvO7E8OKT5EKpV6zQNXHnvsK-S8ZfZjwZUcqwc1i3tInr-5E) asked me if I could figure out a way to predict the World Series champions based off how much a team spent on their players. While I never got arond to answering his question, I decided to try and predict what teams would make the playoffs instead. Here are the key questions that to address in this project:

1. What models, with the best accuracy, precision, recall, and F1 score, would perform the best at predicting which teams made the playoffs?
2. Do models perform better when trained on the raw, per game statistics, or perform better using ranked statistics compared over each season?
3. Is there a subset of data, for example using 10 years of data before predicting the next season, that improves a model's metrics? Following this, are there trends in baseball that may predict playoff appearances over a given era? Or does using the historical data create the best model?
4 Are there certain variables that are the best indicators to determine if a team will make the playoffs or not? And if so, what statistics?

To those only interested in my findings, I recommend referring to [Summary.pdf](./Summary.pdf).

For those interested in the code, refer to [Analysis_Code.Rmd](./Analysis_Code.Rmd).

For those interested in the output of the code (as a pdf), refer to [Analysis_Output.pdf](./Analysis_Output.pdf).

Lastly, if you're interested in how the data was scraped and transformed to per game stats, refer to [Data Scraping.Rmd](./Data Scraping.Rmd). Or, you can look into the [full_data.csv](Datasets/full_data.csv) to look at the data used in our models. All other datasets are either subsets of this, or converted to either per game stats ([pergame_stats_fullsub.csv](Datasets/pergame_stats_fullsub.csv)) or ranked stats ([ranked_fullsub.csv](Datasets/ranked_fullsub.csv) 

Anyways, hope you enjoyed this!
