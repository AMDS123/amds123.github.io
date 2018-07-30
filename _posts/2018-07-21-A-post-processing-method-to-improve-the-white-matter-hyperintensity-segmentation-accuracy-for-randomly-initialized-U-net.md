---
layout: post
title: "A post-processing method to improve the white matter hyperintensity segmentation accuracy for randomly-initialized U-net"
date: 2018-07-21 12:45:45
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Quantitative
author: Yue Zhang, Wanli Chen, Yifan Chen, Xiaoying Tang
mathjax: true
---

* content
{:toc}

##### Abstract
White matter hyperintensity (WMH) is commonly found in elder individuals and appears to be associated with brain diseases. U-net is a convolutional network that has been widely used for biomedical image segmentation. Recently, U-net has been successfully applied to WMH segmentation. Random initialization is usally used to initialize the model weights in the U-net. However, the model may coverage to different local optima with different randomly initialized weights. We find a combination of thresholding and averaging the outputs of U-nets with different random initializations can largely improve the WMH segmentation accuracy. Based on this observation, we propose a post-processing technique concerning the way how averaging and thresholding are conducted. Specifically, we first transfer the score maps from three U-nets to binary masks via thresholding and then average those binary masks to obtain the final WMH segmentation. Both quantitative analysis (via the Dice similarity coefficient) and qualitative analysis (via visual examinations) reveal the superior performance of the proposed method. This post-processing technique is independent of the model used. As such, it can also be applied to situations where other deep learning models are employed, especially when random initialization is adopted and pre-training is unavailable.

##### Abstract (translated by Google)
白质高信号（WMH）常见于老年人，并且似乎与脑疾病有关。 U-net是一种卷积网络，已被广泛用于生物医学图像分割。最近，U-net已成功应用于WMH分割。随机初始化通常用于初始化U-net中的模型权重。然而，该模型可以覆盖不同的局部最优，具有不同的随机初始化权重。我们发现阈值和平均U-net的输出与不同的随机初始化的组合可以在很大程度上提高WMH分割的准确性。基于这一观察，我们提出了一种关于如何进行平均和阈值处理的后处理技术。具体来说，我们首先通过阈值处理将得分图从三个U网转移到二进制掩码，然后平均这些二进制掩码以获得最终的WMH分段。定量分析（通过Dice相似系数）和定性分析（通过视觉检查）揭示了所提出方法的优越性能。该后处理技术与所使用的模型无关。因此，它也可以应用于采用其他深度学习模型的情况，特别是当采用随机初始化并且不能进行预训练时。

##### URL
[http://arxiv.org/abs/1807.10600](http://arxiv.org/abs/1807.10600)

##### PDF
[http://arxiv.org/pdf/1807.10600](http://arxiv.org/pdf/1807.10600)

