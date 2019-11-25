# Assignment4
Recommendation System

This recommendation system has two implementation methods, one is content-based, the other is collaborative filtering

Content-based Recommendation：
The idea is to train a model to rate users and products based on their characteristics. Finally, all the commodities are sorted according to the scores, and the ones with higher scores are selected for return.
So the whole process is to refine the features according to the data, then train a model, and finally rank the scores.<br/>
refer to:<br/>
https://keras.io/getting-started/functional-api-guide/ (English)<br/>
https://blog.csdn.net/BF02jgtRS00XKtCx/article/details/85812754 (foreign language）<br/>
https://blog.csdn.net/jclian91/article/details/83024344 (foreign language）

collaborative filtering：<br/>
Direct use surprise, which itself is the recommendation system to do the library.<br/>
refer to: <br/>
http://surpriselib.com/ (English)<br/>
https://blog.csdn.net/mycafe_/article/details/79146764#12-音乐预测的例子 (foreign language) <br/>
