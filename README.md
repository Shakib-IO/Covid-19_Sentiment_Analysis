
# [Covid-19 Sentiment Analysis](https://www.hindawi.com/journals/cmmm/2021/4321131/)

> The given challenge is to build a classification model to predict the sentiment of Covid-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done. We are given information like Location, Tweet At, Original Tweet, and Sentiment.

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


---

**Abstract**

Abstract: This COVID-19 pandemic is so dreadful that it leads to severe anxiety, phobias, and complicated feelings or emotions. Even after ‘Vaccination’ against Coronavirus has been initiated, people’s feelings have become more diverse and complex, and our goal is to understand and unravel their sentiments in this research using some 'Deep Learning' techniques. Social media is currently the best way to express feelings and emotions, and with the help of it, specifically ‘Twitter’, one can have a better idea of what’s trending and what’s going on in people's minds. In this research, the timeline of the collected tweets was from December’21 to July’21, and contained tweets about the most common vaccines available recently from all across the world. The sentiments of people regarding vaccines of all sorts were assessed by using a Natural Language Processing (NLP) tool named ‘VADER’. By initializing the sentiment polarities into 3 groups (positive, negative and neutral), the overall scenario was visualized here and our findings came out as 33.96% positive, 17.55% negative and 48.49% neutral responses. Besides, the timeline analysis shown in this research, as sentiments fluctuated over time between the mentioned timeline above. Recurrent Neural Network (RNN) oriented architectures such as LSTM and Bi-LSTM were used to assess the performance of the predictive models, with LSTM achieving an accuracy of 90.59% and Bi-LSTM achieving an accuracy of 90.83%. Other performance metrics such as Precision, Recall, F-1 score and Confusion matrix were also shown to validate our models and findings more effectively. This study will help everyone to understand public opinion on the COVID-19 vaccines and have an impact on the aim of eradicating the Coronavirus from our beautiful world.

---

**Overall Architecture**

<img src = "https://github.com/Shakib-IO/Covid-19_Sentiment_Analysis/blob/main/images/Covid-19.png">
