## Classifying Images of Boats in the Cloud with AutoML Images

In our project, we have used Google Cloud AutoML Images to train a machine learning model to classify images of boats. AutoML Images is a service that allows users to easily train and deploy custom image recognition models using their own data.

To train the model, we provided AutoML Images with a dataset of images of boats, along with labels indicating the type of boat in each image. We have also specified certain parameters, such as the type of model to use and the amount of data to use for training.

Once the training process was complete, we tested the model's performance on a separate dataset to evaluate its accuracy. If the model performed well, you may have deployed it for use in a production environment.

Overall, the "Classify Images of Boats in the Google Cloud with AutoML Images" project demonstrated the power of AutoML Images for building custom image recognition models, and specifically for classifying images of boats.

In this project, we did the following:

* Uploaded a labeled "Boats" dataset to Cloud Storage and connected it to AutoML with a CSV label file.

* Trained a model with AutoML and evaluated its accuracy.

* Generated predictions on our trained model.

It took around 3 hours to train our model and get 87% accuracy.
