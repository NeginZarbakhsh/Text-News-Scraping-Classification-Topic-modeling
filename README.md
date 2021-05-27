# Text-News-Scraping-Classification-Topic-modeling
# Overview:
The objective of this assignment is to scrape a corpus of news stories from a set of web pages, pre-process the data, and evaluate the performance of both binary and multi-label text classification algorithms on the data. The news stories are archived by month at the link below and each story has been assigned one of 9 news categories.
http://mlg.ucd.ie/modules/COMP41680/assignment2/index.html
Based on this data, you should complete the three tasks listed below. The assignment should be implemented as a single Jupyter Notebook (not a script file). Your notebook should be clearly documented, using comments and Markdown cells to explain the code and results.
Task 1. Data Collection
Select three of the 9 news categories: [Books, Business, Film, Life-and-Style, Music, Politics, Sport, UK-News, US-News]
From the link above, retrieve details regarding all stories corresponding to your three selected categories, covering all months January to December 2020. For each story you will need to parse the HTML to extract the following information:
The title of the news story.
The short text snippet for the story which represents the start of the complete news article.
The category label assigned to the story.
Note: You do not have to retrieve the full linked article from The Guardian, only the data on the mlg.ucd.ie website.
Store the parsed data that you have collected in an appropriate format.
Task 2. Binary Text Classification
Load the data from Task 1 and create a set of documents, one per news story. Each document should consist of the concatenation of the story’s title and text snippet. Each document should also have a class label, based on the story’s news category.
For each unique pair of categories (A,B) from the three that you selected:
Apply appropriate preprocessing steps to create a numeric representation of the documents from these two categories, suitable for classification.
Train a classification model using a binary classifier of your choice, which can distinguish documents in category A from documents in category B.
Test the predictions of the classification model using an appropriate evaluation strategy. Report and discuss the evaluation results.
Task 3. Multi-Class Text Classification
Using all three categories (A,B,C) that you have selected:
Apply appropriate preprocessing steps to create a numeric representation of the documents for these three categories, suitable for classification.
Train a classification model using a multi-class classifier of your choice, which can distinguish documents from the categories A, B, and C.
Test the predictions of the classification model using an appropriate evaluation strategy. Report and discuss the evaluation results.
