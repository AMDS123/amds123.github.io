---
layout: post
title: "Adversarial Examples for Semantic Segmentation and Object Detection"
date: 2017-07-21 17:27:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Semantic_Segmentation Detection Recognition
author: Cihang Xie, Jianyu Wang, Zhishuai Zhang, Yuyin Zhou, Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
It has been well demonstrated that adversarial examples, i.e., natural images with visually imperceptible perturbations added, generally exist for deep networks to fail on image classification. In this paper, we extend adversarial examples to semantic segmentation and object detection which are much more difficult. Our observation is that both segmentation and detection are based on classifying multiple targets on an image (e.g., the basic target is a pixel or a receptive field in segmentation, and an object proposal in detection), which inspires us to optimize a loss function over a set of pixels/proposals for generating adversarial perturbations. Based on this idea, we propose a novel algorithm named Dense Adversary Generation (DAG), which generates a large family of adversarial examples, and applies to a wide range of state-of-the-art deep networks for segmentation and detection. We also find that the adversarial perturbations can be transferred across networks with different training data, based on different architectures, and even for different recognition tasks. In particular, the transferability across networks with the same architecture is more significant than in other cases. Besides, summing up heterogeneous perturbations often leads to better transfer performance, which provides an effective method of black-box adversarial attack.

##### Abstract (translated by Google)
已经很好地证明，通常存在对抗性的例子，即具有视觉不可察觉的扰动的自然图像，深网络通常存在图像分类失败。在本文中，我们将对立的例子扩展到更难的语义分割和对象检测。我们的观察是，分割和检测都基于对图像上的多个目标进行分类（例如，基本目标是分割中的像素或接受区域，以及检测中的目标提议），这激励我们优化丢失函数用于产生敌对扰动的一组像素/建议。基于这个思想，我们提出了一种新的算法Dense Adversary Generation（DAG），它产生了一个很大的对抗性的例子，并且应用于各种最先进的深度网络中进行分割和检测。我们还发现，基于不同的体系结构，甚至不同的识别任务，敌对扰动可以跨不同训练数据的网络传输。尤其是，具有相同体系结构的网络之间的可转移性比其他情况下更显着。另外，总结异质性扰动常常导致更好的传输性能，为黑盒对抗攻击提供了一种有效的方法。

##### URL
[https://arxiv.org/abs/1703.08603](https://arxiv.org/abs/1703.08603)

