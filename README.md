
# Covid-19 Sentiment Analysis**

**Context**

I collect recent tweets about the COVID-19 vaccines used in entire world on large scale, as following:

- Pfizer/BioNTech;
- Sinopharm;
- Sinovac;
- Moderna;
- Oxford/AstraZeneca;
- Covaxin;
- Sputnik V.

**Data collection**

The data is collected using tweepy Python package to access Twitter API. For each of the vaccine I use relevant search term (most frequently used in Twitter to refer to the respective vaccine)

**Data collection frequency**

Initial data was merged from tweets about Pfizer/BioNTech vaccine. I added then tweets from Sinopharm, Sinovac (both Chinese-produced vaccines), Moderna, Oxford/Astra-Zeneca, Covaxin and Sputnik V vaccines. The collection was in the first days twice a day, until I identified approximatively the new tweets quota and then collection (for all vaccines) stabilized at once a day, during morning hours (GMT).

**Inspiration**

You can perform multiple operations on the vaccines tweets. Here are few possible suggestions:

- Study the subjects of recent tweets about the vaccine made by various producers;
- Perform various NLP tasks on this data source (topic modelling, sentiment analysis);
- Using the COVID-19 World Vaccination Progress (where we can see the progress of the vaccinations and the countries where the vaccines are administered), you can study the relationship between the vaccination progress and the discussions in social media (from the tweets) about the vaccines.



*Kaggle Dataset*
- https://www.kaggle.com/c/tweet-sentiment-extraction

- https://www.kaggle.com/gpreda/all-covid19-vaccines-tweets

