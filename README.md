# SoccerBestBetPrediction
Soccer Best Bet Prediction Using Kaggle's Dataset

We use Kaggle's dataset which can be found in "https://www.kaggle.com/hugomathien/soccer".

To start we need to clean our dataset of inputs with missing values. We have all the information of betting companies so we apply
MeanSquaredError and LeastSquares to all the betting companies to see which one of them has the minimum. In order to do that we need to convert the returns, they gave for each different outcome into odds that they give that a certain outcome will come. After that, we are extracting the features of the dataset and split the data into train and test. Different models are being applied and finally, after doing 10-K fold-cross validation the model with the highest percentage is being chosen.

Updates i might consider doing:
Translate code comments to English.
