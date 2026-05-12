# sentiment-analysis-word-cloud
## Problem Statement: The purpose of this project is to perform sentiment analysis on a text-based CSV dataset. The goal is to analyze the overall emotional tone of the documents, identify whether the text is positive, negative, or neutral, and visualize the most common words using a word cloud.

#dataset:
The dataset used for this project was selected from the datasets link provided in class.

#data Loading: The CSV file was loaded into Python using pandas.

#Data Processing:
- Loaded the CSV dataset
- Selected the text column for analysis
- Checked for missing values
- Removed or handled blank text entries
- Cleaned the text data
- Prepared the text for sentiment and emotion analysis

#Models:This project used sentiment analysis at the document level.

The analysis classified the document text into:
- Positive
- Negative
- Neutral

#Type of Algorithm
This project uses Natural Language Processing and rule-based sentiment analysis.
Sentiment analysis was chosen because it is useful for understanding opinions, emotions, and attitudes in text data.

#Model Outputs
- Document-level sentiment analysis
- Word cloud visualization
- Bar graph showing positive, negative, and neutral percentages
- Bar graph showing emotion percentages


#Word Cloud: The word cloud shows the most frequent words in the dataset. Larger words appeared more often in the document text.

#Sentiment Percentages: The sentiment bar graph shows the percentage of text classified as positive, negative, and neutral.

#Emotion Percentages: The emotion bar graph shows the percentage distribution of emotions identified in the document text.


## Limitations:
- Sentiment analysis may not always detect sarcasm or context correctly
- Text cleaning can affect the final results
- The accuracy depends on the quality of the dataset and the sentiment analysis method used
- Some words may have different meanings depending on the context
