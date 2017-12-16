---
layout: post
title: "A deep convolutional neural network using directional wavelets for low-dose X-ray CT reconstruction"
date: 2017-10-14 14:26:48
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Relation
author: Eunhee Kang, Junhong Min, Jong Chul Ye
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the potential risk of inducing cancers, radiation dose of X-ray CT should be reduced for routine patient scanning. However, in low-dose X-ray CT, severe artifacts usually occur due to photon starvation, beamhardening, etc, which decrease the reliability of diagnosis. Thus, high quality reconstruction from low-dose X-ray CT data has become one of the important research topics in CT community. Conventional model-based denoising approaches are, however, computationally very expensive, and image domain denoising approaches hardly deal with CT specific noise patterns. To address these issues, we propose an algorithm using a deep convolutional neural network (CNN), which is applied to wavelet transform coefficients of low-dose CT images. Specifically, by using a directional wavelet transform for extracting directional component of artifacts and exploiting the intra- and inter-band correlations, our deep network can effectively suppress CT specific noises. Moreover, our CNN is designed to have various types of residual learning architecture for faster network training and better denoising. Experimental results confirm that the proposed algorithm effectively removes complex noise patterns of CT images, originated from the reduced X-ray dose. In addition, we show that wavelet domain CNN is efficient in removing the noises from low-dose CT compared to an image domain CNN. Our results were rigorously evaluated by several radiologists and won the second place award in 2016 AAPM Low-Dose CT Grand Challenge. To the best of our knowledge, this work is the first deep learning architecture for low-dose CT reconstruction that has been rigorously evaluated and proven for its efficacy.

##### Abstract (translated by Google)
由于潜在的诱发癌症的风险，对于常规患者扫描，X射线CT的辐射剂量应当减少。然而，在低剂量X射线CT中，由于光子不足，光束硬化等，通常会出现严重的伪影，降低了诊断的可靠性。因此，低剂量X线CT数据的高质量重建已经成为CT界重要的研究课题之一。然而，传统的基于模型的去噪方法在计算上非常昂贵，并且图像域去噪方法很难处理CT特定的噪声模式。为了解决这些问题，我们提出了一种使用深度卷积神经网络（CNN）的算法，该算法被应用于低剂量CT图像的小波变换系数。具体而言，通过使用定向小波变换来提取伪像的方向分量并利用带内和带间相关性，我们的深度网络可以有效地抑制CT特定噪声。此外，我们的CNN被设计为具有各种类型的残留学习架构，以加快网络训练和更好的去噪。实验结果证实，所提出的算法有效地消除了来自减少的X射线剂量的CT图像的复杂噪声模式。另外，我们显示小波域CNN在消除低剂量CT相对于图像域CNN的噪音方面是有效的。我们的研究成果得到了几位放射科医生的严格评估，并在2016年AAPM低剂量CT大赛中获得第二名。据我们所知，这项工作是低剂量CT重建的第一个深度学习架构，经过了严格的评估和验证。

##### URL
[https://arxiv.org/abs/1610.09736](https://arxiv.org/abs/1610.09736)

##### PDF
[https://arxiv.org/pdf/1610.09736](https://arxiv.org/pdf/1610.09736)

