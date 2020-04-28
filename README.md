# Predicting Goalscorer in Football
### Background
I built this model as my final project whilst at Flat Iron Data Science School.
### Goals of the project
The goal of this project was to build a fully automated model that would pick profitable betting selections on goalscorers.
### Methodology
I first started by scraping shot location data off ESPN, using the match commenataries for each match. I used scrapy to do this. I was able to scrape over 600,000 shots, and this only took 3 hours to do.
My next step was to clean and format the data so it was suitable to carry out statsictial modelling. I then carried out a combination of Linear Regression, Logisitical Regression, and Monte Carlo Simulations. 
### Results
After many tweaks to the model I was able to back test the data and show a ROI of 152 bets over 29.7%.
UPDATE: I have now been using this model for 6 weeks since publishing these statistics, and I am showing a ROI of 22% over 400 bets.
### Further Thoughts
Although ESPN's data sources are very comprehensive, I believe that the whoscored.com data may be better, so this may be a change I may make in the future.

### Questions
If you have any queries on this please contact me - joepeirson@gmail.com

### Notes
I have not added all my code for this project as I didn't want anyone to replicate my model but I am happy to talk through my code if there is interest.
