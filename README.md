# Object-Detection-with-SSD

OpenCV is not the most powerful model. The model we are going to implement here 
is much more powerful because it is based on Deep Learning and Neural Networks that Computer Vision where the computer will have a brain. We want to implement some program that will the horses in a video where we have many horses running together. Here we are using SSD(Single Shot Multi box Detection) which gives the best results among other object detection models like CNN and openCV. The Description is as follow:

-After importing the libraries, we define a function that will do the detections. That   function will take as inputs, a frame, a ssd neural network, and a transformation to be applied on the images, and that will return the frame with the detector rectangle.

-We feed the neural network ssd with the image and we get the output after that,  we create the detections tensor contained in the output. 

-We create a tensor object of dimensions [width, height, width, height] that will contain many classes.

-Creating the SSD neural network and an object that is our neural network ssd.

-Creating the transformation, we create an object of the BaseTransform class, a class that will do the required transformations so that the image can be the input of the neural network and finally do some Object Detection on a video.
