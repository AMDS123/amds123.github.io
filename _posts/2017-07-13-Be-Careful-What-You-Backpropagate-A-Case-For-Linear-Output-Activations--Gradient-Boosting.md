---
layout: post
title: "Be Careful What You Backpropagate: A Case For Linear Output Activations & Gradient Boosting"
date: 2017-07-13 16:19:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Semantic_Segmentation Classification
author: Anders Oland, Aayush Bansal, Roger B. Dannenberg, Bhiksha Raj
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we show that saturating output activation functions, such as the softmax, impede learning on a number of standard classification tasks. Moreover, we present results showing that the utility of softmax does not stem from the normalization, as some have speculated. In fact, the normalization makes things worse. Rather, the advantage is in the exponentiation of error gradients. This exponential gradient boosting is shown to speed up convergence and improve generalization. To this end, we demonstrate faster convergence and better performance on diverse classification tasks: image classification using CIFAR-10 and ImageNet, and semantic segmentation using PASCAL VOC 2012. In the latter case, using the state-of-the-art neural network architecture, the model converged 33% faster with our method (roughly two days of training less) than with the standard softmax activation, and with a slightly better performance to boot.

##### Abstract (translated by Google)
在这项工作中，我们表明，饱和输出激活函数，如softmax，阻碍了一些标准分类任务的学习。此外，我们目前的结果显示，softmax的效用并不像一些人所猜测的那样来自标准化。事实上，正常化使事情变得更糟。相反，其优点在于误差梯度的指数化。这种指数梯度提升被证明可以加速收敛并改善泛化。为此，我们展示了在不同的分类任务中更快的收敛性和更好的性能：使用CIFAR-10和ImageNet的图像分类以及使用PASCAL VOC 2012的语义分割。在后一种情况下，使用最先进的神经网络体系结构，与我们的方法（大约两天的训练少）相比，使用标准softmax激活，模型收敛速度提高了33％，并且启动性能略好。

##### URL
[https://arxiv.org/abs/1707.04199](https://arxiv.org/abs/1707.04199)

##### PDF
[https://arxiv.org/pdf/1707.04199](https://arxiv.org/pdf/1707.04199)

