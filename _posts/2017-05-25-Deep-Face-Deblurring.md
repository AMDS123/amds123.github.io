---
layout: post
title: "Deep Face Deblurring"
date: 2017-05-25 07:45:36
categories: arXiv_CV
tags: arXiv_CV Attention Face
author: Grigorios G. Chrysos, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Blind deblurring consists a long studied task, however the outcomes of generic methods are not effective in real world blurred images. Domain-specific methods for deblurring targeted object categories, e.g. text or faces, frequently outperform their generic counterparts, hence they are attracting an increasing amount of attention. In this work, we develop such a domain-specific method to tackle deblurring of human faces, henceforth referred to as face deblurring. Studying faces is of tremendous significance in computer vision, however face deblurring has yet to demonstrate some convincing results. This can be partly attributed to the combination of i) poor texture and ii) highly structure shape that yield the contour/gradient priors (that are typically used) sub-optimal. In our work instead of making assumptions over the prior, we adopt a learning approach by inserting weak supervision that exploits the well-documented structure of the face. Namely, we utilise a deep network to perform the deblurring and employ a face alignment technique to pre-process each face. We additionally surpass the requirement of the deep network for thousands training samples, by introducing an efficient framework that allows the generation of a large dataset. We utilised this framework to create 2MF2, a dataset of over two million frames. We conducted experiments with real world blurred facial images and report that our method returns a result close to the sharp natural latent image.

##### Abstract (translated by Google)
盲目去模糊是一个长期研究的任务，然而，通用方法的结果在现实世界模糊图像中是无效的。去模糊目标对象类别的领域专用方法，例如文字或面孔，经常胜过他们的通用对手，因此他们正在吸引越来越多的关注。在这项工作中，我们开发了这样一个领域特定的方法来解决人脸的去模糊问题，以下称为脸部去模糊。学习面孔在计算机视觉中具有非常重要的意义，然而脸部去模糊还没有显示出一些令人信服的结果。这可能部分归因于i）质地差和ii）高度结构形状的组合，其产生的轮廓/梯度先验（通常使用）是次优的。在我们的工作中，不是对事先做出假设，而是采取一种学习方法，通过插入利用记录良好的面部结构的弱监督。也就是说，我们利用深度网络进行去模糊，并采用人脸对齐技术对每个人脸进行预处理。我们还通过引入一个高效的框架来生成大型数据集，从而超越了数千个训练样本的深度网络需求。我们利用这个框架创建了2MF2，一个超过200万帧的数据集。我们对真实世界的模糊人脸图像进行了实验，并报告说我们的方法返回的结果接近于尖锐的自然潜像。

##### URL
[https://arxiv.org/abs/1704.08772](https://arxiv.org/abs/1704.08772)

##### PDF
[https://arxiv.org/pdf/1704.08772](https://arxiv.org/pdf/1704.08772)

