# Assigment-Session-4
EVA4-Sunday

1) How many Layers?
Ans) Considering an example of 64*64

64 * 64 -> 1(RF)
62 * 62 -> 3
60 * 60 -> 5
MaxPool -> 2RF
30 * 30 -> 10
28 * 28 -> 12
26 * 26 -> 14
MaxPool -> 2RF
13 * 13 -> 28
11 * 11 -> 30
9 * 9 -> 32
7 * 7 -> 34
5 * 5 -> 36

In the above example there are 11 Convolutional Layer

2) MaxPooling
Ans) 1) In the above example we have used 2 MaxPool layers.
2) we can need to reduce channel dimensions.
3) used far off from the final layer.
4) MaxPool will reduce the size by 2 so that parameters will also
reduced in the output. 
5) used when a block has finished its work (edges-gradients/textures-patterns/parts-of-objects/objects).

3) 1 * 1 convolution
Ans) Helps in reducing the parameters and dimension.

4) 3 * 3 convolution
Ans) It is faster in computation. It's widely used and most convenient. It has less number of parameters.

5) Receptive Field
Ans) The region in the input space that a particular CNN's feature is looking at. A receptive field 
of a feature can be described by its center location and its size

6) SoftMax
Ans) 1) The softmax function is often used in the final layer of a neural network.
2) The advantage of using the softmax at the output layer is that it improves the interpretability of the neural network.
3) By looking at the softmax output in terms of the network’s confidence, we can then reason about the behavior of our model.

8) Kernels and how do we decide the number of kernels?
Ans) Kernel is a feature extractor. It is better to use 3 * 3 Kernel.
Number of kernels depends on the number of channels in the output.

9) Batch Normalization
Ans) 1) Used after every layer
2) Never used before last layer
3) nn.BatchNorm2d()

14) Dropout
Ans) 1) Used after every layer
2) Used with small values (0.10,0.15,.20...)
3) It is a kind of reguralization
4)nn.Dropout2d()

 