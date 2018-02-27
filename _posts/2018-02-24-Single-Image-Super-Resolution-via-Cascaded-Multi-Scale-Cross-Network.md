---
layout: post
title: "Single Image Super-Resolution via Cascaded Multi-Scale Cross Network"
date: 2018-02-24 06:16:34
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge CNN Prediction Quantitative
author: Yanting Hu, Xinbo Gao, Jie Li, Yuanfei Huang, Hanzi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The deep convolutional neural networks have achieved significant improvements in accuracy and speed for single image super-resolution. However, as the depth of network grows, the information flow is weakened and the training becomes harder and harder. On the other hand, most of the models adopt a single-stream structure with which integrating complementary contextual information under different receptive fields is difficult. To improve information flow and to capture sufficient knowledge for reconstructing the high-frequency details, we propose a cascaded multi-scale cross network (CMSC) in which a sequence of subnetworks is cascaded to infer high resolution features in a coarse-to-fine manner. In each cascaded subnetwork, we stack multiple multi-scale cross (MSC) modules to fuse complementary multi-scale information in an efficient way as well as to improve information flow across the layers. Meanwhile, by introducing residual-features learning in each stage, the relative information between high-resolution and low-resolution features is fully utilized to further boost reconstruction performance. We train the proposed network with cascaded-supervision and then assemble the intermediate predictions of the cascade to achieve high quality image reconstruction. Extensive quantitative and qualitative evaluations on benchmark datasets illustrate the superiority of our proposed method over state-of-the-art super-resolution methods.

##### Abstract (translated by Google)
深卷积神经网络在单幅图像超分辨率的准确性和速度方面取得了显着的进步。然而，随着网络深度的增长，信息流动减弱，培训变得越来越困难。另一方面，大多数模型采用单流结构，难以在不同的接受领域集成互补的上下文信息。为了改善信息流并捕获足够的知识来重构高频细节，我们提出了一个级联多尺度交叉网络（CMSC），其中一系列子网络级联以便以粗到细的方式推断高分辨率特征。在每个级联子网络中，我们堆叠多个多尺度交叉（MSC）模块，以高效的方式融合互补的多尺度信息，并改善层间的信息流。同时，通过在每个阶段引入残差特征学习，充分利用高分辨率和低分辨率特征之间的相对信息进一步提升重建性能。我们通过级联监督对拟议的网络进行训练，然后组合级联的中间预测来实现高质量的图像重建。对基准数据集进行广泛的定量和定性评估说明了我们提出的方法优于最先进的超分辨率方法的优势。

##### URL
[http://arxiv.org/abs/1802.08808](http://arxiv.org/abs/1802.08808)

##### PDF
[http://arxiv.org/pdf/1802.08808](http://arxiv.org/pdf/1802.08808)

