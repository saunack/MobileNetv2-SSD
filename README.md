# MobileNetv2-SSD
An end-to-end implementation of the MobileNetv2+SSD architecture in Keras from scratch for learning purposes.

The dataset is handcrafted using MNIST images: MNIST images are embedded into a box and the model detects the numbers and the bounding box for the numbers. 

The code is commented for ease of understanding and also highlights some key points which need to be taken care of while creating the model.

Note: Hard negative mining has not been used due to the nature of the data used. 


References:

Mobilenetv2: https://arxiv.org/pdf/1801.04381.pdf

SSD: https://arxiv.org/pdf/1512.02325.pdf

Code:https://github.com/pierluigiferrari/ssd_keras and https://github.com/rs9899/mySSDimplementation/ 
