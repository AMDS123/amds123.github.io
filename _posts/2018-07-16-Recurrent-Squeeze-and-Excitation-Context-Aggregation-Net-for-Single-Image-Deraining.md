---
layout: post
title: "Recurrent Squeeze-and-Excitation Context Aggregation Net for Single Image Deraining"
date: 2018-07-16 06:49:22
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Xia Li, Jianlong Wu, Zhouchen Lin, Hong Liu, Hongbin Zha
mathjax: true
---

* content
{:toc}

##### Abstract
Rain streaks can severely degrade the visibility, which causes many current computer vision algorithms fail to work. So it is necessary to remove the rain from images. We propose a novel deep network architecture based on deep convolutional and recurrent neural networks for single image deraining. As contextual information is very important for rain removal, we first adopt the dilated convolutional neural network to acquire large receptive field. To better fit the rain removal task, we also modify the network. In heavy rain, rain streaks have various directions and shapes, which can be regarded as the accumulation of multiple rain streak layers. We assign different alpha-values to various rain streak layers according to the intensity and transparency by incorporating the squeeze-and-excitation block. Since rain streak layers overlap with each other, it is not easy to remove the rain in one stage. So we further decompose the rain removal into multiple stages. Recurrent neural network is incorporated to preserve the useful information in previous stages and benefit the rain removal in later stages. We conduct extensive experiments on both synthetic and real-world datasets. Our proposed method outperforms the state-of-the-art approaches under all evaluation metrics. Codes and supplementary material are available at our project webpage: https://xialipku.github.io/RESCAN .

##### Abstract (translated by Google)
雨水条纹会严重降低能见度，导致许多当前的计算机视觉算法无法工作。因此有必要去除图像中的雨水。我们提出了一种基于深度卷积和递归神经网络的新型深度网络体系结构，用于单图像去除。由于背景信息对于降雨非常重要，我们首先采用扩张卷积神经网络来获取大的感受野。为了更好地适应除雨任务，我们还修改了网络。在大雨中，雨水条纹有各种方向和形状，可以看作是多个雨水层的积累。我们通过结合挤压和激发块，根据强度和透明度为不同的雨条纹层分配不同的α值。由于雨条纹层彼此重叠，因此在一个阶段中不容易除去雨水。因此我们进一步将雨水分解分为多个阶段。结合递归神经网络以保留先前阶段中的有用信息并有利于后期的除雨。我们对合成数据集和现实数据集进行了大量实验。我们提出的方法在所有评估指标下都优于最先进的方法。代码和补充材料可在我们的项目网页上找到：https：//xialipku.github.io/RESCAN。

##### URL
[http://arxiv.org/abs/1807.05698](http://arxiv.org/abs/1807.05698)

##### PDF
[http://arxiv.org/pdf/1807.05698](http://arxiv.org/pdf/1807.05698)

