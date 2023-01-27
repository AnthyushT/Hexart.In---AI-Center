This project is based on Natural Language Processing in which sentiment prediction and analysis on real-time scraped flipkart reviews(without labels).

I had uploaded two files here the file named SentimentGithub.ipynb is what makes you clear understanding and differentiate of how textblob is useful for labelling the data and how badly the random placement of labels.
Generally we do sentiment analysis on labelled data.Here we dont have labelled data(realtime scraped data) so How I transform the unlabelled to label data without going into deeper like using clustering algorithms.
I used sklearn's tfidf vectorizerfor vectorizing the data and build classification model using logistic regression on how likely the predicted labels are correct.

We generally notice comments and ratings of the product in ecommerce sites.If we look closer we will notice bad rating even for positive comment. So, I realized the sentiment analysis should be done based on comment rather than rating!Ofcourse ratings will be useful for company to showcase the product but deeper its a trap.

in sentimental analysis
The mood of the ipynb file is predicted both in the comments and in the review section. Only minimal changes to the code (replacing reviews with comments) may be suitable for sentiment analysis using the reviews section

. Classes were sometimes changed as Flipkart recognized bots according to an automated process. If you find a bug please change the class **

** Contribute to the code just by dragging a request. If accepted, we can merge the PR**.

You may notice that the above folder contains some of the records created by the flipkarreviews.py file code.

This is beneficial for any business as the rating system is calculated based on user ratings. I think product reviews can only be expressed in comments/review_description. So this project calculates the product rating based on user ratings.
