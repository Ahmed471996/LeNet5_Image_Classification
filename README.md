# LeNet5_Image_Classification

## Introduction

we will be building one of the earliest Convolutional Neural Networks ever introduced, LeNet5 (paper). We are building this CNN from scratch in PyTorch, and will also see how it performs on a real-world dataset.

We will start by exploring the architecture of LeNet5. We will then load and analyze our dataset, MNIST, using the provided class from torchvision. Using PyTorch, we will build our LeNet5 from scratch and train it on our data. Finally, we will see how the model performs on the unseen test data.


## LeNet5
LeNet5 is one of the earliest Convolutional Neural Networks (CNNs). It was proposed by Yann LeCun and others in 1998. You can read the original paper here: Gradient-Based Learning Applied to Document Recognition. In the paper, the LeNet5 was used for the recognition of handwritten characters.

Let's now understand the architecture of LeNet5 as shown in the figure below:




![image](https://user-images.githubusercontent.com/101316217/210370106-013754d6-4bf5-4d45-aa91-642c686c2c8d.png)

## Dataset
We will be using the MNIST dataset. The MNIST dataset contains images of handwritten numerical digits. The images are greyscale, all with a size of 28x28, and is composed of 60,000 training images and 10,000 testing images.

You can see some of the samples of images below:

![image](https://user-images.githubusercontent.com/101316217/210398206-ff2d8d1d-a7f6-4a4c-a35d-47eb78366c6f.png)


## Future Work

You can try using different datasets but for this model you will need gray scale datasets. 
You can experiment with different hyperparameters and see the best combination of them for the model.
