---
layout: post
title: "Denoising of 3D magnetic resonance images with multi-channel residual learning of convolutional neural network"
date: 2017-12-23 07:35:51
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Dongsheng Jiang, Weiqiang Dou, Luc Vosters, Xiayu Xu, Yue Sun, Tao Tan
mathjax: true
---

* content
{:toc}

##### Abstract
The denoising of magnetic resonance (MR) images is a task of great importance for improving the acquired image quality. Many methods have been proposed in the literature to retrieve noise free images with good performances. Howerever, the state-of-the-art denoising methods, all needs a time-consuming optimization processes and their performance strongly depend on the estimated noise level parameter. Within this manuscript we propose the idea of denoising MRI Rician noise using a convolutional neural network. The advantage of the proposed methodology is that the learning based model can be directly used in the denosing process without optimization and even without the noise level parameter. Specifically, a ten convolutional layers neural network combined with residual learning and multi-channel strategy was proposed. Two training ways: training on a specific noise level and training on a general level were conducted to demonstrate the capability of our methods. Experimental results over synthetic and real 3D MR data demonstrate our proposed network can achieve superior performance compared with other methods in term of both of the peak signal to noise ratio and the global of structure similarity index. Without noise level parameter, our general noise-applicable model is also better than the other compared methods in two datasets. Furthermore, our training model shows good general applicability.

##### Abstract (translated by Google)
磁共振（MR）图像的去噪是提高图像质量的重要任务。在文献中已经提出许多方法来检索具有良好性能的无噪声图像。但是，最先进的去噪方法都需要耗费时间的优化过程，其性能强烈依赖于估计的噪声水平参数。在这个手稿中，我们提出了使用卷积神经网络去噪MRI Rician噪声的想法。所提出的方法的优点在于，基于学习的模型可以直接用于没有优化的去噪处理，甚至没有噪声水平参数。具体而言，提出了一种结合残差学习和多通道策略的卷积层神经网络。两种培训方式：特定噪音水平的培训和一般水平的培训，以展示我们的方法的能力。在合成和真实3D MR数据上的实验结果表明，我们提出的网络在峰值信噪比和全局结构相似性指数方面与其他方法相比可以实现优越的性能。没有噪声水平参数，我们的一般噪声适用模型在两个数据集中也比其他比较方法好。此外，我们的培训模式显示出良好的普遍适用性。

##### URL
[http://arxiv.org/abs/1712.08726](http://arxiv.org/abs/1712.08726)

##### PDF
[http://arxiv.org/pdf/1712.08726](http://arxiv.org/pdf/1712.08726)

