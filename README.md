# Plant-Diseases-Prediction

Plant diseases prediction is prediction in which we can predict the disease of leaves from their image. 

In this project we will create a Convolutional Neural Network which will be able to predict whether a plant is suffering from a disease. We will use different layers and other hyperparameters for building, training and testing this classifictaion model.We will be using tensorflow and keras for this project.

  We have three diseases one Corn common rust, second one is Potato Early blight and another one is Tomato Bacterial spot.

  With the help of cv2 we will convert images to array.

  After that we split the data into two models train and test.
  
  Now we will use the sequential model in that 1st layer we will use conv2D then we will use MaxPooling2D, 3rd is Flatten layer, last layer is Dense model.
  
  We will train the model into number of epochs, the more number of epochs you give the more model accuracy you will get as output.
  
  Now we will plot the Model Accuracy with the help of matplotolib.
  
  Lastly we will print the Original and Predicted diseases. When you will get the same disease then the is very accurate.
  
  
Conclusion:

We started with loading the dataset into google colab using google drive and visualizing the images. Normalizing is an important step when working with any type of dataset. After that we created a CNN Model which is further used for predicting the plant diseases using the image supplied to model. This model is highly beneficial as it can be used by different agricultural firms and farmers to increase their yield and stop wastage of crops due to disease.
