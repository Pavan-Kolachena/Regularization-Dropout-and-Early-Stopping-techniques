# Regularization-Dropout-and-Early-Stopping-techniques
Details of Regularization , Early stopping and Dropout Techniques

The Major challenge of a Machine Learning or Deep Learning Model is Generalization
There are Two types of Error in ML or a DL Model

1. Train Error : The Error of the model on the train data
2. test Error : The error of the model on the test data

When the model performs well on both the types of data( training data and test data) then it is generalizeed model

When the model doesnt generalize well on the test data then it will lead to overfitting

Overfitting will happen when a model perform well on tarining data but doesnt work on test data,to over comr this we will follow below techniques

1. L1 regularization or Lasso Regularization: Here we will add the absolute values of the parameters(weights) to the loss function, here we will make sure that we will drive the weights to zero effectively performing feture selection, it is very fast
2. L2 Regularization or Ridge Regulariarion: Here we will add the squared values of the parameters(weights) to the loss function, here we will make sure that we will not drive the weights to zero , it is very slow
3. Elastic net REgularization : It is a combination of both L1 and L2 regularization, here we will get feature selection with unique solution
4. Droput : In dropout , during the tarining we will randomly select the neuron from hiden layers and deactivate them or sets their activation to zero before passing to the next layer, the fraction of neuron to be dropped is a hyper parameter known as dropput rate
5. Early stopping :stop training when difference between training and test eror starts increasing, this is based on educated guess
   
