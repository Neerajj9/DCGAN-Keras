# DCGAN-Keras
Deep Convolutional Generative Adverasrial Network in Keras (Tensorflow backend)

A DCGAN model to generate images from the MNIST handwritten digit dataset .

1 . Images are normalized to [-1,1]

2 . Activation function for the last layer - tanh 
    Activation function for other layers - LeakyReLU

3 . No Fully Connected Layers used in the model .                         

4 . Upsampling followed by Convolution layers are used to increase the resolution of the image .

5 . Optimizer : Adam

Result after 80 epochs :

![alt text](https://raw.githubusercontent.com/Neerajj9/DCGAN-Keras/Output/80.png)
