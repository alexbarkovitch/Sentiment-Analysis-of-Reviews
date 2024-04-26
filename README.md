# Sentiment-Analysis-of-Reviews
Alex Barkovitch CMP 262 Project #3 4/22/2024
This is a repository that contains the files needed for this project. It contains the python code as well as a png file for the wordcloud mask. This code uses the Yelp Fusion API to perform sentiment analysis on reivews. I'll look at reviews for nightclubs in New York, displaying data for 30 businesses. I will display the business name, category, rating, review count, and 3 reviews for each nightclub. I'll use both the default analyzer and NaiveBayesAnalyzer, adding up the values of the sentiment values for each and creating donut charts to compare the results. I will also create a WordCloud of the top 20 words used in all the reviews, and create a dataframe that allows us to see the top rated nightclubs and what categories are rated highest.


Assignment Details:
Complete:

In a Jupyter Notebook, perform sentiment analysis on reviews using an API such as Yelp Fusion.

Your analysis should include the following:

Introduction (in Markdown): an overall question that you have about your dataset, along with your name and date and description of the problem and summary of your solution.
Use the API to search for at least 60 reviews about your topic. (Note Yelp Fusion only delivers 3 reviews per business.)
Clean your reviews as needed.
Perform sentiment analysis on these reviews, displaying a donut chart of the positive, negative, and neutral percentages. Use the default Textblob analyzer and then compare it with the results of the NaiveBayesAnalyzer.
Delete the stop words from the reviews using the NLTK library stop-words lists.
Display a WordCloud of the top 20 words used in the reviews you cleaned.
Conclusion (in Markdown): include insights that you learned from this analysis.
Submit: a link to your GitHub repository containing your Notebook file.
