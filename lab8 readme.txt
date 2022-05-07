Class: EE 104
Xinyuan Zhou
About this code:
All the code used is credit to Professor Pham.

This lab is consist of three modeules:
1. CNN improvement
2. CNN Challenge test
3. Game Development – Balloon Flight

Module 1:
In this module, we are trying to improve the accuracy when CNN recognize color image.
To run the code on Google Colab, you need to install extra packages using the commands:

!pip install tensorflow
!pip install keras
!pip install h5py
!pip install Matplotlib
!pip install numpy

The graphic files used are from: https://www.cs.toronto.edu/~kriz/cifar.html
The basic code is from: https://colab.research.google.com/
github/tensorflow/docs/blob/master/site/en/tutorials/images/
cnn.ipynb#scrollTo=WRzW5xSDDbNF

To improve the accuracy, baseline, increase dropout, data augmentation, batch normalization could
be used in this lab, the result is shown in the video.

Module 2:
In this module, we are going to test 5 unrecognizable images from the test images.
After running the program, we can see the result.

Module 3:
For this balloon flight, we are going to add four more features based on the coding structure,
what I did are: more high scores, speed it up, add multiple obstacles, and level up.


Instruction:

For the first module, you only need to install every packages needed first, then you can go through
google colab to get faster running speed using GPU, by running each code line, you finally get
the accuracy required.

For the second module, you need to put different unrecognizable figures into this program,
the program is going to define it for you.

For the third part, the game is that you need to use your mouse to control the balloon,
each time you click the left button, the balloon goes up. You need to avoid the collision with 
the obstacles to get high scores.

