---
layout: post
title: "Feature Mapping for Learning Fast and Accurate 3D Pose Inference from Synthetic Images"
date: 2017-12-11 17:27:49
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference
author: Mahdi Rad, Markus Oberweger, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple and efficient method for exploiting synthetic images when training a Deep Network to predict a 3D pose from an image. The ability of using synthetic images for training a Deep Network is extremely valuable as it is easy to create a virtually infinite training set made of such images, while capturing and annotating real images can be very cumbersome. However, synthetic images do not resemble real images exactly, and using them for training can result in suboptimal performance. It was recently shown that for exemplar-based approaches, it is possible to learn a mapping from the exemplar representations of real images to the exemplar representations of synthetic images. In this paper, we show that this approach is more general, and that a network can also be applied after the mapping to infer a 3D pose: At run time, given a real image of the target object, we first compute the features for the image, map them to the feature space of synthetic images, and finally use the resulting features as input to another network which predicts the 3D pose. Since this network can be trained very effectively by using synthetic images, it performs very well in practice, and inference is faster and more accurate than with an exemplar-based approach. We demonstrate our approach on the LINEMOD dataset for 3D object pose estimation from color images, and the NYU dataset for 3D hand pose estimation from depth maps. We show that it allows us to outperform the state-of-the-art on both datasets.

##### Abstract (translated by Google)
我们提出了一种简单而有效的方法来训练深度网络来预测图像的三维姿态时利用合成图像。使用合成图像来训练深度网络的能力是非常有价值的，因为很容易创建由这样的图像组成的几乎无限的训练集，而捕捉和注释真实图像可能是非常麻烦的。但是，合成图像并不完全类似于真实图像，将其用于训练可能会导致性能不理想。最近表明，对于基于样本的方法，可以学习从真实图像的示例性表示到合成图像的示例性表示的映射。在本文中，我们展示了这种方法更一般化，并且网络也可以在映射之后应用来推断3D姿态：在运行时，给定目标对象的真实图像，我们首先计算图像，将它们映射到合成图像的特征空间，最后将所得特征用作预测三维姿态的另一网络的输入。由于这个网络可以通过使用合成图像非常有效地进行训练，所以它在实践中表现得非常好，推理比基于样本的方法更快，更准确。我们在LINEMOD数据集上展示了我们的方法，用于从彩色图像中进行3D对象姿态估计以及从深度图中进行3D手姿态估计的NYU数据集。我们表明，它使我们能够胜过两个数据集上的最新技术。

##### URL
[http://arxiv.org/abs/1712.03904](http://arxiv.org/abs/1712.03904)

##### PDF
[http://arxiv.org/pdf/1712.03904](http://arxiv.org/pdf/1712.03904)

