# Microsoft-AI-Challenge-2018

https://competitions.codalab.org/competitions/20616

## Introduction
As search engines evolve to respond to speech inputs and as usage of ambient devices like speakers grow in the society etc. returning 10 blue links to a search query is not always desirable. At Bing.com, our aim is to serve answer to questions directly without users having to search through the 10 blue links. Try searching “what is cricket ball made of” in Bing and a direct answer pops up.

## Problem statement:
 
Given a user query and candidate passages corresponding to each, the task is to mark the most relevant passage which contains the answer to the user query.
 
## Data
In the data, there are 10 passages for each query out of which only one passage is correct. Therefore, only one passage is marked as label 1 and all other passages for that query are marked as label 0. Your goal is to rank the passages by scoring them such that the actual correct passage gets as high score as possible.

## Evaluation
We provide three types of data sets to the participants -- i) the labelled train data for training your models and doing validations ii) the unlabelled eval1 data against which you submit your predictions during the contest and iii) the unlabelled eval2 data against which final predictions are submitted.
