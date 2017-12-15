---
layout: post
title: "SegNet: A Deep Convolutional Encoder-Decoder Architecture for Robust Semantic Pixel-Wise Labelling"
date: 2015-05-27 12:54:17
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Prediction
author: Vijay Badrinarayanan, Ankur Handa, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel deep architecture, SegNet, for semantic pixel wise image labelling. SegNet has several attractive properties; (i) it only requires forward evaluation of a fully learnt function to obtain smooth label predictions, (ii) with increasing depth, a larger context is considered for pixel labelling which improves accuracy, and (iii) it is easy to visualise the effect of feature activation(s) in the pixel label space at any depth. SegNet is composed of a stack of encoders followed by a corresponding decoder stack which feeds into a soft-max classification layer. The decoders help map low resolution feature maps at the output of the encoder stack to full input image size feature maps. This addresses an important drawback of recent deep learning approaches which have adopted networks designed for object categorization for pixel wise labelling. These methods lack a mechanism to map deep layer feature maps to input dimensions. They resort to ad hoc methods to upsample features, e.g. by replication. This results in noisy predictions and also restricts the number of pooling layers in order to avoid too much upsampling and thus reduces spatial context. SegNet overcomes these problems by learning to map encoder outputs to image pixel labels. We test the performance of SegNet on outdoor RGB scenes from CamVid, KITTI and indoor scenes from the NYU dataset. Our results show that SegNet achieves state-of-the-art performance even without use of additional cues such as depth, video frames or post-processing with CRF models.

##### Abstract (translated by Google)
我们提出了一种新的深层架构，SegNet，用于语义像素明智的图像标记。 SegNet有几个有吸引力的属性; （i）只需要对完全学习的函数进行前向评估以获得平滑的标签预测，（ii）随着深度的增加，对像素标签考虑更大的上下文以提高准确性，以及（iii）易于可视化在任何深度的像素标签空间中激活特征。 SegNet由一堆编码器组成，后跟一个相应的解码器堆栈，将其馈入软最大分类层。解码器帮助将编码器堆栈的输出处的低分辨率特征映射映射到完整的输入图像大小特征映射。这解决了最近的深度学习方法的一个重要的缺点，这些方法采用了设计用于像素标记的对象分类的网络。这些方法缺乏将深层图层特征映射到输入维度的机制。他们采用临时的方法来上传特征，例如通过复制。这导致嘈杂的预测，也限制了池层的数量，以避免太多的上采样，从而减少空间上下文。 SegNet通过学习将编码器输出映射到图像像素标签来克服这些问题。我们测试SegNet在CamVid，KITTI室外RGB场景和NYU数据集室内场景的性能。我们的研究结果显示，即使不使用深度，视频帧或CRF模型后处理等附加提示，SegNet也可以实现最先进的性能。

##### URL
[https://arxiv.org/abs/1505.07293](https://arxiv.org/abs/1505.07293)

##### PDF
[https://arxiv.org/pdf/1505.07293](https://arxiv.org/pdf/1505.07293)

