# image-classification-stanford_dog_dataset

i used a specific library called opendatasets. because, i was running my code in google collab. I was importing 
dataset from kaggle to collab. to import data from kaggle to collab, it will ask kaggle username and kaggle key. 
This process is explained in the following link https://www.geeksforgeeks.org/how-to-import-kaggle-datasets-directly-into-google-colab/

1. Dataset 
  Stanford dog dataset contains more than 20k images of 120 breeds of dogs. 
  
2. Method:
  * vanila CNN:
    The code includes implementation of vanila CNN. which has less accuracy about 12%, even after data augmentation techniques.
  * Transer learning:
    Inception V3 is used as a pretrained model to classify images. By this method i achived 77% accuracy.
