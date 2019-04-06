# Fashion_mnist1

## Dataset for this repo can be download from kaggle 
https://www.kaggle.com/zalando-research/fashionmnist .
this dataset contains
60,000- training data and
10,000- testing data of 28 X 28 images of 10 different classes

## steps included
1) Preprocessing the data
2) choose appropriate hyperparameter (eg. learning rate, optimizer etc.)
3) Make convolutional neural network
4) compile the network and evaluate the model on test data

## Preprocessing the Data


 First split the  training dataset into two different dataset one for train the model and another one for validating the model.
 ![](https://user-images.githubusercontent.com/42611371/55674997-9ad04a00-58d9-11e9-9824-42853285a2c5.png)

Now don't forget to reshape the training ,testing and validating data to 4-dimensional because Keras.Conv2D() takes  4-D  images as its input and our dataset have 3-D images (height*width*channel )
 Note:---channel=3 in case of RGB images 

## CONVNet
I am using Keras with tensorflow as its backend. The code is easily understandable refer the code for this section.

Using my model i am able to get **92.09 %** of accuracy on test cases

![evaluatingg](https://user-images.githubusercontent.com/42611371/55675028-1e8a3680-58da-11e9-9365-f91a06133df1.png)


 
