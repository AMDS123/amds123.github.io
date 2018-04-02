---
layout: post
title: "Contrast-Oriented Deep Neural Networks for Salient Object Detection"
date: 2018-03-30 09:51:04
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Sparse Attention Embedding CNN Inference Prediction Detection
author: Guanbin Li, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have become a key element in the recent breakthrough of salient object detection. However, existing CNN-based methods are based on either patch-wise (region-wise) training and inference or fully convolutional networks. Methods in the former category are generally time-consuming due to severe storage and computational redundancies among overlapping patches. To overcome this deficiency, methods in the second category attempt to directly map a raw input image to a predicted dense saliency map in a single network forward pass. Though being very efficient, it is arduous for these methods to detect salient objects of different scales or salient regions with weak semantic information. In this paper, we develop hybrid contrast-oriented deep neural networks to overcome the aforementioned limitations. Each of our deep networks is composed of two complementary components, including a fully convolutional stream for dense prediction and a segment-level spatial pooling stream for sparse saliency inference. We further propose an attentional module that learns weight maps for fusing the two saliency predictions from these two streams. A tailored alternate scheme is designed to train these deep networks by fine-tuning pre-trained baseline models. Finally, a customized fully connected CRF model incorporating a salient contour feature embedding can be optionally applied as a post-processing step to improve spatial coherence and contour positioning in the fused result from these two streams. Extensive experiments on six benchmark datasets demonstrate that our proposed model can significantly outperform the state of the art in terms of all popular evaluation metrics.

##### Abstract (translated by Google)
深卷积神经网络已成为最近突破显着物体检测的关键因素。然而，现有的基于CNN的方法是基于补丁方式（区域方式）训练和推理或完全卷积网络。由于严重的存储和重叠补丁之间的计算冗余，前一类中的方法通常是耗时的。为了克服这个缺陷，第二类中的方法试图将原始输入图像直接映射到单个网络正向通道中的预测密集显着图。虽然效率很高，但是这些方法检测不同尺度的显着物体或弱语义信息的显着区域是很困难的。在本文中，我们开发了混合对比度导向的深度神经网络来克服上述限制。我们每个深层网络都由两个互补的组件组成，包括用于密集预测的完全卷积流和用于稀疏显着性推断的段级空间池流。我们进一步提出了一个注意模块，该模块可以学习用于融合来自这两个流的两个显着性预测的权重图。定制的替代方案旨在通过对预先训练的基线模型进行微调来训练这些深度网络。最后，一个定制的完全连接的CRF模型包含了一个显着的轮廓特征嵌入，可以作为后处理步骤选择性地应用于改善这两个流的融合结果中的空间相干性和轮廓定位。在六个基准数据集上的大量实验表明，我们提出的模型在所有流行的评估指标方面都可以显着优于现有技术水平。

##### URL
[https://arxiv.org/abs/1803.11395](https://arxiv.org/abs/1803.11395)

##### PDF
[https://arxiv.org/pdf/1803.11395](https://arxiv.org/pdf/1803.11395)

