# ML Models – CNN
Machine Learning (ML) models are used all the time in our technology filled worlds and will only
continue to become more prevalent. Today we’ll cover the Convolution Neural Network (CNN) which is
a type of classification model almost exclusively used in image recognition.

## Supervised VS Unsupervised
In the world of ML, there are two main groups of models, those being **supervised** and
**unsupervised**. Supervised ML models make use of datasets in which the data has some form of
labeled and the user is required to essentially “teach” the model. They’re used in applications of
classification or regression (prediction). Unsupervised ML models on the other do not make use of
labeled data and the user isn’t required to teach the model. The model instead “learns” based on
patterns within the data. They’re used in applications of clustering or association.

## CNNs
CNNs are a type of supervised ML model which requires a labeled dataset. CNNs, however, function
based on principles of pattern recognition. As a result, some consider CNNs to be a hybrid of supervised
and unsupervised ML. CNNs require that all images in the dataset are normalized to set size typically
380x380. From there a frame is defined. A frame is like a window of specific size that then traverses the
image by a given stride. For example, we can have a frame of size 5x5, and a stride of 1. During ever
movement of the frame, a pattern is identified and formed from the training dataset. The model then
utilizes that pattern during testing and becomes the basis of the model.

## Example
Cover white blood cell project!