# NLP-Disaster-Tweets-Kaggle-Mini-Project
In this challenge, we are tasked with building a machine learning model that can identify whether a tweet is about a real disaster or not. While humans can quickly infer meaning from context, sarcasm, or tone, machines require careful processing and modeling to make such distinctions. This is a binary text classification problem within the field of Natural Language Processing (NLP).

NLP focuses on enabling machines to understand, interpret, and generate human language. This project specifically requires understanding short, informal, and noisy text data (i.e., tweets), which presents unique challenges such as ambiguity, slang, and limited context.

**Dataset Summary:**
The dataset contains 7,613 labeled tweets. Each tweet is manually classified as either:

- 1: Related to a real disaster

- 0: Not related to a real disaster

**Features:**
- id: Unique identifier for each tweet
- keyword	Disaster-related: Keyword in the tweet (optional)
- location: Location where the tweet was posted (optional)
- text: The full tweet text
- target: Binary label indicating disaster relevance

**Data Characteristics:**
- Size: 7,613 rows, 5 columns
- Text Data: The text column is the primary focus for NLP modeling
- Missing Data: keyword: 61 missing entries, location: 2,533 missing entries
- Target Distribution: Fairly balanced between disaster and non-disaster classes
