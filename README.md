# About the problem 

The goal of this challenge is to identify the prevalent sentiment in brief passages of text,
and classify them along the Positive/Negative polarity axis.The task at hand is hence a classification task.

The text passages are lifted from posts on the popular social platform Twitter.
As such, they may contain idiosyncrasies like hashtags, mentions etc. It is up to you to decide how to handle them.

The data provided is as follows:

- **Train set**:

    a collection of textual passages in English; each passage  is associated with a label, 
    which can be, negative, neutral, or positive (coded as 0, 1, and 2, respectively).

    The train set is formatted as a .csv file

- **Test set**:

    a disjoint collection of textual passages in English, unlabeled.
    You will have to submit predictions against the passages in this test set to compete in the challenge.

    The test set is formatted as a .txt file in which each line contains a single passage.

# Evaluation

The metric chosen to evaluate how well you do in this challenge is the macro-averaged F-1 score 
over the set of predictions you provide for the test set. 
This metric is especially suited for evaluating multi-class classification tasks. 