# MobileNetv2-SSD
An end-to-end implementation of the MobileNetv2+SSD architecture in Keras from scratch for learning purposes.

## Getting started
The python notebook lists all the code required for running the model. The code is commented for ease of understanding and also highlights some key points which need to be taken care of while creating the model.<br>
The model is supposed to predict the bounding boxes for a digit embedded in the image as well as a confidence score for the digit inside the bounding box.

## Dataset
The dataset is handcrafted using MNIST images: MNIST images are embedded into a box and the model detects the numbers and the bounding box for the numbers. For now, each image consists of only one embedded number. Multiple embeddings are also possible. The input and output datasets need to be changed correspondingly.

## Implementation details
The models have been created from scratch using the original papers as references. All deviations from the original models in the papers are marked inside the code. One important thing to note is that hard negative mining has not been used. 


## References
* Mobilenetv2: https://arxiv.org/pdf/1801.04381.pdf
* SSD: https://arxiv.org/pdf/1512.02325.pdf
* Code:https://github.com/pierluigiferrari/ssd_keras and https://github.com/rs9899/mySSDimplementation/ 
* Blogs: https://machinethink.net/blog/object-detection/ and https://lambdalabs.com/blog/how-to-implement-ssd-object-detection-in-tensorflow/ 
