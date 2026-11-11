# PolarNet

Opened 2016-04-20.

MatConvNet experiments on CIFAR-10. `cnn_cifar.m` trains LeNet, with a polar parameterization switched on by `usePolar` and `polarOpts`, and a Network-in-Network model. Training and initialization are `cnn_train.m`, `cnn_cifar_init.m`, and `cnn_cifar_init_nin.m`, with helpers in `Optimization/` and `simplenn/`.

## Papers

- Amir Emad Marvasti, Ehsan Emad Marvasti, Ulas Bagci, and Hassan Foroosh. [Maximum Probability Theorem: A Framework for Probabilistic Machine Learning](https://www.computer.org/csdl/journal/ai/2021/03/09446965/1ua0q5D18Yg). *IEEE Transactions on Artificial Intelligence*, 2021.
- Amir Emad Marvasti, Ehsan Emad Marvasti, G. Atia, Ulas Bagci, and Hassan Foroosh. [Rediscovering Deep Neural Networks Through Finite-State Distributions](https://arxiv.org/abs/1809.10073). *IEEE Access*.
- Amir Emad Marvasti, Ehsan Emad Marvasti, and Ulas Bagci. [Out of Distribution Detection, Generalization, and Robustness Triangle with Maximum Probability Theorem](https://arxiv.org/abs/2203.12145). *ICECCME*, 2022.
