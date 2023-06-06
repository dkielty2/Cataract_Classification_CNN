This repository contains a dataset consisting of 612 images of human eyes with "normal" or "cataract" labels. The training and testing data sets were both of size 501 and 121, respectively, with 50/50 normal/cataract splits. The data set is open source and comes from the Kaggle page "Cataract dataset" [https://www.kaggle.com/datasets/nandanp6/cataract-image-dataset]. 

A cataract is a medical condition in which the lens of the eye becomes calcified and opaque. This gives the appearance of a white pupil that can be seen with the naked eye.

In cataract_CNN_clf.ipynb, we train a convolutional neural network (CNN) to classify an eye image as having a cataract or not having a cataract. The models were trained using 1:3 train/validation split. We used kerastuner.tuners.RandomSearch() to perform the training and hyperparameter tuning. 

The CNN model predicted with ~90% accuracy on the test set.

