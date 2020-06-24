# Apple-vs-Samsung-with-higher-customer-satisfaction

## Introduction

Every business in the world, relies on clients as their source of making profits. Customer satisfaction is one of the most important criteria that any business would like to excel in. Our primary focus, in this project, is to see whether Apple or Samsung, despite the brand value held, is successful in retaining the customers' trust and satisfaction.
Apple is a multinational company headquartered in California, United States of America, that designs, manufactures and sells consumer electronics and computer software. The company's most in-demand hardware products include Iphone smartphones, Ipad tablets, Ipod portable media players, Apple Watch smartwatches and Mac laptops. Apple is the world's largest company in terms of revenue and is one of the world's most valued brands with a high level of brand loyalty.Samsung Electronics is a multinational company headquartered in Suwon, South Korea. It is world's largest manufacturer of mobile phones and smartphones. The company's most in-demand electronic products include tablets, smartphones, smartwatches and smart television.

People these days on social media tend to use text along with some emojis/images/gifs rather than only text. This additional image field is useful as it helps the user express his emotions – a picture speaks a thousand words. We plan to extract the emojis from the tweet text and perform sentiment analysis on it. With the help of this we can find the general customer satisfaction for these two Tech giants.

## Data Collection

Using the powerful “Tweepy” API, we extracted tweets using “samsung” as the search query. The results were returned individually in “.json” format. These individual “.json” objects are collected and stored in a folder. This folder has multiple .json files having “Samsung” tweets. The same process was followed to extract tweets for Apple, where “apple” was used as the search query.

A “restful” approach was used to extract the twitter data. The REST APIs are very useful and easy to implement if we only want to search for Tweets authored by a specific user or about a particular topic. It is a best-effort retrieval that doesn’t guarantee completeness, however, for the purpose of this assignment the more random the order of tweets, the more it relates to the real world population.

## File Description

