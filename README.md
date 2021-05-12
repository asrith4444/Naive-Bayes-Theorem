# Naive-Bayes-Theorem
Applying the Naive Bayes Theorem to find out the probable outcome for the given test data, in python is the goal of this program.

In this program I took a binary classifier dataset. This code will work for more than 2 classifiers too.

## To achieve the Naive Bayes Theorem using the Python:
In this program I'm followed the below formula:<br/><br/>
  P ( C | X ) = ( P ( X | C ) * P ( C ) ) / P ( X )<br/><br/>
But I am ignoring the denominator part and finding the Maximum of Numerator parts for each classifier which is also results in same conclusion.<br/>
So, reduced formula is :<br/><br/>
  P ( C | X ) = ( P ( X | C ) * P ( C ) )<br/><br/>
By finding the Max( P ( C | X ) ) results the probable outcome or target label for the given test data.

You can try this program with any kind of dataset, but header of the dataset is important for the program.
If there is no header for the given dataset then it raise an error.

**This program also biased to the class of the 1st row if and only if the given attributes are not present in the dataset.**<br/><br/>
Modules used in this program are Pandas and Counter.<br/>
Every line of the code is explained using the comments. So, go through the comments to understand the code.<br/>
If there is any problem with the program, kindly raise an issue.
