---
layout: post
title: "Perceptual Adversarial Networks for Image-to-Image Transformation"
date: 2017-06-28 07:04:08
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Relation
author: Chaoyue Wang, Chang Xu, Chaohui Wang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a principled Perceptual Adversarial Networks (PAN) for image-to-image transformation tasks. Unlike existing application-specific algorithms, PAN provides a generic framework of learning mapping relationship between paired images (Fig. 1), such as mapping a rainy image to its de-rained counterpart, object edges to its photo, semantic labels to a scenes image, etc. The proposed PAN consists of two feed-forward convolutional neural networks (CNNs), the image transformation network T and the discriminative network D. Through combining the generative adversarial loss and the proposed perceptual adversarial loss, these two networks can be trained alternately to solve image-to-image transformation tasks. Among them, the hidden layers and output of the discriminative network D are upgraded to continually and automatically discover the discrepancy between the transformed image and the corresponding ground-truth. Simultaneously, the image transformation network T is trained to minimize the discrepancy explored by the discriminative network D. Through the adversarial training process, the image transformation network T will continually narrow the gap between transformed images and ground-truth images. Experiments evaluated on several image-to-image transformation tasks (e.g., image de-raining, image inpainting, etc.) show that the proposed PAN outperforms many related state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一个原理性的感知对抗网络（PAN）的图像到图像转换任务。与现有的应用程序特定算法不同，PAN提供了一个通用的学习映射关系（如图1所示）的配对图像之间的映射框架，如将雨天图像映射到其对应的图像，将对象边缘映射到其照片，将语义标签映射到场景图像等等。所提出的PAN由两个前馈卷积神经网络（CNN），图像变换网络T和判别网络D组成。通过结合生成对抗损失和提出的感知对抗损失，可以交替地训练这两个网络解决图像到图像的转换任务。其中，判别式网络D的隐含层和输出被升级为不断自动发现变换后的图像与相应的真实情况之间的差异。同时，对图像变换网络T进行训练，以最小化由辨别网络D探测到的差异。通过对抗训练过程，图像变换网络T将不断缩小变换图像和地面真实图像之间的差距。在几个图像到图像转换任务（例如，图像去除，图像修补等）上评估的实验表明，所提出的PAN优于许多相关的最先进的方法。

##### URL
[https://arxiv.org/abs/1706.09138](https://arxiv.org/abs/1706.09138)

##### PDF
[https://arxiv.org/pdf/1706.09138](https://arxiv.org/pdf/1706.09138)

