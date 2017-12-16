---
layout: post
title: "Dirty Pixels: Optimizing Image Classification Architectures for Raw Sensor Data"
date: 2017-01-23 16:46:12
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Image_Classification Classification
author: Steven Diamond, Vincent Sitzmann, Stephen Boyd, Gordon Wetzstein, Felix Heide
mathjax: true
---

* content
{:toc}

##### Abstract
Real-world sensors suffer from noise, blur, and other imperfections that make high-level computer vision tasks like scene segmentation, tracking, and scene understanding difficult. Making high-level computer vision networks robust is imperative for real-world applications like autonomous driving, robotics, and surveillance. We propose a novel end-to-end differentiable architecture for joint denoising, deblurring, and classification that makes classification robust to realistic noise and blur. The proposed architecture dramatically improves the accuracy of a classification network in low light and other challenging conditions, outperforming alternative approaches such as retraining the network on noisy and blurry images and preprocessing raw sensor inputs with conventional denoising and deblurring algorithms. The architecture learns denoising and deblurring pipelines optimized for classification whose outputs differ markedly from those of state-of-the-art denoising and deblurring methods, preserving fine detail at the cost of more noise and artifacts. Our results suggest that the best low-level image processing for computer vision is different from existing algorithms designed to produce visually pleasing images. The principles used to design the proposed architecture easily extend to other high-level computer vision tasks and image formation models, providing a general framework for integrating low-level and high-level image processing.

##### Abstract (translated by Google)
现实世界中的传感器受到噪声，模糊和其他缺陷的影响，使高级计算机视觉任务如场景分割，跟踪和场景理解变得困难。使高层次的计算机视觉网络强大，对于自动驾驶，机器人和监视等实际应用来说是必不可少的。我们提出了一种新颖的端到端可微结构，用于联合去噪，去模糊和分类，使得分类对逼真的噪声和模糊变得鲁棒。所提出的体系结构在低照度和其他具有挑战性的条件下显着提高了分类网络的准确性，优于诸如在噪声和模糊图像上再训练网络和使用传统去噪和去模糊算法预处理原始传感器输入的替代方法。该架构学习了针对分类进行优化的去噪和去模糊管线，其输出与最先进的去噪和去模糊方法的输出明显不同，以更多噪声和伪影为代价来保留细节。我们的研究结果表明，计算机视觉的最佳低级图像处理不同于现有算法设计来产生视觉上令人愉快的图像。用于设计所提出的体系结构的原理很容易扩展到其他高级计算机视觉任务和图像形成模型，为集成低级和高级图像处理提供了一个通用框架。

##### URL
[https://arxiv.org/abs/1701.06487](https://arxiv.org/abs/1701.06487)

##### PDF
[https://arxiv.org/pdf/1701.06487](https://arxiv.org/pdf/1701.06487)

