# Week 01


# Week 02

<img width="601" alt="image" src="https://github.com/user-attachments/assets/3734325f-cf70-4151-bb20-d481ec1adffa" />

## Normalization

In the example of image classification, the number are between 0 and 255. If you are training a neural network especially in image processing, for various reasons it will usually learn better if you <u> scale </u> all values to between 0 and 1. It's a process called normalization and fortunately in Python, it's easy to normalize an array without looping.


## Rules of thumb:
- The number of neurons in the last layer should match the number of classes you are classifying for. In this case it's the digits 0-9, so there are 10 of them, hence you should have 10 neurons in your final layer.
- There isn't a significant impact of adding another layers - because this is relatively simple data. For far more complex data (including color images to be classified as flowers that you'll see in the next lesson), extra layers are often necessary.

## Callbacks </u>

<img width="919" alt="image" src="https://github.com/user-attachments/assets/d5c0e363-ae77-4dd4-b62f-bb31cab10b07" />

<img width="919" alt="image" src="https://github.com/user-attachments/assets/f0d914a6-a35a-491f-8405-34c84c78f01e" />

# Week 03

Convolutional ANN

This filter emphazied vertical lines

<img width="919" alt="image" src="https://github.com/user-attachments/assets/64740a15-bcf3-43ad-bb32-3ab2e7ed1286" />

This filter emphazied horizontal lines

<img width="919" alt="image" src="https://github.com/user-attachments/assets/0f1f5099-d772-489d-812e-0cee3570b514" />



# Links

- Playground with neural networks
  - http://playground.tensorflow.org/
  - <img width="1439" alt="image" src="https://github.com/user-attachments/assets/c5612df3-95ff-4300-9a4e-5a167ab2498c" />

- Youtube TensorFlow
  - https://www.youtube.com/tensorflow


