# Cat vs Dog Image Classifier

This is a simple project where we train a model to look at a picture and determine if it's a **cat** or a **dog**

## Datasets and Tools

- **Dataset:** Cat and Dog images from https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset
- **Tools:** Python, TensorFlow, Keras, Jupyter Notebook

## Procedure

1. **Loaded the Images**
   Downloaded the dataset from kaggle, resized the imagages and relabeled them to '0' and '1's.

2. **Built a Model**
   Builed a CNN(Convolutional Neural Network) that observes different features of the animal
   to determine if it is a cat or a dog.

4. **Trained the Model**
   Fed the model with the downloaded dataset of images. Each iteration(**epoch**) increase accuracy.

5. **Tested the Model**
   Gave new data and the model predicted whether it was a cat or dog. This tested the accuracy of the model.
   

## Some diffiuclties faced
As CNN's require a lot of processing power, CPUs are generally not enough. It took a lot of time to run each epoch. Google colab 
and Kaggle were also slow due to slow internet. The model may hence have less accuracy sue to less training.

## Improvements
Can be made with more complex models like RESNet and MobileNet.
