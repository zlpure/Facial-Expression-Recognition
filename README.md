## My Solution of Facial Emotion Recognization in Kaggle
This is my solution of [Facial Emotion Recognization in Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/).
The motivation of this task is to recognize humans' facial emotion in natual environment, which is fun but a little difficult. The reason for this is the facial emotions on people's face are always neutral, such as it is difficult to distingnish happy and surprise at the same time. 
******
The data consists of 48x48 pixel grayscale images of faces. And there are more than 30000 samples. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). 
******
This is the snapshot of the facial emotion dataset.
![image](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/face_picture.png)
******
**Note:** If you consult my code that you may want to incorporate into your strategy or algorithm, 
so long as you clearly cite your sources in your code and your writeup.
******

## Contents
* [weights.hdf5](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/weights.hdf5)
* [model.json](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/model.json)
******
This is the snapshot of my architecture of deep conv network.
＜/br＞
![image](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/convnet.png)
******
If you look for the complete data and weights, you can goto [Baidu Cloud disk](http://pan.baidu.com/s/1o8FNtoQ), password:orzv. It incldes raw tar.gz data, my neural network strcture json file, weights zip file, and the data and label after compressing raw data into hdf5 format files.

## Dependencies
* Anaconda
* Python 2.7
* Numpy
* Keras

## Author
[@zlpure](github.com/zlpure)
