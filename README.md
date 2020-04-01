# dogcatclassifier
This is a deep learning project where transfer learning is used to classify two different classes of animals : 1)dogs 2}cats.
The dataset is taken from kaggle dataset and the trainig is done on google colab using gpu which makes the training purpose faster.
The transfer learning is used using VGG16 algorithm for getting the better accuracy of the deep learning model. The layers are not trained and some layers are added to fine tune the model for object classification of two classes.Since VGG16 has been trained on Imagenet dataset classifying 1000 classes of objects so we have fine tuned our model for two classes using binary crossentropy loss function and Adam optimizer.The model gets an accuracy score of over 99% on the training dataset and 97% on test and validation dataset.
The notebook contains the working code of the project in which the dataset is downloaded from kaggle creating an API key to get access to the kaggle dataset.
For getting more accurate results we can ecperiment using image annotations techniques which is not demonstrated on my notebook.
After training the model the model weights are saved in .h5 format and the model architecture is saved on .json format which is also included in the repository.
