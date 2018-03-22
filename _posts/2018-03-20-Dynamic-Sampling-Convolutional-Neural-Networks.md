---
layout: post
title: "Dynamic Sampling Convolutional Neural Networks"
date: 2018-03-20 19:52:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Attention CNN Prediction Detection Recognition
author: Jialin Wu, Dai Li, Yu Yang, Chandrajit Bajaj, Xiangyang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
We present Dynamic Sampling Convolutional Neural Networks (DSCNN), where the position-specific kernels learn from not only the current position but also multiple sampled neighbour regions. During sampling, residual learning is introduced to ease training and an attention mechanism is applied to fuse features from different samples. And the kernels are further factorized to reduce parameters. The multiple sampling strategy enlarges the effective receptive fields significantly without requiring more parameters. While DSCNNs inherit the advantages of DFN, namely avoiding feature map blurring by position-specific kernels while keeping translation invariance, it also efficiently alleviates the overfitting issue caused by much more parameters than normal CNNs. Our model is efficient and can be trained end-to-end via standard back-propagation. We demonstrate the merits of our DSCNNs on both sparse and dense prediction tasks involving object detection and flow estimation. Our results show that DSCNNs enjoy stronger recognition abilities and achieve 81.7% in VOC2012 detection dataset. Also, DSCNNs obtain much sharper responses in flow estimation on FlyingChairs dataset compared to multiple FlowNet models' baselines.

##### Abstract (translated by Google)
我们提出了动态采样卷积神经网络（DSCNN），其中位置特定的内核不仅从当前位置学习，而且还从多个采样相邻区域学习。在采样期间，引入残留学习以减轻训练，并且应用关注机制来融合来自不同样本的特征。内核被进一步分解以减少参数。多重采样策略显着扩大了有效感受野，而不需要更多参数。尽管DSCNN继承了DFN的优势，即避免特定于位置的内核在保持平移不变的同时使特征映射模糊，但它也有效地缓解了比正常CNN更多的参数引起的过度拟合问题。我们的模型是高效的，可以通过标准的反向传播进行端对端培训。我们证明了我们的DSCNN在涉及物体检测和流量估计的稀疏和密集预测任务上的优点。我们的研究结果表明DSCNNs具有更强的识别能力，在VOC2012检测数据集中达到81.7％。此外，与多个FlowNet模型的基线相比，DSCNN在FlyingChairs数据集的流量估计中获得更加明显的响应。

##### URL
[http://arxiv.org/abs/1803.07624](http://arxiv.org/abs/1803.07624)

##### PDF
[http://arxiv.org/pdf/1803.07624](http://arxiv.org/pdf/1803.07624)

