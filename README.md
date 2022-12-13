# Machine-Learning-Developer-Dicoding-Bootcamp-Tensorflow-Projects




## Rock, Paper, Scissors Hand Gestures Image Classification Project

This is one my first image classification project using the Tensorflow Keras library where the raw dataset contains over 2188 sample pictures 
of rock, paper and scissors hand gestures (of roughly equal amount for each) and the task was to build a simple image classifier using a Sequential model that can correctly
classify uploaded images of hand gesture as resembling either "rock", "paper" or "scissors" with an accuracy of over 95%. This projects demonstrates the use of:
- An ImageDataGenerator instance to create image augmentations 
- A sequential model implementing multiple 2D convolutional layers (which also consists of max pooling, dropout and dense layers) 
- A callback method (ReduceROnPlateau) to prevent stagnation in the learning stage

## Multiclass Text Classification on Dutch News Articles

An example of the implementation of Tensorflow Keras LSTM layers in a NLP text classification task. The purpose of this task was to build a sequential model that has a
LSTM layer to accurately classify text data with an overall accuracy of roughly 95%. This project demonstrates the use of:
- NLP preprocessing techniques for text data in Dutch (which includes number & punctuation removal, case folding, tokenization, lemmatization and stopword filtering) 
using a customized user-defined function 
- Word to vector tokenization, sequencing and padding 
- A sequential model implementing an Embedding layer and a Bidirectional LSTM layer (which also consists of dropout and dense layers) 

## The Application of Transfer Learning in Image Classification on the Flowers Dataset

This is a somewhat more complex version of the image classification project using the "Rock, Paper, Scissors" dataset as it compares using a standard CNN based 
sequential model consisting of four convolutional layers and multiple dense layers to another sequential model that implements transfer learning by means of a 
ResNet152v2 layer. The metrics using the standard CNN model was only able to produce an accuracy of around 55% but the model that used transfer learning resulted in 
better metrics including a training and validation accuracy above 80% just after 3 epochs

## NLP (Text Classification) using the BBC News Dataset

This is a similair project to the Dutch News Article Text Classification one, with the only fundamental difference being the test data used in this project is in English
(hence a different use of lemmatizer instance as well as the stopwords used for filtering) and a slightly deeper sequential model is used (consisting of a couple more dense
layers to optimally fit the BBC News Data in this particulat case). Two tokenizer instance are also used in this case (one for the text data and the other one to encode the
label into numeric form)




