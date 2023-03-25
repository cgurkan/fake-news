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

## Output data format

- public_id- Unique identifier of the news article
- predicted_rating- predicted class
