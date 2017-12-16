---
layout: post
title: "Deep Learning for Rapid Sparse MR Fingerprinting Reconstruction"
date: 2017-10-15 02:58:14
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning
author: Ouri Cohen, Bo Zhu, Matthew S. Rosen
mathjax: true
---

* content
{:toc}

##### Abstract
PURPOSE: Demonstrate a novel fast method for reconstruction of multi-dimensional MR Fingerprinting (MRF) data using Deep Learning methods. METHODS: A neural network (NN) is defined using the TensorFlow framework and trained on simulated MRF data computed using the Bloch equations. The accuracy of the NN reconstruction of noisy data is compared to conventional MRF template matching as a function of training data size, and quantified in a both simulated numerical brain phantom data and acquired data from the ISMRM/NIST phantom. The utility of the method is demonstrated in a healthy subject in vivo at 1.5 T. RESULTS: Network training required 10 minutes and once trained, data reconstruction required approximately 10 ms. Reconstruction of simulated brain data using the NN resulted in a root-mean-square error (RMSE) of 3.5 ms for T1 and 7.8 ms for T2. The RMSE for the NN trained on sparse dictionaries was approximately 6 fold lower for T1 and 2 fold lower for T2 than conventional MRF dot-product dictionary matching on the same dictionaries. Phantom measurements yielded good agreement (R2=0.99) between the T1 and T2 estimated by the NN and reference values from the ISMRM/NIST phantom. CONCLUSION: Reconstruction of MRF data with a NN is accurate, 300 fold faster and more robust to noise and undersampling than conventional MRF dictionary matching.

##### Abstract (translated by Google)
目的：利用深度学习方法展示一种用于重建多维MR指纹（MRF）数据的快速新方法。方法：使用TensorFlow框架定义神经网络（NN），并对使用Bloch方程计算的模拟MRF数据进行训练。噪声数据的NN重建的准确性与常规MRF模板匹配作为训练数据大小的函数进行比较，并且在模拟的数字脑模型数据和来自ISMRM / NIST模型的采集的数据中量化。结果：网络训练需要10分钟，一旦训练，数据重建需要大约10毫秒。使用NN重建模拟脑数据导致T1的均方根误差（RMSE）为3.5ms，T2的均方根误差为7.8ms。稀疏词典训练的神经网络的均方根误差在T1中低约6倍，在T2中低于传统的MRF点积词典在相同词典中的低2倍。由NN估计的T1和T2与来自ISMRM / NIST体模的参考值之间的体模测量产生良好的一致性（R2 = 0.99）。结论：用神经网络重建MRF数据是准确的，比传统的MRF字典匹配快300倍，对噪声和欠采样更加鲁棒。

##### URL
[https://arxiv.org/abs/1710.05267](https://arxiv.org/abs/1710.05267)

##### PDF
[https://arxiv.org/pdf/1710.05267](https://arxiv.org/pdf/1710.05267)

