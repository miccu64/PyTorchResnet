# PyTorchResnet

Aim of the project is to implement famous ResNet network in a customizable manner.

## Technologies

Python, PyTorch, Jupyter Notebook

## Network instantiate

User can specify network shape by using ResNetConvSizes class. Its parameters:
- resnet_layers: int - total number of layers, it must match the formula: block_size = 2 + (conv2+conv3+conv4+conv5) * block_size,
- block_size: int - size of all blocks of the network. Possible values: 2: basic block, 3: bottleneck block,
- conv2: int - number of blocks of convolution layer 2
- conv3: int - number of blocks of convolution layer 3
- conv4: int - number of blocks of convolution layer 4
- conv5: int - number of blocks of convolution layer 5 - this is the only layer which size can be equal to zero.
