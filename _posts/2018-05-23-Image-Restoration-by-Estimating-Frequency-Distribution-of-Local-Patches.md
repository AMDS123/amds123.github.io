---
layout: post
title: "Image Restoration by Estimating Frequency Distribution of Local Patches"
date: 2018-05-23 12:50:08
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Jaeyoung Yoo, Sang-ho Lee, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method to solve the image restoration problem, which tries to restore the details of a corrupted image, especially due to the loss caused by JPEG compression. We have treated an image in the frequency domain to explicitly restore the frequency components lost during image compression. In doing so, the distribution in the frequency domain is learned using the cross entropy loss. Unlike recent approaches, we have reconstructed the details of an image without using the scheme of adversarial training. Rather, the image restoration problem is treated as a classification problem to determine the frequency coefficient for each frequency band in an image patch. In this paper, we show that the proposed method effectively restores a JPEG-compressed image with more detailed high frequency components, making the restored image more vivid.

##### Abstract (translated by Google)
在本文中，我们提出了一种解决图像恢复问题的方法，该方法试图恢复损坏图像的细节，特别是由于JPEG压缩造成的损失。我们已经在频域中处理了一幅图像，以明确地恢复在图像压缩期间丢失的频率分量。在这样做时，使用交叉熵损失来学习频域中的分布。与最近的方法不同，我们在不使用对抗训练方案的情况下重构了图像的细节。相反，图像恢复问题被视为分类问题，以确定图像块中每个频带的频率系数。在本文中，我们表明，所提出的方法有效地恢复了一个JPEG压缩图像，具有更为详细的高频分量，使恢复的图像更加生动。

##### URL
[http://arxiv.org/abs/1805.09097](http://arxiv.org/abs/1805.09097)

##### PDF
[http://arxiv.org/pdf/1805.09097](http://arxiv.org/pdf/1805.09097)

