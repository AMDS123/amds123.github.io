---
layout: post
title: "Reblur2Deblur: Deblurring Videos via Self-Supervised Learning"
date: 2018-01-16 05:02:09
categories: arXiv_CV
tags: arXiv_CV Inference
author: Huaijin Chen, Jinwei Gu, Orazio Gallo, Ming-Yu Liu, Ashok Veeraraghavan, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Motion blur is a fundamental problem in computer vision as it impacts image quality and hinders inference. Traditional deblurring algorithms leverage the physics of the image formation model and use hand-crafted priors: they usually produce results that better reflect the underlying scene, but present artifacts. Recent learning-based methods implicitly extract the distribution of natural images directly from the data and use it to synthesize plausible images. Their results are impressive, but they are not always faithful to the content of the latent image. We present an approach that bridges the two. Our method fine-tunes existing deblurring neural networks in a self-supervised fashion by enforcing that the output, when blurred based on the optical flow between subsequent frames, matches the input blurry image. We show that our method significantly improves the performance of existing methods on several datasets both visually and in terms of image quality metrics. The supplementary material is https://goo.gl/nYPjEQ

##### Abstract (translated by Google)
运动模糊是计算机视觉中的一个基本问题，因为它会影响图像质量并阻碍推理。传统的去模糊算法利用图像形成模型的物理特性，并使用手工制作的先验：它们通常会产生更好地反映底层场景的结果，但是会出现文物。最近的基于学习的方法直接从数据中直接提取自然图像的分布，并用它来合成合理的图像。他们的结果令人印象深刻，但他们并不总是忠实于潜像的内容。我们提出了一种桥接两者的方法。我们的方法通过强调在基于后续帧之间的光流模糊的输出匹配输入模糊图像时以自监督的方式对现有的去模糊神经网络进行微调。我们表明，我们的方法在视觉上以及在图像质量指标方面显着提高了现有方法在几个数据集上的性能。补充材料是https://goo.gl/nYPjEQ

##### URL
[http://arxiv.org/abs/1801.05117](http://arxiv.org/abs/1801.05117)

##### PDF
[http://arxiv.org/pdf/1801.05117](http://arxiv.org/pdf/1801.05117)

