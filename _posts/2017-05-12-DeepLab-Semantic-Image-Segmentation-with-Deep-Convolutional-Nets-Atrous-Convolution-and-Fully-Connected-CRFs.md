---
layout: post
title: "DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs"
date: 2017-05-12 03:25:47
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction Quantitative
author: Liang-Chieh Chen, George Papandreou, Iasonas Kokkinos, Kevin Murphy, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the task of semantic image segmentation with Deep Learning and make three main contributions that are experimentally shown to have substantial practical merit. First, we highlight convolution with upsampled filters, or 'atrous convolution', as a powerful tool in dense prediction tasks. Atrous convolution allows us to explicitly control the resolution at which feature responses are computed within Deep Convolutional Neural Networks. It also allows us to effectively enlarge the field of view of filters to incorporate larger context without increasing the number of parameters or the amount of computation. Second, we propose atrous spatial pyramid pooling (ASPP) to robustly segment objects at multiple scales. ASPP probes an incoming convolutional feature layer with filters at multiple sampling rates and effective fields-of-views, thus capturing objects as well as image context at multiple scales. Third, we improve the localization of object boundaries by combining methods from DCNNs and probabilistic graphical models. The commonly deployed combination of max-pooling and downsampling in DCNNs achieves invariance but has a toll on localization accuracy. We overcome this by combining the responses at the final DCNN layer with a fully connected Conditional Random Field (CRF), which is shown both qualitatively and quantitatively to improve localization performance. Our proposed "DeepLab" system sets the new state-of-art at the PASCAL VOC-2012 semantic image segmentation task, reaching 79.7% mIOU in the test set, and advances the results on three other datasets: PASCAL-Context, PASCAL-Person-Part, and Cityscapes. All of our code is made publicly available online.

##### Abstract (translated by Google)
在这项工作中，我们解决了深度学习的语义图像分割的任务，并做出了三个主要贡献，实验证明具有实质性的优点。首先，我们强调上采样滤波器的卷积，或者“恶性卷积”，作为密集预测任务的强大工具。 Atrous卷积允许我们明确地控制在深度卷积神经网络内计算特征响应的分辨率。它还使我们能够有效地扩大过滤器的视野，以在不增加参数数量或计算量的情况下结合更大的上下文。其次，我们提出了恶性空间金字塔池（ASPP）以在多个尺度上强健地分割对象。 ASPP用多个采样率和有效的视场来探测具有滤波器的传入卷积要素图层，从而以多个比例捕获对象以及图像上下文。第三，通过结合DCNN和概率图模型的方法，我们改进了对象边界的局部化。在DCNNs中最常使用的最大汇集和下采样的组合实现了不变性，但是对定位精度有影响。我们通过将最终的DCNN层的响应与完全连接的条件随机场（CRF）相结合来克服这个问题，所述条件随机场（CRF）被定性和定量地显示以改善本地化性能。我们提出的“DeepLab”系统在PASCAL VOC-2012语义图像分割任务中设置了最新的技术水平，在测试集中达到了79.7％的mIOU，并在其他三个数据集上推进了结果：PASCAL-Context，PASCAL-Person部分和城市景观。我们所有的代码都是在网上公开的。

##### URL
[https://arxiv.org/abs/1606.00915](https://arxiv.org/abs/1606.00915)

##### PDF
[https://arxiv.org/pdf/1606.00915](https://arxiv.org/pdf/1606.00915)

