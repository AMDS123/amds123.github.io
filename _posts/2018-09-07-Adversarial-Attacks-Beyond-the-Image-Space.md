---
layout: post
title: "Adversarial Attacks Beyond the Image Space"
date: 2018-09-07 03:20:11
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention Face Classification Prediction VQA
author: Xiaohui Zeng, Chenxi Liu, Yu-Siang Wang, Weichao Qiu, Lingxi Xie, Yu-Wing Tai, Chi Keung Tang, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Generating adversarial examples is an intriguing problem and an important way of understanding the working mechanism of deep neural networks. Most existing approaches generated perturbations in the image space, i.e., each pixel can be modified independently. However, in this paper we pay special attention to the subset of adversarial examples that are physically authentic -- those corresponding to actual changes in 3D physical properties (like surface normals, illumination condition, etc.). These adversaries arguably pose a more serious concern, as they demonstrate the possibility of causing neural network failure by small perturbations of real-world 3D objects and scenes. 
 In the contexts of object classification and visual question answering, we augment state-of-the-art deep neural networks that receive 2D input images with a rendering module (either differentiable or not) in front, so that a 3D scene (in the physical space) is rendered into a 2D image (in the image space), and then mapped to a prediction (in the output space). The adversarial perturbations can now go beyond the image space, and have clear meanings in the 3D physical world. Through extensive experiments, we found that a vast majority of image-space adversaries cannot be explained by adjusting parameters in the physical space, i.e., they are usually physically inauthentic. But it is still possible to successfully attack beyond the image space on the physical space (such that authenticity is enforced), though this is more difficult than image-space attacks, reflected in lower success rates and heavier perturbations required.

##### Abstract (translated by Google)
生成对抗性示例是一个有趣的问题，也是理解深度神经网络工作机制的重要方法。大多数现有方法在图像空间中产生扰动，即，每个像素可以独立地修改。然而，在本文中，我们特别关注物理上可靠的对抗性示例的子集 - 与3D物理属性的实际变化相对应的那些（如表面法线，光照条件等）。这些对手可能会引起更严重的关注，因为它们证明了通过对现实世界3D物体和场景的微小扰动导致神经网络失效的可能性。
 在对象分类和视觉问题回答的背景下，我们增加了最先进的深度神经网络，它接收2D输入图像，前面有渲染模块（可区分或不可分），因此3D场景（在物理上）空间）被渲染成2D图像（在图像空间中），然后映射到预测（在输出空间中）。对抗性扰动现在可以超越图像空间，并且在3D物理世界中具有明确的含义。通过大量实验，我们发现绝大多数图像空间对手无法通过调整物理空间中的参数来解释，即它们通常是物理上不真实的。但是仍然有可能成功地攻击物理空间上的图像空间（这样可以强制执行真实性），尽管这比图像空间攻击更难，反映在较低的成功率和较重的扰动需要。

##### URL
[http://arxiv.org/abs/1711.07183](http://arxiv.org/abs/1711.07183)

##### PDF
[http://arxiv.org/pdf/1711.07183](http://arxiv.org/pdf/1711.07183)

