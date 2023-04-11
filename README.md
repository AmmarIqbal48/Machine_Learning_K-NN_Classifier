# Machine_Learning_K-NN_Classifier

k-Nearest neighbours classifier is a non-parametric classification method which inputs are the k closest training
examples of a data set, while the output is a class membership. The goal of this laboratory is to implement this
classifier in MATLAB on the specified data sets.


## K-Nearest neighbour classifier
The KNN algorithm is a simple and easy to implement supervised machine learning algorithm. It’s non parametric so it makes no assumption about the probability distribution building a discrimination rule directly from the
data.
To implement this algorithm is needed a:
- Training set X=x1, . . . , xl, . . . , xn and a query point
- A value k
Then given the set for training with n examples, it firstly identifies the k-nn training example of the new instance
and then assigns the class label with the highest number of neighbours of the new instance.
