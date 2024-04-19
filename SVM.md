## Support Vector Machine

SVM is a ***supervised machine learning algorithm*** used for both ***classification and regression*** tasks. However, it's best suited for classification.

- The main objective of SVM algorithm is to find the ***optimal hyperplane*** in a N-dimmensional space that can separate the data points in different classes in the feature space.
The dimension of the hyperplane depends upon the number of features

- The hyperplane tries to maximize the margin between the closest points of different classes. If the number of input features is two, then the hyperplane is just a line. 
if the number of input features is three, then the hyperplane depends upon the number of features.

- The SVM algorithm is very effective as it tries to find the maximum separating hyperplane between the different classes available in the target feature.
It can manage high-dimensional data and nonlinear relationships, making it adaptable and efficeint in a variety of applications.

- One of the key features of SVM is its robustness to outliers. It has the characteristic to ignore the outlier and finds the best hyperplane that maximizes the margin.

- In cases where the data is not linearly separable, SVM uses a method known as the ***kernel trick*** to transform
the input space into a higher dimmensional space where a hyperplane can be used to separate the data.

- SVMs are widely used in various fields, including patter recognition, image analysis, and natural language processing.

Return to [home page](README.md)
