---
layout: post
title: "Robust and Fast Decoding of High-Capacity Color QR Codes for Mobile Applications"
date: 2017-04-21 09:01:43
categories: arXiv_CV
tags: arXiv_CV
author: Zhibo Yang, Huanle Xu, Jianyuan Deng, Chen Change Loy, Wing Cheong Lau
mathjax: true
---

* content
{:toc}

##### Abstract
The use of color in QR codes brings extra data capacity, but also inflicts tremendous challenges on the decoding process due to chromatic distortion, cross-channel color interference and illumination variation. Particularly, we further discover a new type of chromatic distortion in high-density color QR codes, cross-module color interference, caused by the high density which also makes the geometric distortion correction more challenging. To address these problems, we propose two approaches, namely, LSVM-CMI and QDA-CMI, which jointly model these different types of chromatic distortion. Extended from SVM and QDA, respectively, both LSVM-CMI and QDA-CMI optimize over a particular objective function to learn a color classifier. Furthermore, a robust geometric transformation method is proposed to accurately correct the geometric distortion for high-density color QR codes. We put forth and implement a framework for high-capacity color QR codes equipped with our methods, called HiQ. To evaluate the performance of HiQ, we collect a challenging large-scale color QR code dataset, CUHK-CQRC, which consists of 5390 high-density color QR code samples. The comparison with the baseline method [2] on CUHK-CQRC shows that HiQ at least outperforms [2] by 188% in decoding success rate and 60% in bit error rate. Our implementation of HiQ in iOS and Android also demonstrates the effectiveness of our framework in real-world applications.

##### Abstract (translated by Google)
在QR码中使用色彩带来了额外的数据容量，但是由于色彩失真，跨通道色彩干扰和光照变化，对解码过程也造成了巨大的挑战。特别是，我们进一步发现了高密度彩色QR码中的一种新的彩色失真，由高密度引起的跨模色干涉，这也使得几何失真校正更具挑战性。为了解决这些问题，我们提出了两种方法，即LSVM-CMI和QDA-CMI，它们共同模拟这些不同类型的色差。分别从SVM和QDA扩展，LSVM-CMI和QDA-CMI分别针对一个特定的目标函数进行优化，以学习一个颜色分类器。此外，还提出了一种稳健的几何变换方法来精确校正高密度彩色QR码的几何失真。我们提出并实施了一个配备我们的方法的高容量彩色QR码框架，称为HiQ。为了评估HiQ的性能，我们收集了具有挑战性的大规模彩色QR码数据集CUHK-CQRC，其由5390个高密度彩色QR码样本组成。与CUHK-CQRC的基线方法[2]的比较表明，HiQ在解码成功率上至少胜过188％，在误码率上胜过60％。我们在iOS和Android中实现HiQ也证明了我们的框架在实际应用中的有效性。

##### URL
[https://arxiv.org/abs/1704.06447](https://arxiv.org/abs/1704.06447)

##### PDF
[https://arxiv.org/pdf/1704.06447](https://arxiv.org/pdf/1704.06447)

