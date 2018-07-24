---
layout: post
title: "Improving Automatic Skin Lesion Segmentation using Adversarial Learning based Data Argumentation"
date: 2018-07-23 00:42:25
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN
author: Lei Bi, Dagan Feng, Jinman Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of skin lesions is considered as an important step in computer aided diagnosis (CAD) for automated melanoma diagnosis. In recent years, segmentation methods based on fully convolutional networks (FCN) have achieved great success in general images. This success is primarily due to the leveraging of large labelled datasets to learn features that correspond to the shallow appearance as well as the deep semantics of the images. However, the dependence on large dataset does not translate well into medical images. To improve the FCN performance for skin lesion segmentations, researchers attempted to use specific cost functions or add post-processing algorithms to refine the coarse boundaries of the FCN results. However, the performance of these methods is heavily reliant on the tuning of many parameters and post-processing techniques. In this paper, we leverage the state-of-the-art image feature learning method of generative adversarial network (GAN) for its inherent ability to produce consistent and realistic image features by using deep neural networks and adversarial learning concept. We improve upon GAN such that skin lesion features can be learned at different level of complexities, in a controlled manner. The outputs from our method is then augmented to the existing FCN training data, thus increasing the overall feature diversity. We evaluated our method on the ISIC 2018 skin lesion segmentation challenge dataset and showed that it was more accurate and robust when compared to the existing skin lesion segmentation methods.

##### Abstract (translated by Google)
皮肤病变的分割被认为是用于自动化黑素瘤诊断的计算机辅助诊断（CAD）中的重要步骤。近年来，基于完全卷积网络（FCN）的分割方法在一般图像中取得了巨大成功。这种成功主要归功于利用大型标记数据集来学习与浅层外观以及图像的深层语义相对应的特征。然而，对大数据集的依赖性并不能很好地转化为医学图像。为了改善皮肤病变分割的FCN性能，研究人员尝试使用特定的成本函数或添加后处理算法来细化FCN结果的粗略边界。然而，这些方法的性能严重依赖于许多参数和后处理技术的调整。在本文中，我们利用最先进的生成对抗网络（GAN）图像特征学习方法，通过使用深度神经网络和对抗性学习概念，使其具有产生一致和逼真图像特征的固有能力。我们改进了GAN，使得可以以受控的方式在不同的复杂程度上学习皮肤病变特征。然后，我们的方法的输出被扩充到现有的FCN训练数据，从而增加了整体特征的多样性。我们在ISIC 2018皮肤病变分割挑战数据集上评估了我们的方法，并表明与现有的皮肤病变分割方法相比，它更加准确和稳健。

##### URL
[http://arxiv.org/abs/1807.08392](http://arxiv.org/abs/1807.08392)

##### PDF
[http://arxiv.org/pdf/1807.08392](http://arxiv.org/pdf/1807.08392)

