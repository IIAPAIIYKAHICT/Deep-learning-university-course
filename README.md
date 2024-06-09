# Deep-learning-university-course
## Lab 1
Just a bunch of different activation functions, their derivatives and loss function with their plots, the point of this lab was to take a closer look into different activations/losses behaviour
## Lab 2
In this lab we had a Parameter class code, which was inspired by Andrej Karpathy "micrograd" project, our task was to implement backward(using topological sort) and our activation functions from lab1, then we implemented the gradient descent algorithm and tested it by optimizing some linear function
## Lab 3
In this lab we had to create our own MLP class using torch library, we also needed to implement data loading, transforming and training loop
## Lab 4
We needed to add batchnorm and dropout parameter which is optional for each layer of the MLP from lab 3
## Lab 5
In this lab we needed to implement resnet architecture using Pytorch from scratch, we also needed to make 3 presets - resnet10, resnet18, resnet34 and then compare these models on the CIFAR10 dataset
## Lab 6
This is the final lab, here, we were given with the transformer architecture code and we needed to adjust it for computer vision(implement ViT). For this, We split the image into 16x16 patches, flatten them, project linearly and feed them to the transformer
