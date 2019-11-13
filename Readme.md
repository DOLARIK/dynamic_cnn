# Dynamic Convolutional Neural Network

I have built a model in which we can make however deep a CNN we wish to with the freedom to have separate parameters for separate Layers. We can recreate any model (not including the use of residual Layers), like LeNet-5, VGG-16, VGG-19 just by tweaking some numbers in the model input. This saves a lot of time while undertaking newer projects using CNNs. It lets us focus on other things rather than putting in efforts recreating or modifying famous architectures. This also requires far less space until CNN architecture details have been specified, resulting in a dynamic usage of memory.

# Test

I have tested it for handwritten digit recognition -

Dataset: **MNIST Handwritten Digits (60k samples)** <br/>
Architecture: **LeNet-5** <br/>
Accuracy: **95.09%**

### Instructions:

Use MNIST_CNN.m to run and train the model for MNIST Dataset. (For detailed information checkout my other [repo][1]


## Results

![Results](https://github.com/DOLARIK/dynamic_cnn/blob/master/results/handwritten_dig_cnn_2.gif)


[1]: https://github.com/DOLARIK/Machine-Learning-Projects/tree/master/Handwritten%20Digit%20Classification%20(using%20CNN)/LeNet-5
