# Canary
<!-- > All the practice of Canary is for project Griffin, and I hope it is the last sacrificed bird. -->

A Decentralized Distributed DL Architecture in Multi-interface Network.


# Prerequisite
* [PyTorch](https://pytorch.org/)
* [Open MPI](https://www.open-mpi.org/)

# Overview
There are three main folders:

* `model`: the models used in DL training, incluing common CNN. AlexNet, VGG19.
* `8bit_quantization`: building gradient sketch by transferring float32 into 8bit quantization.
* `topology`: PS on FatTree and AllReduce on BCube.

# Dataset
Three classical datasets are supported: MNIST, Fashion MNIT, and CIFAR-10.

* MNIST: The demos have already contained MNIST in the directory `data`, you can also download it from [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/)
* Fashion MNIST: you can download it from [https://github.com/zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist).
* CIFAR-10: You can download it from [https://www.cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html).