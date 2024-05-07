# Subscriber_Classification

After collecting the dataset from **<a href = 'https://archive.ics.uci.edu/dataset/222/bank+marketing' target = 'blank'>UCI Machine Learning Repository</a>**, I did some pre-processing of the dataset.

Then I did a exploratory data analysis on the dataset. However, the data was imbalanced. So, I applied ADASYN to balance the dataset. After that it was found that the varianc, skewness, kurtosis of the dataset was almost same.So, the distribution of the different factors didnot change much due to ADASYN.


Since, this is a banking campaign and the bank would like to predict all those who can say yes to their policy.So, the model must have very few 'False Negative'. So, the Recall Score is a good metric for this classification problem.
After this, I fitted a Decision Tree to classify the data. To improve the recall score, I did hyper parameter tuning. Finally the Random Forest Classifier was use dto classify the customers. The final model had a recall score of 0.95.
