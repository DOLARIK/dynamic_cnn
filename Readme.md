# Dynamic Convolutional Neural Network

I have built a model in which we can make however deep a CNN we wish to with the freedom to have separate parameters for separate Layers. We can recreate any model (not including the use of residual Layers), like LeNet-5, VGG-16, VGG-19 just by tweaking some numbers in the model input. This saves a lot of time while undertaking newer projects using CNNs. It lets us focus on other things rather than putting in efforts recreating or modifying famous architectures. This also requires far less space until CNN architecture details have been specified, resulting in a dynamic usage of memory.

# Test

I have tested it for handwritten digit recognition with LeNet-5 architecture. The model was able to achieve an accuracy of **95.4%**.

## Results

![Results](https://github.com/DOLARIK/dynamic_cnn/blob/master/results/handwritten_dig_cnn_2.gif)
