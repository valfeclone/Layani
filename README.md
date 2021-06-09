# ML-Layani

Layani is an application that collects complaints by scraping social media, so it is visible and centralized for the civil servants to solve.

We created our own dataset by scraping tweets using Tweepy and Twitter API, We labeled our dataset manually with 2 labels, 0 for not complaint and 1 for complaint. We then preprocessed the dataset by cleaning unnecessary data(URLs, mentions, emojis), filtering stopwords, normalizing and stemming. We then use the FastText library by Gensim to vectorize the word for learning. We then train our model using Tensorflow keras layers CNN 1D and Bidirectional LSTM as its layers. We use Tensorflow keras binary cross entropy as loss function and Tensorflow keras adam as the optimizer. We then deploy the ML model using flask and nginx. As for the backend we deploy using app engine and to communicate with Android we use Rest API. To create the Android application, we use Kotlin as the programming language, we design our own UI for the application and implement it at android studio. We make the layout, activities, and fragments for our app and we connect it to the Rest API using retrofit.

Machine Learning Model: https://github.com/valfeclone/ML-Layani
Android: https://github.com/maheswarii/Layani 
Cloud Setup: https://github.com/farissatyaw/layani
