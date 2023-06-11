# Multi-class fake news detection of news articles

Problem Definition : Problem Definition: Given the text of a news article, determine whether the main claim made in the article is _true_, _partially true_, _false_, or _other_ (e.g., claims in dispute) and detect the topical domain of the article. This task will run in English and German.

## Dataset

https://zenodo.org/record/6555293

## Input Data

The data will be provided in the format of Id, title, text, rating, the domain; the description of the columns is as follows:

- ID- Unique identifier of the news article
- Title- Title of the news article
- text- Text mentioned inside the news article
- our rating - class of the news article as false, partially false, true, other

## Abstract
This study focuses on detecting fake news, which refers to disseminating fabricated stories lacking verifiable information, sources, or quotes. 
With the widespread use of the internet and social media, the impact of fake news on society has become more pronounced. Our research addresses
this issue by developing machine learning and deep learning models capable of classifying news claims into four distinct categories. We utilized 
the CT-FAN dataset from the Check-That!2022 competition and focused explicitly on linguistic features for analysis. Experimental evaluations were
conducted using both traditional Machine Learning algorithms and Deep Learning algorithms. Among them, the BiLSTM model outperformed the
traditional machine learning algorithms, achieving a f1-macro score of 0.26.
