# Machine Learning with Java - Part 5 (Naive Bayes)

In my previous article we have seen series of algorithms and this article describes about the Naive Bayes algorithm.The simplest solutions are the most powerful ones and Navie Bayes is the best example for the same.


# Naive Bayes

Naive Bayes is a family of probablistic algorithm that takes an advantage of probability theory and Bayes theory to predict the category of sample.

# Example 

To find whether an email is ham or spam, we have training samples listed below

now we will calculate which category the sentence "you won lottery" belongs to?
Naive Bayes is a probablistic classifier. To determine whether an email is ham or spam, we want to calculate the probability that the sentence "you won lottery" is ham and the probability that its spam. After the calculation we will take the largest one.

# How to calculate the probabilities?

The probabilities are calculated using the word frequencies.It is calculated using some basic properties of probabilities and the Bayes theorem.The conditional probabilities like the one discussed here will suits for the Bayes theorem.

\[ P(A | B) = \frac {P(B | A) \times P(A)} { P(B)} \


@[Naive Bayes Demo]({"stubs": ["src/main/java/com/gg/ml/NaiveBayesDemo.java"], "command": "com.gg.ml.NaiveBayesDemoTest#test"})


# Code Explanation

# Challenges with Nearest Neighbor model 
