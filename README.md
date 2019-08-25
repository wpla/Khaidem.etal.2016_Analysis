# Predicting the direction of stock market prices using random forests

Analysis of the results of the paper "Predicting the direction of stock market prices using random forest" (2016) by Khaidem et al. (https://arxiv.org/abs/1605.00003)

Their model is overfitted, since they are splitting the data randomly, using scikit-learns `train_test_split`. When the data is splitted, such that the first 80% are used for training, and the remaining 20% are used for testing, the results vanish. 

Reddit post: https://www.reddit.com/r/algotrading/comments/cv83yh/overfitting/
