# MLB_Playoffs
Predicting which MLB teams will make the playoffs

Hi everyone, and welcome to my first project!

The conglomeration of files may seem daunting at first, but this explanation will hopefully cover all your questions.

This project first came about when Samuel In (https://linktr.ee/samuelin?fbclid=IwAR1HS47i7sVsvO7E8OKT5EKpV6zQNXHnvsK-S8ZfZjwZUcqwc1i3tInr-5E) asked me if I could figure out a way to predict the World Series champions based off how much a team spent on their players, either through the amount spent, or their rank, in comparison with other MLB teams. While I never answered this question specifically, I decided to delve a little bit more into the MLB to see whether or not I could predict if a team could make the playoffs.

Why the playoffs, you might ask? Well, determining the winner from 1 of the 30 current teams available, seemed like a daunting challenge as it was, and models would often have high accuracy scores because they "correctly" predicted that a team would NOT be the World Series winner. Thus, I decided to create models to predict what teams would make the playoffs (including the wild card games) instead. Sam had mentioned that unlike the NBA, all teams that made the playoffs had a good chance of winning it all.

That being said, here are the questions I wanted to address in this project:

1. What models, with the best accuracy, precision, recall, and F1 score, would perform the best at predicting which teams made the playoffs?
2. Is there a subset of data, for example using 10 years of data before predicting the next season, that improves a model's metrics? Following this, are there trends in baseball that may predict playoff appearances over a given era? Or does using the historical data create the best model?
3. Are there certain variables that are the best indicators to determine if a team will make the playoffs or not? And if so, what statistics?
4. Do models perform better when receiving the raw data, I.E. the per-game statistics, or does ranked data, I.E. a ranking of each team's stats, create the best models overall?

File explanation:

Data scraping can be found under the file "Data_Scraping.RMD". All my data was found from baseball-reference.com.

My first trial (which took the majority of my 2020 summer), can be found under "Analytics.RMD". This file is a precursor as to the steps taken in my real analysis, as this is very messy, but helped me learn how to use certain functions to tune hyperparameters of functions.

The complete analysis of all the models, different metrics, and comparisons can be found under "Analytics2.RMD". This was done in 7 days due to time constraints. For those wondering how I created and scored my models, as well as tuning hyperparameters, this will be your place to go. However, this is 63 pages long (around 2000 lines of code, comment, etc.), and may be mildly difficult for those who aren't used to looking at code for hours on end.

Lastly, head towards "kdslkdjffd.slkdjfksdljfsd" to find a summary and conclusion of what was done in "Analysis.RMD", as well as my limitations (like an actual research paper). This will report my findings as to the best models, show some graphs, and explain in detail some of my findings, and flaws to my design.

Hopefully you enjoyed yourselves, and found this interesting!

