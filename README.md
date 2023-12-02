# Dog_breed_identification
### Using Tensorflow and Import image classification model from Tensorboard Hub
### This is kaggle competition problem

### Resources
Data and Problem statement - https://www.kaggle.com/competitions/dog-breed-identification
Tensorflow trained model - https://www.kaggle.com/models/google/mobilenet-v2/frameworks/tensorFlow2/variations/035-192-classification/versions/2?tfhub-redirect=true

#### Steps - 
1. Import the filename of labels of dog breed
2. Then import filename of photos of train dog identified as importing photo take time.
3. Made the new list which is appropiate to give to the model as boolean list
4. Test the model by inputing only 1000 image first to check if model is working properly
5. After done sample modelling, train the model using all images and labels to train
6. Before model train, it is required to convert the image into tensors with same dimension as tensorflow hub model
7. Trained the model, made prediction on given valid data
8. Now the last process which is to save the model like save.model
9. I have test this model on images I have download from Internet and it make prediction of 5 right out of 7.
