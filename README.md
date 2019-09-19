# obstacle-avoidance-mobile_bot
In this work, a non-linear model is prepared for a mobile robot for detecting an obstacle and avoiding it using Artificial Neural Network with an accuracy of 98.2%. Here Robot uses Raspberry Pi Zero W and Node MCU as microcontroller and employs one ultrasonic distance sensor and two Infrared sensors.

This work contributes a powerful and a well-trained model that can be used for an autonomous robot for real-time navigation in a complex environment. This model is prepared through neural networks using Backpropagation algorithm with great accuracy.

ROBOT:

![photo](https://user-images.githubusercontent.com/45910597/65208799-c162f580-dab3-11e9-89c7-d7227ca929f9.jpeg)


Our preparation of the model is divided into three parts:

Firstly we collect our training data by randomly navigating our robot in an environment containing obstacles and navigation is done through software connected to Node MCU controlling its motor driver. Data is in the format of a distance of the obstacle from the ultrasonic sensor, the velocity of the right wheel and velocity of the left wheel, velocity is measured using infrared sensors.

Secondly, data is cleaned, all the ambiguous values are deleted and clean data is obtained for training a model.

Lastly, a model is trained using Artificial Neural Network and fitted in the robot to avoid obstacles in real-time and reach the desired location.It can be achieved through Neural Network using Backpropagation algorithm to recognize obstacles in the environment and control its speed.

DESIGN:

STRUCTURE
