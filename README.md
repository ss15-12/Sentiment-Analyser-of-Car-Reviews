# Sentiment-Analyser-of-Car-Reviews
A sentiment analysis model for analysing car reviews , providing a competitive analysis between different cars using various methods.

## The basic structure of the working model is as follows:

->*Choose one of the best car review websites or car selling websites.*

->*Scrape essential information such as ratings, main reviews, and overview.*

->*Use opinion lexicons to estimate the positivity/negativity of the reviews.*

->*Store all reviews in a dataframe for using it  in sentiment analysis.*

->*The information can be used as a training dataset for the neural network that predicts the positive and negative sentiments of the reviews.*

->*The overall sentiment expressed in the statement reflects the true meaning of the review.*

->*This can help the company make informed decisions to improve their quality and standards based on customer feedback.*

## Sentiment Analysis Model:

->*The implementation begins by taking the car reviews dataset.*

->*The program preprocesses the text data by cleaning it up, leaving only non-stop words composed of A-Z and a-z only in lowercase. It also removes HTML tags, punctuations, numbers, and single characters, and removes stopwords.*

->*The program then splits the data into training and testing sets and tokenizes the words using a tokenizer. The tokenizer converts text to sequences of integers.*

->*The program then prepares the embedding matrix using GloVae, a pre-trained word embedding technique.*

->*The model is then built using Long short-term memory networks (LSTM), a type of recurrent neural network, and trained using the training set.*

->*The LSTM model is used for predicting the sentiment of the reviews using the processed text data. The model is trained using training data and validated using testing data.*

->*The model is saved in a file and can be used for predicting.*

->*Finally, the model is used to predict the sentiment of unseen reviews and the predicted sentiment is written to a CSV file.*

## The User Interface:

The user interface was built by a python library known as gradio. We have made basic divisions in the interface performing various actions. We have a module printing the average sentiment .Another one printing the Polarity score. One analysing the sentence and how positive it is.

![image](https://github.com/ss15-12/Sentiment-Analyser-of-Car-Reviews/assets/83355479/2beff632-ab49-45b9-8841-7f8f9e9e76d9)

![image](https://github.com/ss15-12/Sentiment-Analyser-of-Car-Reviews/assets/83355479/cdd48009-dcc5-4eea-933b-dda790b56e31)

![image](https://github.com/ss15-12/Sentiment-Analyser-of-Car-Reviews/assets/83355479/d79ee472-42ed-44ee-a5c1-795c05ea7135)

![image](https://github.com/ss15-12/Sentiment-Analyser-of-Car-Reviews/assets/83355479/dac5453a-41d1-4620-b441-1388f4fa7df1)




