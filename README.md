# Sentiment towards Artificial intelligence on social media

![image](https://user-images.githubusercontent.com/121023453/225805568-765b1375-cfac-4a08-8327-eabff0ffb14d.png)


## Introduction
With the advancement of technology, we are seeing more and more artificial intelligence (AI) tools being developed that are becoming increasingly accessible to the general public. From self-driving cars to tools that can generate realistic pictures or art, and language models like ChatGPT, AI is becoming an integral part of our lives. However, with this increasing integration, there is a growing concern among people about the potential negative impacts of AI. In this analysis, we will explore people's sentiment towards AI on social media platforms such as Reddit, YouTube, and LinkedIn and the way people engage with it.

## Methods
We collected over 150.000 comments related to AI from popular social media platforms including Reddit, YouTube, and LinkedIn using web scraping techniques.

After scraping data of 150.000 comments related to AI on Reddit, YouTube, and LinkedIn, we used the Natural Language Toolkit (NLTK) library's SentimentIntensityAnalyzer to perform sentiment analysis on each comment. This tool calculates a sentiment score for each comment between -1 (most negative) and 1 (most positive) based on the presence of positive and negative words in the text.

For example, a comment like "I love artificial intelligence so much, it is the best thing ever!" would receive a high score of 0.9, while a comment like "Artificial intelligence is horrible, I hate it!" would receive a low score of -0.7. The sentiment score can help us understand the overall sentiment of the comments and whether people have positive or negative opinions about AI.

After scoring the sentiment of each comment, we transferred the cleaned and structured data to a MySQL database. Using SQL queries, we were able to extract insights from the data more easily. For example, we were able to analyze the sentiment of comments related to specific subjects such as Alexa, ChatGPT and Dall-E.

## Charts
(Link to Tabeleau: https://public.tableau.com/app/profile/tim.kuijten/viz/AISocialMedia/Story1?publish=yes)

## Conclusions
In conclusion, our analysis of 150.000 comments related to AI on social media platforms shows that people have a mixed sentiment towards AI. While there are some positive comments, there are also negative comments. LinkedIn users have the most positive sentiment towards AI, followed by YouTube and Reddit. The sentiment on these platforms has been relatively stable over the years, with no significant changes in sentiment. Moreover, we found that posts with a positive sentiment receive more passive and active engagements, indicating that people are more likely to engage with positive AI-related content. Overall, our analysis provides insights into people's opinions on AI on social media platforms and highlights the need for continued discussions about the positive and negative impacts of AI.

                                                   AI won't replace you,
                                                  a person using AI will.
                                                 - Someone in my dataset
