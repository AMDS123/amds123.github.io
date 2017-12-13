---
layout: post
title: "200x Low-dose PET Reconstruction using Deep Learning"
date: 2017-12-12 04:13:27
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Junshen Xu, Enhao Gong, John Pauly, Greg Zaharchuk
mathjax: true
---

* content
{:toc}

##### Abstract
Positron emission tomography (PET) is widely used in various clinical applications, including cancer diagnosis, heart disease and neuro disorders. The use of radioactive tracer in PET imaging raises concerns due to the risk of radiation exposure. To minimize this potential risk in PET imaging, efforts have been made to reduce the amount of radio-tracer usage. However, lowing dose results in low Signal-to-Noise-Ratio (SNR) and loss of information, both of which will heavily affect clinical diagnosis. Besides, the ill-conditioning of low-dose PET image reconstruction makes it a difficult problem for iterative reconstruction algorithms. Previous methods proposed are typically complicated and slow, yet still cannot yield satisfactory results at significantly low dose. Here, we propose a deep learning method to resolve this issue with an encoder-decoder residual deep network with concatenate skip connections. Experiments shows the proposed method can reconstruct low-dose PET image to a standard-dose quality with only two-hundredth dose. Different cost functions for training model are explored. Multi-slice input strategy is introduced to provide the network with more structural information and make it more robust to noise. Evaluation on ultra-low-dose clinical data shows that the proposed method can achieve better result than the state-of-the-art methods and reconstruct images with comparable quality using only 0.5% of the original regular dose.

##### Abstract (translated by Google)
正电子发射断层扫描（PET）广泛用于各种临床应用，包括癌症诊断，心脏病和神经疾病。放射性示踪剂在PET成像中的使用引起了辐射风险的担忧。为了尽量减少PET成像的潜在风险，已经做出努力来减少无线电示踪剂的使用量。然而，剂量下降导致信噪比（SNR）低和信息损失，这两者都将严重影响临床诊断。此外，低剂量PET图像重建的不适应性使其成为迭代重建算法的难题。提出的以前的方法通常是复杂和缓慢的，但仍然不能在显着低剂量下产生令人满意的结果。在这里，我们提出了一种深度学习方法来解决这个问题与编码器 - 解码器残余深度网络连接跳过连接。实验表明，所提出的方法可以将低剂量的PET图像重建为仅有二百分之一剂量的标准剂量质量。探讨了培训模式的不同成本函数。引入多切片输入策略，为网络提供更多的结构信息，使其对噪声更加鲁棒。对超低剂量临床数据的评估表明，所提出的方法可以获得比现有技术方法更好的结果，并且仅使用原始规律剂量的0.5％来重建具有可比较质量的图像。

##### URL
[http://arxiv.org/abs/1712.04119](http://arxiv.org/abs/1712.04119)

##### PDF
[http://arxiv.org/pdf/1712.04119](http://arxiv.org/pdf/1712.04119)

