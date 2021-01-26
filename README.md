# ANN_from_scratch_classification

## Description
I tried to make ANN classification from scratch as a personal assignment from my Professor.
The purpose from our model is simple, it is to predict whether a series of integer is a aritmatic series, geometry series, or neither of them.
Our inputs consist of 6 entries of the series(in order manner). The dataset itself is randomized each run. The code to build the dataset is included.

The ANN architecture itself consist of 6 inputs node, 1 hidden layer with 10 nodes and output layer with 3 nodes.

For the activation;
- tanh      (hidden layer)
- softmax   (output layer)

Optimizer;
- Adam

I also provide python code for the same model but with Keras package, you can compare both model performance using same dataset from csv file, provided near the end.


### Dependencies
- Main
  - Numpy
  - Pandas
  - RobustScaler  (I will include formulas and reasoning)
  
- Optional
  - confusion_matrix , classification_report from sklearn.metrics (Not affecting the model, I used this only to take a quick look to my model performance)
  
 ### Possible Improvisasions
 - Better loss function
 - Visualization on accuracy and Loss for each epoch
 - Better explanation
 - Tidier code
 - Tidier model evaluation
 

#### Disclaimer
***I did'nt make this without looking at internet at all. You may notice some lines that same with a code from some websites, I make this repository in purpose to show how I put things together. Still use some packages that doesnt affect the model that much.***

***I will update this repository to make it better***
