---
layout: post
title: "Flip-Rotate-Pooling Convolution and Split Dropout on Convolution Neural Networks for Image Classification"
date: 2015-07-31 05:02:56
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Fa Wu, Peijun Hu, Dexing Kong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new version of Dropout called Split Dropout (sDropout) and rotational convolution techniques to improve CNNs' performance on image classification. The widely used standard Dropout has advantage of preventing deep neural networks from overfitting by randomly dropping units during training. Our sDropout randomly splits the data into two subsets and keeps both rather than discards one subset. We also introduce two rotational convolution techniques, i.e. rotate-pooling convolution (RPC) and flip-rotate-pooling convolution (FRPC) to boost CNNs' performance on the robustness for rotation transformation. These two techniques encode rotation invariance into the network without adding extra parameters. Experimental evaluations on ImageNet2012 classification task demonstrate that sDropout not only enhances the performance but also converges faster. Additionally, RPC and FRPC make CNNs more robust for rotation transformations. Overall, FRPC together with sDropout bring $1.18\%$ (model of Zeiler and Fergus~\cite{zeiler2013visualizing}, 10-view, top-1) accuracy increase in ImageNet 2012 classification task compared to the original network.

##### Abstract (translated by Google)
本文提出了一个新版本的Dropout，称为Split Dropout（sDropout）和旋转卷积技术来改善CNN在图像分类上的表现。广泛使用的标准Dropout具有在训练期间通过随机丢弃单元来防止深度神经网络过度拟合的优点。我们的sDropout随机地将数据分成两个子集，并保留两个子集而不是丢弃一个子集。我们还引入了两个旋转卷积技术，即旋转池卷积（RPC）和翻转旋转池卷积（FRPC）以提高CNN的性能对旋转变换的鲁棒性。这两种技术将旋转不变性编码到网络中而不增加额外的参数。 ImageNet2012分类任务的实验评估表明，sDropout不仅可以提高性能，而且还可以更快收敛。另外，RPC和FRPC使得CNN在旋转转换方面更加强大。总的来说，与原始网络相比，FRPC与sDropout相比，ImageNet 2012分类任务的准确性提高了1.18％（Zeiler和Fergus的模型，10视图，前1）。

##### URL
[https://arxiv.org/abs/1507.08754](https://arxiv.org/abs/1507.08754)

##### PDF
[https://arxiv.org/pdf/1507.08754](https://arxiv.org/pdf/1507.08754)

