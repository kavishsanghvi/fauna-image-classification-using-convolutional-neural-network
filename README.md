# Fauna Image Classification using Convolutional Neural Network
Convolutional neural network for classification of animal images from Animal-10 dataset

## Aim
Aim of the project was to develop an animal image classifier in dense forest environments to achieve desired accuracy, and aid ecologists and researchers in neural network/Artificial Intelligence & zoological domains to further study and/or improve habitat, environmental and extinction patterns.

## Method
We present a methodology for the classification of fauna images, which will help ecologist and scientists to further study and/or improve habitat, environmental and extinction patterns. We have used Convolutional Neural Network with Leaky ReLU activation function and VGG16 architecture for our model. The initial step taken by the system aims at creation of features with VGG16 model. Application of Image Processing along with Loading, Testing, Training, and Validating the dataset before the training step helps to remove the noise, obstacles, distortion and dirt from the images. The next step uses Convolutional Neural Network along with Leaky ReLU to train the model to accurately and precisely classify animal classes. In order to avoid the problem of Dying ReLU, where some ReLU neurons essentially die for all inputs and remain inactive no matter what input is supplied, here no gradient flows and if large number of dead neurons are there in a neural network its performance is affected. To resolve this issue, we make use of what is called Leaky ReLU, where slope is changed left of x=0 and thus causing a leak and extending the range of ReLU. After training the model, we graph the model’s training and validation accuracy and loss to have insights about how well the model is trained. Lesser the loss, more is the accuracy. The next step is to generate classification matrix and confusion matrix to have exact details about how correctly the model is trained and classifying, as we cannot only rely on the accuracy. Lastly, we tested our model with sample data and found it to be accurately classified.

## Dataset
<a href="https://www.kaggle.com/alessiocorrado99/animals10">Animal-10 dataset</a>, which contains around 26179 hand-picked images of animals such as Butterfly, Cat, Chicken, Cow, Dog, Elephant, Horse, Sheep, Spyder, and Squirrel. Image count for each category varies from 2000 to 5000 images. Made available open-source through Kaggle.

## Video
URL: https://youtu.be/iGTybI_6zKU

## Contact
Read the complete article on <a href="https://medium.com/@kavishsanghvi/fauna-image-classification-using-convolutional-neural-network-30df9e25a010">Medium</a><br>
<a href="mailto:sanghvi_kavish@yahoo.in">Email</a> | <a href="https://www.linkedin.com/in/kavishsanghvi">LinkedIn</a> | <a href="https://kavishsanghvi.github.io">Website</a> | <a href="https://www.medium.com/@kavishsanghvi">Medium</a> | <a href="https://kavishsanghviblog.wordpress.com">Blog</a> | <a href="https://twitter.com/kavishsanghvi25">Twitter</a> | <a href="https://www.facebook.com/kavish.sanghvi.5">Facebook</a> | <a href="https://www.instagram.com/kavishsanghvi96">Instagram</a>
