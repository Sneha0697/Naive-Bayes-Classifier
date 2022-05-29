# Naive-Bayes-Classifier

I am grateful to all of my teammates, who were a group of enthusiasts and a huge resource in building this model.

**Naïve Bayes**

***Advantages***

   The Naïve Bayes model performs better to other models, considering it only requires a
smaller training set to predict the test data. Prepping the data in Python was very helpful after
cleaning the data such as the missing values, headers for the explanatory variables and creating
dummies for the salary range which is our dependent variable. However, the Excel part was
still not easy because it took time to extract the data to different sheets in creating the bins,
categories per explanatory variable, pivot tables, trained model and confusion matrix based on
over 18 thousand cells.

***Limitations***

  The first limitation by the Naïve Bayes is that we assume that all the explanatory
variables are independent from each other, but in real life it is not like that. This classification
system suggests that the correlation between the explanatory variables is 0, which is not true.
For example, we see that there is a correlation between type of employment, higher age and
jobs compared to higher salary. But the Naïve Bayes does not take this into consideration.
The second limitation is when a categorical variable in the given test data includes a
variable that is not included in the training data set, the model will assign a probability of 0,
implying it will not generate a prediction. This is commonly referred to as Zero Frequency.

***Application in Business fields***

   When there is a text classification scenario, the data is large, and the training set is
small, Naive Bayes is commonly applied. For conditions like this, career websites like
LinkedIn, Glassdoor, Dice, and clothing/retail websites like Amazon, Calvin Klein, Shein, and
others can use them to generate accurate predictions on a variety of factors to improve their
business' performance.
