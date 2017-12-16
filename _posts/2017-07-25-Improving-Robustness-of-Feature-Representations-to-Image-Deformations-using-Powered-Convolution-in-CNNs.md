---
layout: post
title: "Improving Robustness of Feature Representations to Image Deformations using Powered Convolution in CNNs"
date: 2017-07-25 06:33:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge CNN Detection Recognition
author: Zhun Sun, Mete Ozay, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we address the problem of improvement of robustness of feature representations learned using convolutional neural networks (CNNs) to image deformation. We argue that higher moment statistics of feature distributions could be shifted due to image deformations, and the shift leads to degrade of performance and cannot be reduced by ordinary normalization methods as observed in experimental analyses. In order to attenuate this effect, we apply additional non-linearity in CNNs by combining power functions with learnable parameters into convolution operation. In the experiments, we observe that CNNs which employ the proposed method obtain remarkable boost in both the generalization performance and the robustness under various types of deformations using large scale benchmark datasets. For instance, a model equipped with the proposed method obtains 3.3\% performance boost in mAP on Pascal Voc object detection task using deformed images, compared to the reference model, while both models provide the same performance using original images. To the best of our knowledge, this is the first work that studies robustness of deep features learned using CNNs to a wide range of deformations for object recognition and detection.

##### Abstract (translated by Google)
在这项工作中，我们解决了使用卷积神经网络（CNNs）学习图像变形的特征表示的鲁棒性的改善问题。我们认为，由于图像变形，特征分布的较高时刻统计量可能会发生偏移，这种偏移会导致性能的下降，而且不能像实验分析中所观察到的那样通过普通的归一化方法来降低。为了减弱这种效应，我们通过将功率函数与可学习的参数组合成卷积运算来在CNN中应用附加的非线性。在实验中，我们观察到使用所提出的方法的CNN在使用大规模基准数据集的各种类型的变形下在泛化性能和鲁棒性方面得到显着提高。例如，与参考模型相比，使用变形图像的Pascal Voc对象检测任务中，具有所提出的方法的模型在mAP上获得3.3％的性能提升，而两个模型使用原始图像提供相同的性能。据我们所知，这是第一项研究使用CNN学习深度特征的鲁棒性来进行物体识别和检测的各种变形。

##### URL
[https://arxiv.org/abs/1707.07830](https://arxiv.org/abs/1707.07830)

##### PDF
[https://arxiv.org/pdf/1707.07830](https://arxiv.org/pdf/1707.07830)

