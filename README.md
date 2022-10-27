# Sentiment and Time series Analysis for Pfizer &amp; BioNTech COVID-19 Vaccine (Presented on 05/06/2021)

# Executive Summary
COVID-19, is an ongoing global pandemic of coronavirus disease 2019 caused by severe acute respiratory syndrome coronavirirus 2 (SARS CoV-2). The virus was first identified in Dec 2019 in Wuhan, china and on 11th of Mar 2020 WHO declared it a pandemic. With more than 147 million confirmed cases and more than 3.12 million deaths, this has been one of the deadliest pandemics in history. Various COVID-19 vaccines have been developed to provide acquired immunity against this virus and as of today, 13 vaccines have been authorized by at least one national regulatory authority for public use all over the world. CDC has authorized and recommended 3 vaccines in the United States to prevent COVID-19: 1. Pfizer-BioNTech, 2. Moderna and 3. Johnson & Johnson/Janssen.
On December 11,2020, the U.S. Food and Drug Administration issued the first emergency use authorization (EUA) that allowed the Pfizer-BioNTech COVID-19 Vaccine to be distributed in the U.S. There has been a fair amount of concern regarding this vaccine and it will be critical for public health authorities to be able to effectively counter negative public attitude towards the vaccine.
In this report, sentiment and time series analysis has been used to answer three important questions regarding Pfizer-BioNtech COVID-19 vaccine:
1. Is willingness to be vaccinated increasing or decreasing?
2. What are some of the reasons for public hesitancy about getting vaccinated?
3. What motivates people most to get vaccinated?
From this analysis, we can conclude that, people are generally accepting towards Pfizer-BioNTech COVID-19 vaccine and are willing to get vaccinated. People having negative attitude towards the vaccine are more concerned about the side effects, it’s safety and allergies. People showcasing positive sentiment seem to believe in scientific studies carried out to develop the vaccine, approvals given and efficacy of the vaccine against COVID-19. This analysis would help public health authorities design and plan vaccine campaigns to increase public inoculation by focusing their ads and campaigns on concerns that people have.

# Data Description 
Two datasets have been used for this analysis.
1. Pfizer & BioNTech Vaccine Tweets - This dataset includes tweets about Pfizer-BionTech Vaccines from 12 Dec 2020 to 15 Mar 2021. It provides 6818 records/observations with 16 variables such as id, user_name, user_description, user_followers, date, text, hashtags, retweets etc.
2. COVID-19 World Vaccination Progress - This dataset includes the Daily and Total Vaccination data for COVID-19 from 19 Dec 2020 to 15 Mar 2021, in the World. It provides 6517 records/observations with 15 variables such as country, date, vaccines, total_vaccinations, people_vaccinated, people_fully_vaccinated, daily_vaccinations etc.

# Hypotheses :
Hypothesis 1: The dominant sentiment about the vaccine is Positive.

Hypothesis 2: The daily average sentiment follows an upward trend.

Hypothesis 3: The sentiment series is stationary and can be used to forecast average sentiment score in the future.

Hypothesis 4: There is a strong correlation between the average sentiment score and the percentage of people vaccinated.

Hypothesis 5: There is a strong correlation between the average sentiment score and daily number of tweets.

# Skills used - 
Programming Language - R

Data Science Skills - Preprocessing, Handling missing values, EDA, Hypothesis Testing, ARIMA,  Text Analytics (Vader Sentiment Analysis, Wordcloud)

# Future Opportunities :
While this analysis may seem thorough, there are a few opportunities to improve this analysis further. These are listed as follows:
• As can be seen from the wordcloud of people having Neutral sentiment, Pfizer-BioNTech as an individual brand has not much impact. Pfizer-BioNTech can use this analysis to improve their public reach and emphasize how their vaccine is better as compared to other vaccine manufacturers.
• This analysis can be extended to other vaccines used in USA like Moderna.
• Vaccine manufacturer’s can approach people for next clinical trials if their overall sentiment about the vaccine has been positive.

# Conclusion :
Using the Pfizer and BioNTech Vaccine Tweets and Vaccination progress datasets, we conclude:
1. The willingness to get vaccinated has been increasing, however, in future the willingness seems to remain constant.
2. The percentage of people vaccinated and daily number of tweets do not motivate people to get vaccinated. What motivates them is the scientific data, information about the approvals given for the vaccine and efficacy of the vaccine. We also see that people who got vaccinated are more confident about the vaccine. These people can be approached to advocate about the vaccine through social media.
3. Some of the reasons for the public hesitancy towards Pfizer-BioNtech and vaccines in general, are concerns like safety, severe side effects and allergies. Thus, the public health authorities should design and plan their campaigns in such away that they emphasize more on the concerns people have. They should provide more information and transparency on the efficacy and approval process through social media so as to reach maximum public.

# References and Sources :
1. Pfizer and BioNTech Vaccine Tweets - This dataset has tweets about Pfizer-BionTech Vaccines. https://www.kaggle.com/gpreda/pfizer-vaccine-tweets
2. COVID-19 World Vaccination Progress - This dataset has data about Daily and Total Vaccination for COVID-19 in the World https://www.kaggle.com/gpreda/covid-world-vaccination-progress/code?datasetId=1093816&language=R
3. https://en.wikipedia.org/wiki/COVID-19_recession#:~:text=The%20COVID%2D19%20pandemic%20is,30%20Januar
4. https://www.cdc.gov/coronavirus/2019-ncov/vaccines/different-vaccines/how-they-work.html
5. https://www.pfizer.com/news/press-release/press-release-detail/pfizer-and-biontech-confirm-highefficacy-and-no-serious
6. https://www.theguardian.com/world/2021/feb/25/pfizer-covid-vaccine-94-effective-study-of-12mpeople-finds
