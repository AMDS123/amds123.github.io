---
layout: post
title: "Distantly Supervised Road Segmentation"
date: 2017-08-21 08:34:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Satoshi Tsutsui, Tommi Kerola, Shunta Saito
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach for road segmentation that only requires image-level annotations at training time. We leverage distant supervision, which allows us to train our model using images that are different from the target domain. Using large publicly available image databases as distant supervisors, we develop a simple method to automatically generate weak pixel-wise road masks. These are used to iteratively train a fully convolutional neural network, which produces our final segmentation model. We evaluate our method on the Cityscapes dataset, where we compare it with a fully supervised approach. Further, we discuss the trade-off between annotation cost and performance. Overall, our distantly supervised approach achieves 93.8% of the performance of the fully supervised approach, while using orders of magnitude less annotation work.

##### Abstract (translated by Google)
我们提出了一种道路分割的方法，在训练时只需要图像级别的注释。我们利用遥远的监督，这使我们能够使用与目标领域不同的图像来训练我们的模型。使用大型公开可用的图像数据库作为遥远的监督者，我们开发了一种简单的方法来自动生成弱像素路面罩。这些被用来迭代训练一个完全卷积的神经网络，它产生了我们最终的分割模型。我们在Cityscapes数据集上评估我们的方法，并将其与完全监督的方法进行比较。此外，我们讨论了注释成本和性能之间的折衷。总体而言，我们的远程监督方法达到了完全监督方法的93.8％的性能，而使用少量的注释工作。

##### URL
[https://arxiv.org/abs/1708.06118](https://arxiv.org/abs/1708.06118)

##### PDF
[https://arxiv.org/pdf/1708.06118](https://arxiv.org/pdf/1708.06118)

