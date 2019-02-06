# The algorithm in Layman term:

Fruit image recognition process in Machine Learning is so similar to how babies start recognizing the fruits. 

For example, parents try to make babies learn the colors. They show baby the color and tell the name of the color with it. And they just not do it once, they keep reminding baby and practice the color identification exercise everyday! Some chemical things happen in the brain and baby start learning the colors like red, yellow by seeing different colors so many times. Similar for the shapes, baby start recognizing the circle, rectangle, triangle, etc. 

Then parents keep reminding the baby that if it is red and round, it’s an “apple”. If its round and orange, it is an “orange” and so on. Maybe as human, baby will also recognize the fruit with smell and taste later.

So, same as parents, we fed various images are fed in machine learning model (you can consider that baby’s brain) with some maths equations (consider it as those chemical reactions in brain) which recognize the different features (the factors that baby will consider to recognize the fruit like color, size, shape, smell, taste). And with different combinations baby will finally classify the fruits.

So two tasks are taking place here to identify the fruits for image:
Feature extraction  Deciding the factors to be considered
Classification  See the combinations of the features and check with which fruit it is most similar.

Conventionally, only one algorithm called Convolutional Neural Network (CNN) is used for both the tasks as CNN. But what if I use the algorithms working individually best for each task! (one for Feature Extraction and one for Classification).  CNN does pretty good job in identifying the features. For classification, “Random Forest” algorithm is well-known. Hence, I have used Random forest+ CNN to identify the fruit rather than only CNN. 

This novel algorithm gave me 5 times more accuracy than the conventionally using only CNN.




# Image-Classification-with-CNN-RF

Our goal is to implement fruit recognition using Convolutional Neural Network(CNN) (keras and OpenCV) by training the Fruits 360 dataset available on kaggle. We aim to develop a feature extraction technique with convolutional neural networks. On extracted features (with CNN), random forest classifier is used to classify the images. By applying this model to images captured using front camera, fruits can be predicted. 

# Reference:
We are using kaggle dataset https://www.kaggle.com/moltean/fruits/data
