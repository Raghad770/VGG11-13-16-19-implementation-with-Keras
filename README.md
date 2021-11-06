# VGG11-13-16-19-implementation-with-Keras

VGG is a popular neural network architecture proposed by Karen Simonyan & Andrew Zisserman from the University of Oxford. It is also based on CNNs, and was applied to the ImageNet Challenge in 2014. The authors detail their work in their paper, Very Deep Convolutional Networks for large-scale Image Recognition [source](https://arxiv.org/pdf/1409.1556.pdf) 
**The input dimensions of the architecture are fixed to the image size, (244 × 244).
**a stack of convolutional layers with small receptive-field filters of size (3×3). In a few configurations the filter size is set to (1 × 1), which can be identified as a linear transformation of the input channels (followed by non-linearity).
**The stride for the convolution operation is fixed to 1.
**The max-pooling is performed over a (2 × 2) pixel window, with stride size set to 2.
**The configuration for fully-connected layers is always the same; the first two layers have 4096 channels each, the third performs 1000-way ILSVRC classification (and thus contains 1000 channels, one for each class), and the final layer is the softmax layer. All the hidden layers for the VGG network are followed by the ReLu activation function.

<center>
<img src="vgg all.png" align="center" width="800" height="600"/>
</center>

the VGG paper you can check it for more details *_* [source]()
