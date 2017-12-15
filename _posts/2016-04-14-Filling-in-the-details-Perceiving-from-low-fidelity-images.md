---
layout: post
title: "Filling in the details: Perceiving from low fidelity images"
date: 2016-04-14 12:10:23
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Farahnaz Ahmed Wick, Michael L. Wick, Marc Pomplun
mathjax: true
---

* content
{:toc}

##### Abstract
Humans perceive their surroundings in great detail even though most of our visual field is reduced to low-fidelity color-deprived (e.g. dichromatic) input by the retina. In contrast, most deep learning architectures are computationally wasteful in that they consider every part of the input when performing an image processing task. Yet, the human visual system is able to perform visual reasoning despite having only a small fovea of high visual acuity. With this in mind, we wish to understand the extent to which connectionist architectures are able to learn from and reason with low acuity, distorted inputs. Specifically, we train autoencoders to generate full-detail images from low-detail "foveations" of those images and then measure their ability to reconstruct the full-detail images from the foveated versions. By varying the type of foveation, we can study how well the architectures can cope with various types of distortion. We find that the autoencoder compensates for lower detail by learning increasingly global feature functions. In many cases, the learnt features are suitable for reconstructing the original full-detail image. For example, we find that the networks accurately perceive color in the periphery, even when 75\% of the input is achromatic.

##### Abstract (translated by Google)
尽管我们的大部分视野被降低到视网膜的低保真彩色剥夺（例如双色）输入，但人类仍然非常详细地察觉周围的环境。相比之下，大多数深度学习架构在计算上是浪费的，因为他们在执行图像处理任务时考虑输入的每个部分。然而，人的视觉系统能够进行视觉推理，尽管只有一小部分高视力的视力。考虑到这一点，我们希望了解联结主义架构能够从低灵敏度，扭曲的输入中学习和推理的程度。具体来说，我们训练自动编码器从这些图像的低细节“foveations”生成全细节图像，然后测量它们从中心版本重构完整细节图像的能力。通过改变建筑的类型，我们可以研究建筑能够很好地应对各种类型的变形。我们发现，自动编码器通过学习越来越多的全局特征函数来补偿较低的细节。在很多情况下，学习的特征适合于重建原始的全细节图像。例如，我们发现，即使当输入的75％是无彩色的时候，网络也能准确地感知外围的颜色。

##### URL
[https://arxiv.org/abs/1604.04125](https://arxiv.org/abs/1604.04125)

##### PDF
[https://arxiv.org/pdf/1604.04125](https://arxiv.org/pdf/1604.04125)

