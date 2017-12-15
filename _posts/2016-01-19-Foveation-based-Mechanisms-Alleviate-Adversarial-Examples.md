---
layout: post
title: "Foveation-based Mechanisms Alleviate Adversarial Examples"
date: 2016-01-19 18:15:28
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Yan Luo, Xavier Boix, Gemma Roig, Tomaso Poggio, Qi Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
We show that adversarial examples, i.e., the visually imperceptible perturbations that result in Convolutional Neural Networks (CNNs) fail, can be alleviated with a mechanism based on foveations---applying the CNN in different image regions. To see this, first, we report results in ImageNet that lead to a revision of the hypothesis that adversarial perturbations are a consequence of CNNs acting as a linear classifier: CNNs act locally linearly to changes in the image regions with objects recognized by the CNN, and in other regions the CNN may act non-linearly. Then, we corroborate that when the neural responses are linear, applying the foveation mechanism to the adversarial example tends to significantly reduce the effect of the perturbation. This is because, hypothetically, the CNNs for ImageNet are robust to changes of scale and translation of the object produced by the foveation, but this property does not generalize to transformations of the perturbation. As a result, the accuracy after a foveation is almost the same as the accuracy of the CNN without the adversarial perturbation, even if the adversarial perturbation is calculated taking into account a foveation.

##### Abstract (translated by Google)
我们表明，敌对的例子，即导致卷积神经网络（CNNs）失败的视觉不可察觉的扰动，可以通过基于方法的机制 - 在不同图像区域中应用CNN来减轻。为了看到这一点，我们首先在ImageNet中报告结果，导致修改对抗性扰动是CNN作为线性分类器的结果的假设：CNNs以线性方式对图像区域中的变化进行操作，而在其他地区CNN可能会非线性地起作用。然后，我们证实了当神经反应是线性的时候，将对策机制应用于敌对的例子中会显着减少扰动的影响。这是因为，假设地，CNN对于所产生的物体的尺度和平移的变化是鲁棒的，但是这个性质并没有推广到摄动的变换。其结果是，即使在计算对抗性扰动时考虑到一个中心，但是一个中心的准确性与没有对抗性扰动的CNN的准确度几乎是一样的。

##### URL
[https://arxiv.org/abs/1511.06292](https://arxiv.org/abs/1511.06292)

##### PDF
[https://arxiv.org/pdf/1511.06292](https://arxiv.org/pdf/1511.06292)

