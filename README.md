# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Reddit Topic Predictions



### Problem Statement
Many times, advertisers want to target their marketing to customers that will purchase their product. That is why, if someone is selling a book, they would be interested in showing a book ad to someone who is already talking about books. The data science problem answered in this project is whether or not subreddit titles and self text are predictive of the subreddit "movies" and "books" topics. To approach this problem, I leveraged the Pushshift API and NLP to train binary classifiers.


### Executive Summary
Both the Logistic Regression and Multinomial Naive Bayes models provided good outputs. Though the model shows high variance, as can be seen from the higher train than test score, the model is able to predict whether a document is coming from a Movies subreddit or a Books subreddit with good accuracy. Limiting the number of features or adding regulation would reduce variance, but also decrease the accuracy of the model.


### Conclusion
The Logistic Regression model with 1000 max iterations, a C value of 10, ngram range of (1,2), and 'english' stop_words performed the best. Some errors came from phrases that had no clear division between movies and books, were in a different language, or did not even use the alphabet.


### Next Steps
As next steps, I would work on reducing the variance without reducing the score. In addition, I would try other models and compare the results. One step I want to do is tokenizing and lemmatizing on my own. Finally, I would try the same project on a different data set.

### Contents

- [Reddit Predictions PPT](./reddit_predictions.pdf)
- [Reddit Predictions Code](./reddit_predictions_code.ipynb)

The train data includes information from 2,051 sales which have 81 detailed features. The selling price time frame is from 2006 to 2010. The test data provides information for 878 houses for us to predict the selling price, but does not provide the selling price. Both the code and datasets folders have an archive folder of draft information.

### Additional

https://www.reddit.com/r/books/
https://www.reddit.com/r/movies/



