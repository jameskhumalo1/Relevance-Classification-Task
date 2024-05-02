Dataset Description
The document is composed of several fields (doc_id, author, title, byline and body) and the user's information need (topic_id, query_title, description, narrative). You can you as much of the document text as you like and as much of the information need text as you need. You need to judge the relevance of the information need to the documents text.

Files
relevance_train.parquet - the training set
relevance_test.parquet - the test set
relevance_test_sample_answer.csv - a sample submission file in the correct format

Columns
doc id - the id of document (and the id to be used for the answers)
author - the author name, if there is one (text)
title - the title of the article (text)
*. byline - the byline of the article (text)
body - the body of the article (text)
topic_id - the topic number
topic_title - the title of the topic describing the information need
description - describes what the document should contain to be relevant
narrative - describe what is relevant
'judgment' - 0 if the document doesn't match the topic, 1 if relevant.

Download the dataset frm the following URL:
https://www.kaggle.com/competitions/cs985-987-relevance-prediction-2024/data
