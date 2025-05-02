Taught by:
Laurence Moroney, Instructor

# Week 01 - A New Programming Paradigm

<img width="1187" alt="image" src="https://github.com/user-attachments/assets/b08c4f5a-0564-470a-b05a-3bc3378b78ba" />

<img width="1302" alt="image" src="https://github.com/user-attachments/assets/c4c8d377-abf2-463b-ac5c-378bb929cd25" />

- Dense defines the number of layers
- sgd: stochastic gradient descent
- epochs: the fit algorithm will go through training loop 500 times

# Week 02 - Introduction to Computer Vision

<img width="601" alt="image" src="https://github.com/user-attachments/assets/3734325f-cf70-4151-bb20-d481ec1adffa" />

## Normalization

In the example of image classification, the number are between 0 and 255. If you are training a neural network especially in image processing, for various reasons it will usually learn better if you <u> scale </u> all values to between 0 and 1. It's a process called normalization and fortunately in Python, it's easy to normalize an array without looping.


## Rules of thumb:
- The number of neurons in the last layer should match the number of classes you are classifying for. In this case it's the digits 0-9, so there are 10 of them, hence you should have 10 neurons in your final layer.
- There isn't a significant impact of adding another layers - because this is relatively simple data. For far more complex data (including color images to be classified as flowers that you'll see in the next lesson), extra layers are often necessary.

## Callbacks </u>

<img width="919" alt="image" src="https://github.com/user-attachments/assets/d5c0e363-ae77-4dd4-b62f-bb31cab10b07" />

<img width="919" alt="image" src="https://github.com/user-attachments/assets/f0d914a6-a35a-491f-8405-34c84c78f01e" />


## Functions

- ReLU

- Softmax

# Week 03 - Enhancing Vision with Convolutional Neural Networks

## Convolutional Neural Networks

Instead of treating all input features equally (like traditional neural networks), CNNs use filters (also called kernels) that scan across the image, picking up important patterns like edges, textures, and shapes. This scanning process is called a convolution, hence the name.

### 🧠 Basic CNN Structure

1.	Input Layer

Receives the raw image data (e.g., 28x28 grayscale image).

2.	Convolutional Layers

Applies filters that detect patterns (e.g., vertical lines, corners). These filters are learned during training.

3.	Activation Function (ReLU)

Introduces non-linearity, helping the network learn complex patterns.

4.	Pooling Layers (e.g., MaxPooling)

Reduces the spatial size of the data, making the model faster and less likely to overfit.

5.	Fully Connected Layers

After pattern extraction, these layers make the final decision (like classifying an image as a cat or dog).

6.	Output Layer

Gives the final result (e.g., probabilities of classes).

### Filter Examples:

This filter emphazied vertical lines

<img width="919" alt="image" src="https://github.com/user-attachments/assets/64740a15-bcf3-43ad-bb32-3ab2e7ed1286" />

This filter emphazied horizontal lines

<img width="919" alt="image" src="https://github.com/user-attachments/assets/0f1f5099-d772-489d-812e-0cee3570b514" />

### Example Use Cases

- Image classification (e.g., dog vs. cat)
- Object detection (e.g., where’s the face in the photo?)
- Medical image analysis (e.g., detecting tumors)
- Facial recognition
- Self-driving cars (e.g., reading road signs)

### Pooling Layer

A Pooling Layer is a downsampling operation — it shrinks the size of the feature maps that come from the convolutional layers, while keeping the important information.

Think of it as a way to:
- Make the model faster
- Reduce memory usage
- Make the network more robust to small shifts and distortions in the input (e.g. if an object moves slightly in an image)


# Week 04 - Using Real-world Images


# Links

- Playground with neural networks
  - http://playground.tensorflow.org/
  - <img width="1439" alt="image" src="https://github.com/user-attachments/assets/c5612df3-95ff-4300-9a4e-5a167ab2498c" />

- Youtube TensorFlow
  - https://www.youtube.com/tensorflow


