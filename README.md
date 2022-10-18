# P-SLab1

Our team during a couple of days worked on the application of Naive Bayes classifier, which is a probabilistic classifier. It determines which class some observation probably(!) belongs to using Bayes formula.
The pros are that naive Bayes classifier is easy to understand and implement, but there some cons: it’s hard to get a high level of accuracy, especially in our case, when the dataset had to be divided into three groups. 
For such case, we should use a more complex and accurate probability classifier, like multinomial Bayes classifier. The train data is rather imbalanced (with low correlation between different groups of sentiments), accuracy level = 35,9% simply because of such difference. 
To analyze the gotten results, we used a simple way of calculating level of predicting correctly, and F1 score metrics, which is a better metrics to use having the imbalanced data (62,4%).
