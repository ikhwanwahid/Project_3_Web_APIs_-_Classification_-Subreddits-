### Project 3: Web APIs & Classification (Subreddits)

## Problem Statement

We are the good folks at Askscience subreddit forums, bringing to you up and coming and interesting Science
facts, news fresh off the oven for your reading pleasure.
Nowadays with the many cross-overs that happen between fields, topics that sound related but are not actually
related or relevant to our cause have seemed to pop up into our subreddit feeds. More prevalantly , the posting
of troll posts, or jokes mocking Science or in no way relevant to Science in anyway.
Our job now is to invent a ML algorithm to correctly dectect such posts that dont belong,and subsequently
filter,remove them from our feed.

## Executive Summary

Reddit is an American social news compiler,web content rating and discussion website. Members submit content to the site such as links,text posts and images which are upvoted or downvoted by the community. Posts are organized by subject into user-created boards called "subreddits", which cover a variety of topics including news, science, movies, video games, music, books, fitness, food, and image-sharing.

As it is an open community, everyone can post whenever/wherever and whatever they want. Most often then not random posts unrelated to the subreddit will appear. While the immediate solution is for moderators to spot them and remove, how efficient can this process be? There is only so much a modertor can detect, before the amount of posts posted becomes too overwhelming for it to be done manually.

Thus arrives the need for automation, filtering out the irrelevant posts and keeping the subreddit accurate. Our job now is to invent a ML algorithm to correctly dectect such posts that dont belong,and subsequently filter,remove them from our feed.

## Contents (Data-Scraping)

Importing the Relevant Libraries
Anything and everything about Subreddit 1
Cleaning the Data
Function to scrape content from Askscience
Anything and everything about Subreddit 2
Function to scrape content from Jokes

## Contents (Data Cleaning and Munging)

Importing the Relevant Libraries
Loading the Data
EDA

## Contents (Modeling)

Importing the Relevant Libraries
Final EDA
Using Count Vectorizer
Mode1 1: Using The NaiveBias Bernoulli
Gridsearch + BernoulliNB function
Model 2: Using The Logistic Regression
Gridsearch + Logistic Regression function
Reapeating Process Using TF_IVF
Findings and Conclusions


Our model proved to be quite effective in classifying words from both subreddits. This model relies on both the words in sub-text as well as the title. future works could maybe delve into looking into building separate models for sub-text as well as titles. Moreover, these models have to constantly be retrained, due to the emergence of new urban words, abbreviations. They may or may not be relaterd to ASKSCIENCE, and simply throwing them out will just make future models less accurate

---

## Why we choose this project for you?
This project covers three of the biggest concepts we cover in the class: Classification Modeling, Natural Language Processing and Data Wrangling/Acquisition.

Part 1 of the project focuses on **Data wrangling/gathering/acquisition**. This is a very important skill as not all the data you will need will be in clean CSVs or a single table in SQL.  There is a good chance that wherever you land you will have to gather some data from some unstructured/semi-structured sources; when possible, requesting information from an API, but often scraping it because they don't have an API (or it's terribly documented).

Part 2 of the project focuses on **Natural Language Processing** and converting standard text data (like Titles and Comments) into a format that allows us to analyze it and use it in modeling.

Part 3 of the project focuses on **Classification Modeling**.  Given that project 2 was a regression focused problem, we needed to give you a classification focused problem to practice the various models, means of assessment and preprocessing associated with classification.   
