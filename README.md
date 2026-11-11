# PolarNet

Opened 2016-04-20.

MatConvNet experiments on CIFAR-10. `cnn_cifar.m` trains LeNet, with a polar parameterization switched on by `usePolar` and `polarOpts`, and a Network-in-Network model. Training and initialization are `cnn_train.m`, `cnn_cifar_init.m`, and `cnn_cifar_init_nin.m`, with helpers in `Optimization/` and `simplenn/`.
