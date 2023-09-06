# Recognition of Physical Exercises

Using Pose Estimation technique to recognize and classify the movements of athletes during training by using machine learning and deep learning techniques.

# Data Set
The dataset represents 10 different physical poses that can be used to distinguish 5 exercises. The exercises are Push-up, Pull-up, Sit-up, Jumping Jack and Squat. For every exercise, 2 different classes have been used to represent the terminal positions of that exercise (e.g., “up” and “down” positions for push-ups).

The data is available on Kaggle: https://www.kaggle.com/datasets/muhannadtuameh/exercise-recognition

# Methodology

<img width="400" alt="image" src="https://github.com/muhannad125/recognition-of-physical-exercises/assets/61150919/4fbd8761-5538-428d-a45c-e9b3479125e4">

The input of the model is a video of a human doing the exercise, and the output is the name of the exercise and a number of how many times the exercise have been done. The repetition counter should update the number of the repetition based on the change of the pose during the video.

In order to create the described model, different machine learning and deep learning techniques has been used and compared to each other, so we can select the best performing method in our model. To be able to train the AI model, a dataset of 1370 images of 5 fitness exercises are collected in the first step of the project. The plan is to train the model to recognize the terminal positions of every exercise, so it will be able to count the repetitions based on them e.g. if the exercise performer changed his/her position in a particular sequence (i.e. up, down, up or down, up, down) the model will consider it as a repetition of the exercise. Also, if the model learned the terminal positions of every exercise, it would also be able to recognize the exercise.

# Contributors

Muhannad Tuameh - muhannadtumah@gmail.com

Muhammed Nasir Sabir - muhammednsrsbr@gmail.com
