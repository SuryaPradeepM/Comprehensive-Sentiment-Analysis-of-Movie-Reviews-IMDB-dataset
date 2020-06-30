## Automated Sentiment Analysis of Movie Reviews using various approaches including sklearn models, keras models & transfer learning
The goal for this analysis is to predict if a review rates the movie positively or negatively. Inside this dataset, there are 25,000 labelled movies reviews for training, 50,000 unlabeled reviews for training, and 25,000 reviews for testing.
<a href="https://imgur.com/FfdEBRz"><img src="https://i.imgur.com/FfdEBRzm.png" title="source: imgur.com" align="right"></a>
- IMDB movie reviews dataset
- http://ai.stanford.edu/~amaas/data/sentiment
- https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
- Contains 25000 positive and 25000 negative reviews
- Contains at most reviews per movie
- At least 7 stars out of 10 &rarr; positive (label = 1)
- At most 4 stars out of 10 &rarr; negative (label = 0)


### <h3 align = "left">Notebooks</h3>
1. [Exploration and Preprocessing](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/Data_exploration_Preprocess.ipynb)
2. [Base Models (Logistic Regression, Multinomial NB)](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/Base_models_predictions.ipynb)
3. [Keras Models](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/Keras_Models_predictions.ipynb)
4. [PyTorch RNN Model](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/PyTorch_RNN_predictions.ipynb)
5. [BERT Fine Tuned Model](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/Bert_model_predictions.ipynb)


### <h3 align = "left">Dataset </h3>
* The data used for this problem can be found at: https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
* The [preprocessed data]() can be found at : https://drive.google.com/file/d/1-KrTwLg3b2NcHFafK_lrKeyTvUK3NhiL/view?usp=sharing


### <h3 align = "left">Accuracies Achieved: </h3>
* Logistic Regression | 90.79 %
* Support Vector Machine | 91.08 %
* Multinomial Naive Bayes | 91.32 %
* Simple Neural Net Keras | 92.83 %
* RNN LSTM PyTorch | 86.04 %
* BERT Fine Tuning | 91.68 %

### <h3 align = "left">WordClouds</h3>
#### Positive Reviews WordCloud
![Positive WordCLoud](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/images/Positive%20Reviews%20WordCloud.png)
#### Negative Reviews WordCloud
![Negative WordCLoud](https://github.com/SuryaPradeepM/Comprehensive-Sentiment-Analysis-of-Movie-Reviews-IMDB-dataset/blob/master/images/Negative%20Reviews%20WordCloud.png)

