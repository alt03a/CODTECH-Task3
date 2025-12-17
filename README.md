# CODTECH-Task3

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SK ALTAB HOSSEN

*INTERN ID*:CT04DR1863

*DOMAIN*:MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*:NEELA SANTOSH

##Task 3: Image Classification Model
Project Description

Title: Image Classification on CIFAR-10 using Convolutional Neural Networks (CNN)**

Introduction Image classification is a core task in Computer Vision where the goal is to assign a label to an image from a predefined set of categories. Traditional neural networks (Dense layers) struggle with image data because they ignore the spatial structure of pixels and require a massive number of parameters. To address this, I implemented a Convolutional Neural Network (CNN), which is specifically architected to process grid-like data such as images.

Dataset I used the CIFAR-10 dataset, a standard benchmark in computer vision. It consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes include airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. The images were normalized by dividing pixel values by 255.0 to scale them into the 0-1 range, which helps the neural network converge faster during training.

Network Architecture The model was built using the TensorFlow/Keras Sequential API:

Convolutional Layers (Conv2D): These layers apply learnable filters (kernels) to the input image. As the filter slides over the image, it detects features like edges, corners, and textures. I used the ReLU (Rectified Linear Unit) activation function to introduce non-linearity.

Pooling Layers (MaxPooling2D): These layers reduce the spatial dimensions (width and height) of the feature maps. This reduces the computational load and helps the model recognize features even if they are slightly shifted or rotated (translation invariance).

Flatten Layer: After the convolutional base extracts features, the 2D arrays are flattened into a 1D vector to be fed into the dense layers.

Dense Layers: Fully connected layers that interpret the features extracted by the convolutions and perform the final classification into the 10 target classes.

Conclusion The model was trained over 10 epochs using the Adam optimizer and Sparse Categorical Crossentropy loss. The training process showed a steady increase in accuracy. This project demonstrates the power of CNNs in automatically learning hierarchical feature representations from raw pixel data, making them the standard for modern image recognition tasks.

##OUTPUT

![Image](https://github.com/user-attachments/assets/21f26fcc-df29-4c7d-b4be-6e1fe09aec1b)

![Image](https://github.com/user-attachments/assets/63efca04-8391-4795-8b67-30cdfac65d4b)

![Image](https://github.com/user-attachments/assets/c6b63913-a0af-4e9a-a685-04f53c0c1f11)
