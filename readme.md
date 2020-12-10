# Endangered Languages Exploration
## by Jean Pierre Simons Rondona


## Dataset
This dataset was published by The Guardian (<a href='https://www.theguardian.com/news/datablog/2011/apr/15/language-extinct-endangered#data'>here</a>). It aims to provide data insights on how many endangered languages there are in the World and what are the chances they will die out completely.


UNESCO provide a classification system to show just how 'in trouble' the language is:

Vulnerable - most children speak the language, but it may be restricted to certain domains (e.g., home)
Definitely endangered - children no longer learn the language as a 'mother tongue' in the home
Severely endangered - language is spoken by grandparents and older generations; while the parent generation may understand it, they do not speak it to children or among themselves
Critically endangered - the youngest speakers are grandparents and older, and they speak the language partially and infrequently
Extinct - there are no speakers left
In addition, I also included information on World Population by country from Worldometer via Kaggle (<a href='https://www.kaggle.com/tanuprabhu/population-by-country-2020'>here</a>).

In the study below I intend to answer the following questions:

What is the average amount of speakers in the world's endangered languages?
Do the amount of speakers directly correlate to a languages likelihood of extinction?
Does a language's world location impact it's likelihood of extinction?


## Summary of Findings

Multiple steps were taken to clean & tidy the data:
* There were extinct languages with practicing speakers, those were removed from the dataset.
* The countries per language were comma separated, the data was split into different rows.
* It was noticed that there are a very large number of languages spanning a very large number of countries. In order to visualize the data more clearly there were several times I either excluded extinct data or zoomed in to the data via a subset.

## Key Insights for Presentation

* Most endangered languages have between 300 - 10,000 fluent speakers.
* There appears to be a correlation between where the language is practiced and it's likelihood to be in critical endangerment. Most notably the South Western and South Eastern hemispheres have very low number of practicing speakers for critically endangered languages.
* The Northern Eastern hemisphere has the most extinct languages.
