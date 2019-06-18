# BCD-for-DNNs-PyTorch

Implementation of BCD for DNNs in *Global Convergence of Block Coordinate Descent in Deep Learning* [(Zeng et al., ICML 2019)](http://proceedings.mlr.press/v97/zeng19a.html) in PyTorch (See also [T. T.-K. Lau et al., ICLR 2018 Workshop](https://openreview.net/forum?id=HycIjFkPM)) with the MNIST dataset. 

```bcd_dnn_mlp_mnist.ipynb```: 3-layer MLP, MNIST, BCD (PyTorch)

```bcd_dnn_mlp_mnist_deep.ipynb```: 10-layer MLP, MNIST, BCD (PyTorch)

```sgd_dnn_mlp_mnist_deep_keras.ipynb```: 10-layer MLP, MNIST, SGD (TensorFlow and Keras; adapted from [this repo](https://github.com/timlautk/BCD-for-DNNs/tree/master/Keras))

```plot.ipynb```: Produces plots in the paper

J. Zeng*, T. T.-K. Lau*, S. Lin and Y. Yao (2019). Global Convergence of Block Coordinate Descent in Deep Learning. In *Proceedings of the 36th International Conference on Machine Learning (ICML)*. 
[URL](http://proceedings.mlr.press/v97/zeng19a.html) 

&ast;Equal contribution
