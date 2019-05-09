# My Solution of Facial Emotion Recognization in Kaggle
This is my solution to [Facial Emotion Recognization in Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/).
The motivation of this task is to recognize humans' facial emotions in the natural environment, which is fun but a little difficult. The reason for this is the facial emotions on people's faces are always neutral, that is to say, it is difficult to distinguish if a person is happy or surprise, simultaneously. 
******
The data consists of 48x48 pixel grayscale images of faces. And there are more than 30000 samples. The task is to categorize each face into one out of seven categories, based on the emotion shown in the facial expression (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). 
******
This is the snapshot of the facial emotion dataset.
<br>
![image](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/face_picture.png)
******
**Note:** If you consult my source codes that you may want to incorporate into your algorithm or system, you should clearly cite references in your codes.
******

## Contents
* [weights.hdf5](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/weights.hdf5)
* [model.json](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/model.json)
******
This is the snapshot of my architecture of the deep conv network.
![image](https://github.com/zlpure/Facial-Expression-Recognition/blob/master/convnet.png)
******
If you look for the complete data and weights, you can go to [Baidu Cloud disk](http://pan.baidu.com/s/1o8FNtoQ), password: orzv. It includes raw tar.gz data, my neural network structure json file, weights zip file, and the data sets after compressing raw data into hdf5 format files.

## Dependencies
* Anaconda
* Python 2.7
* Numpy
* Keras

## Author
[@zlpure](github.com/zlpure)
