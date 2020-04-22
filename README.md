# MNIST
One of the most famous Kaggle competitions is Digit Recognizer, where you can learn the computer vision fundamentals using MNIST data. 

MNIST dataset is a set of 70,000 small images of digits handwritten by high school students and employees of the US Centus Bureau, each image being labeled by the digit it represents.

As this dataset is considered the 'hello world' of Machine Learning, anyone who learns ML tackles this dataset sooner or later, as myself.

This problem is a multiclass task, as we have to classify each image into ten possible classes.

I tried several different ML algorithms, with and without CV, to see how they perform with this dataset:
- Decission Tree Classifier
- Random Forest Classifier
- Liner SVC
- SVC
- XGBClassifier
- AdaBoostClassifier
- Extra Trees Classifier

Once I got the best ML models, and I saw the benefits of applying Cross Validation, I moved to Neural Networks, as they are so powerful in these images tasks.
Specifically, the notebook show the following approaches:
- a standar NN, with regularization techniques to avoid overfitting as Dropout layers or a custom schedule for the learning rate.
- hyperparameter tuning, using Random Search and hyperopt.
- a standard CNN
- a ResNet-34 CNN version

I ended taking the CNN model as the best solution, and I got a submitted score of 0.97 in the Kaggle competition, which can appear to be so great, but it is not as this dataset is considered 'entry-level', and then not very complex.