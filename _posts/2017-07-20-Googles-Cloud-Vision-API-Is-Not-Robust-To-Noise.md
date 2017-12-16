---
layout: post
title: "Google's Cloud Vision API Is Not Robust To Noise"
date: 2017-07-20 05:31:16
categories: arXiv_CV
tags: arXiv_CV Adversarial Face
author: Hossein Hosseini, Baicen Xiao, Radha Poovendran
mathjax: true
---

* content
{:toc}

##### Abstract
Google has recently introduced the Cloud Vision API for image analysis. According to the demonstration website, the API "quickly classifies images into thousands of categories, detects individual objects and faces within images, and finds and reads printed words contained within images." It can be also used to "detect different types of inappropriate content from adult to violent content." In this paper, we evaluate the robustness of Google Cloud Vision API to input perturbation. In particular, we show that by adding sufficient noise to the image, the API generates completely different outputs for the noisy image, while a human observer would perceive its original content. We show that the attack is consistently successful, by performing extensive experiments on different image types, including natural images, images containing faces and images with texts. For instance, using images from ImageNet dataset, we found that adding an average of 14.25% impulse noise is enough to deceive the API. Our findings indicate the vulnerability of the API in adversarial environments. For example, an adversary can bypass an image filtering system by adding noise to inappropriate images. We then show that when a noise filter is applied on input images, the API generates mostly the same outputs for restored images as for original images. This observation suggests that cloud vision API can readily benefit from noise filtering, without the need for updating image analysis algorithms.

##### Abstract (translated by Google)
Google最近推出了用于图像分析的Cloud Vision API。根据演示网站，API“可以快速将图像分类为数千种类别，检测图像中的单个物体和脸部，并查找和读取图像中包含的印刷单词”。它也可以用来“检测从成人到暴力内容的不同类型的不当内容”。在本文中，我们评估了Google Cloud Vision API输入扰动的稳健性。特别是，我们表明，通过给图像添加足够的噪声，API为噪声图像生成完全不同的输出，而人类观察者会感知其原始内容。我们通过在不同的图像类型上进行大量的实验，包括自然图像，包含面部的图像和带有文本的图像，证明攻击始终是成功的。例如，使用来自ImageNet数据集的图像，我们发现添加平均14.25％的脉冲噪声足以欺骗API。我们的研究结果表明API在对抗环境中的脆弱性。例如，攻击者可以通过向不适当的图像添加噪声来绕过图像过滤系统。然后我们显示，当噪声滤波器应用于输入图像时，API对于恢复的图像产生与原始图像大部分相同的输出。这一观察结果表明，云视觉API很容易从噪声过滤中受益，而不需要更新图像分析算法。

##### URL
[https://arxiv.org/abs/1704.05051](https://arxiv.org/abs/1704.05051)

##### PDF
[https://arxiv.org/pdf/1704.05051](https://arxiv.org/pdf/1704.05051)

