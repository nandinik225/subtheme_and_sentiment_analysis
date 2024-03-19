# subtheme_and_sentiment_analysis

The aim of this project is to analyze the garage reviews to extract subthemes and sentiments from each review.

In this I extracts potential subthemes from a review text based on its part-of-speech tags. It iterates through each word and appends it to a temporary list if it represents a noun, adjective, adverb, or verb. Once a complete subtheme phrase is formed, it is stored. After processing all words, sentiment analysis is performed on each subtheme to label it as positive, negative, or neutral. Finally, a dictionary is returned containing the identified subthemes along with their sentiment labels.
