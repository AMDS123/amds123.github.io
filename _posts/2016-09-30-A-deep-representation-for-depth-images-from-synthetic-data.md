---
layout: post
title: "A deep representation for depth images from synthetic data"
date: 2016-09-30 13:10:20
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Fabio Maria Carlucci, Paolo Russo, Barbara Caputo
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) trained on large scale RGB databases have become the secret sauce in the majority of recent approaches for object categorization from RGB-D data. Thanks to colorization techniques, these methods exploit the filters learned from 2D images to extract meaningful representations in 2.5D. Still, the perceptual signature of these two kind of images is very different, with the first usually strongly characterized by textures, and the second mostly by silhouettes of objects. Ideally, one would like to have two CNNs, one for RGB and one for depth, each trained on a suitable data collection, able to capture the perceptual properties of each channel for the task at hand. This has not been possible so far, due to the lack of a suitable depth database. This paper addresses this issue, proposing to opt for synthetically generated images rather than collecting by hand a 2.5D large scale database. While being clearly a proxy for real data, synthetic images allow to trade quality for quantity, making it possible to generate a virtually infinite amount of data. We show that the filters learned from such data collection, using the very same architecture typically used on visual data, learns very different filters, resulting in depth features (a) able to better characterize the different facets of depth images, and (b) complementary with respect to those derived from CNNs pre-trained on 2D datasets. Experiments on two publicly available databases show the power of our approach.

##### Abstract (translated by Google)
在大规模RGB数据库上训练的卷积神经网络（CNN）已经成为近期大多数RGB-D数据对象分类方法的秘密。由于彩色化技术，这些方法利用从二维图像中学习的滤波器来提取2.5D中的有意义的表示。尽管如此，这两种图像的感知特征却非常不同，其中第一种通常以纹理为特征，第二种则以物体的轮廓为主。理想情况下，人们希望有两个CNN，一个用于RGB，另一个用于深度，每个都训练一个合适的数据集合，能够捕捉每个频道的感知属性，以完成当前的任务。由于缺乏合适的深度数据库，迄今为止尚不可能。本文针对这个问题，提出选择合成生成的图像，而不是手工收集2.5D大型数据库。虽然显然是真实数据的代表，但合成图像可以交换数量的质量，从而可以生成几乎无限量的数据。我们展示了从这样的数据收集中学习的滤波器，使用与视觉数据通常使用的相同的体系结构学习非常不同的滤波器，导致深度特征（a）能够更好地表征深度图像的不同方面，和（b）互补相对于从二维数据集预先训练的CNNs派生的那些。在两个公开可用的数据库上的实验显示了我们的方法的力量。

##### URL
[https://arxiv.org/abs/1609.09713](https://arxiv.org/abs/1609.09713)

##### PDF
[https://arxiv.org/pdf/1609.09713](https://arxiv.org/pdf/1609.09713)

