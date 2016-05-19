---
layout: post
title: Will it go viral?
---

Is a post about an "Awkward half-cat loafing on the Stairs" or one about Tylor Swift's new Apple ad more likely to go viral? 

If you have spent any time on the internet the answer might be obvious* - but I decided to train and test some classification models on an "Online News Popularity" dataset hosted by UCI's Machine Learning Repository to see if I could predict whether an article could "do better than most" (meaning be shared more than the median share of 1400). 

I have worked in the Marketing and SEO idustry - so I have read countless articles (let's be honest, they're all listicles) about how you can optimize content to encourage people to share it. I was expecting number of videos, pictures, and links to be have the strongest impact on number of shares. My data set also included information about keywords, publishing (meaning what section of the website and what day of the week the article was published on), length and uniqueness of title and content, and some feautres related to Natural Language Processing (I'll save talking about that for my next blog post).

I trained several of the classfication algorithms we talked about at Metis - K-Nearest Neighbors,Logistic Regression, Gaussian Naive Bayes, Support Vector Machine, Decision Trees and Random Forest - on my training set an then tested them. Random Forest had more predicive power than all the others at 61% accuracy on the test set.  Random Forest has a lot of parameters that you can use to tune the model, so I ran some tests myself and finally implemented a cross validated grid search to find the ideal parameters for my model. This boosted my accuracy to 66.5% - not as strong as I would like, but still useful as guide.

Once I had run my optimized random forest I took a look at the importance of all my features. I was surprised to see that the predictive power was pretty evenely spread across all of my features. The top two features my importance were the average shares for the Average Keyword and Best Keyword. This was the average amount of shares received for all articles in the set containing the given keyword (in this case the average ranking keyword and the best ranking keyword). Unfortunately, this dataset did not contain the actual keywords used (was it cats? or Taylor Swift?) So to further my analysis I will need to collect more data of my own.



You can view my complete presentation deck [here.](https://docs.google.com/presentation/d/1xNXnNK7mHxsax5sWpE0dV7TAd1yIq1EjXEKW8gCY4Kk/edit?usp=sharing)
For access to the dataset I used please visit the [UCI Machine Learning Repository.](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity)
If you are dying to read the articles about [the awkward half cat](http://mashable.com/2016/05/12/awkward-half-cat-photoshop-battle/) or [Taylor Swift](http://mashable.com/2016/05/12/taylor-swift-ad-lip-sync/#Y3mtP_O_B5qq) they can both be found at [Mashable.](http://mashable.com/)

Data Citation: K. Fernandes, P. Vinagre and P. Cortez. A Proactive Intelligent Decision Support System for Predicting the Popularity of Online News. Proceedings of the 17th EPIA 2015 - Portuguese Conference on Artificial Intelligence, September, Coimbra, Portugal.  

