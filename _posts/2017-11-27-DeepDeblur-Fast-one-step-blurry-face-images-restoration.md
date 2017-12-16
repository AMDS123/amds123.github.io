---
layout: post
title: "DeepDeblur: Fast one-step blurry face images restoration"
date: 2017-11-27 02:52:38
categories: arXiv_CV
tags: arXiv_CV Regularization Face CNN Deep_Learning Recognition Face_Recognition
author: Lingxiao Wang, Yali Li, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a very fast and effective one-step restoring method for blurry face images. In the last decades, many blind deblurring algorithms have been proposed to restore latent sharp images. However, these algorithms run slowly because of involving two steps: kernel estimation and following non-blind deconvolution or latent image estimation. Also they cannot handle face images in small size. Our proposed method restores sharp face images directly in one step using Convolutional Neural Network. Unlike previous deep learning involved methods that can only handle a single blur kernel at one time, our network is trained on totally random and numerous training sample pairs to deal with the variances due to different blur kernels in practice. A smoothness regularization as well as a facial regularization are added to keep facial identity information which is the key to face image applications. Comprehensive experiments demonstrate that our proposed method can handle various blur kenels and achieve state-of-the-art results for small size blurry face images restoration. Moreover, the proposed method shows significant improvement in face recognition accuracy along with increasing running speed by more than 100 times.

##### Abstract (translated by Google)
我们提出了一种快速有效的一步恢复模糊人脸图像的方法。在过去的几十年中，已经提出了许多盲去模糊算法来恢复潜在的清晰图像。然而，这些算法运行缓慢，因为涉及两个步骤：核估计和非盲卷积或潜像估计。他们也无法处理小尺寸的脸部图像。我们提出的方法使用卷积神经网络直接恢复一个人脸上的清晰图像。与之前的深度学习不同，它涉及到一次只能处理一个模糊核的方法，我们的网络在完全随机的和众多的训练样本对上进行训练，以处理实际中由于不同的模糊核所造成的方差。增加了光滑正则化和面部正则化，保持了面部图像应用的关键所在。全面的实验表明，我们提出的方法可以处理各种模糊角膜，并实现小尺寸模糊人脸图像恢复的最新成果。此外，所提出的方法显示出随着运行速度提高100倍以上，脸部识别精度显着提高。

##### URL
[https://arxiv.org/abs/1711.09515](https://arxiv.org/abs/1711.09515)

##### PDF
[https://arxiv.org/pdf/1711.09515](https://arxiv.org/pdf/1711.09515)

