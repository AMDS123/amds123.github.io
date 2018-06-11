---
layout: post
title: "StrassenNets: Deep Learning with a Multiplication Budget"
date: 2018-06-08 10:59:23
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification RNN Classification Deep_Learning Language_Model
author: Michael Tschannen, Aran Khanna, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
A large fraction of the arithmetic operations required to evaluate deep neural networks (DNNs) consists of matrix multiplications, in both convolution and fully connected layers. We perform end-to-end learning of low-cost approximations of matrix multiplications in DNN layers by casting matrix multiplications as 2-layer sum-product networks (SPNs) (arithmetic circuits) and learning their (ternary) edge weights from data. The SPNs disentangle multiplication and addition operations and enable us to impose a budget on the number of multiplication operations. Combining our method with knowledge distillation and applying it to image classification DNNs (trained on ImageNet) and language modeling DNNs (using LSTMs), we obtain a first-of-a-kind reduction in number of multiplications (over 99.5%) while maintaining the predictive performance of the full-precision models. Finally, we demonstrate that the proposed framework is able to rediscover Strassen's matrix multiplication algorithm, learning to multiply $2 \times 2$ matrices using only 7 multiplications instead of 8.

##### Abstract (translated by Google)
评估深度神经网络（DNN）所需的大部分算术运算由卷积和完全连接层中的矩阵乘法组成。通过将矩阵乘法作为2层和积网络（SPN）（算术电路）并从数据中学习它们的（三元）边权重，我们在DNN层中执行矩阵乘法的低成本近似的端到端学习。 SPN解开了乘法和加法操作，并使我们能够对乘法操作的数量进行预算。将我们的方法与知识蒸馏相结合，并将其应用于图像分类DNN（在ImageNet上训练）和语言建模DNN（使用LSTM），我们获得了首次减少乘法次数（超过99.5％），同时保持了全精度模型的预测性能。最后，我们证明了所提出的框架能够重新发现Strassen的矩阵乘法算法，学习使用仅7次乘法而不是8乘以$ 2 \ times 2 $矩阵。

##### URL
[http://arxiv.org/abs/1712.03942](http://arxiv.org/abs/1712.03942)

##### PDF
[http://arxiv.org/pdf/1712.03942](http://arxiv.org/pdf/1712.03942)

