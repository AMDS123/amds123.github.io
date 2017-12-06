---
layout: post
title: "Zoom Out-and-In Network with Map Attention Decision for Region Proposal and Object Detection"
date: 2017-09-13 14:18:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Hongyang Li, Yu Liu, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a zoom-out-and-in network for generating object proposals. A key observation is that it is difficult to classify anchors of different sizes with the same set of features. Anchors of different sizes should be placed accordingly based on different depth within a network: smaller boxes on high-resolution layers with a smaller stride while larger boxes on low-resolution counterparts with a larger stride. Inspired by the conv/deconv structure, we fully leverage the low-level local details and high-level regional semantics from two feature map streams, which are complimentary to each other, to identify the objectness in an image. A map attention decision (MAD) unit is further proposed to aggressively search for neuron activations among two streams and attend the most contributive ones on the feature learning of the final loss. The unit serves as a decision maker to adaptively activate maps along certain channels with the solely purpose of optimizing the overall training loss. One advantage of MAD is that the learned weights enforced on each feature channel is predicted on-the-fly based on the input context, which is more suitable than the fixed enforcement of a convolutional kernel. Experimental results on three datasets demonstrate the effectiveness of our proposed algorithm over other state-of-the-arts, in terms of average recall for region proposal and average precision for object detection.

##### Abstract (translated by Google)
在本文中，我们提出了一个生成对象提议的缩小和放大网络。一个关键的观察是难以用相同的一组特征对不同大小的锚进行分类。不同大小的锚点应根据网络中的不同深度进行相应的放置：高分辨率层上较小步长的小盒子，步幅较大的低分辨率层次上较大的盒子。受conv / deconv结构的启发，我们充分利用两个相互补充的特征地图流中的低级本地细节和高级区域语义来识别图像中的对象。进一步提出了地图注意决定（MAD）单元来积极搜索两个流之间的神经元激活，并参与对最终损失的特征学习的贡献最大的单元。该单位作为一个决策者，以自适应地激活某些渠道的地图，目的是优化整体训练损失。 MAD的一个优点是基于输入上下文对每个特征信道强制学习的权重进行了实时预测，这比卷积核的固定执行更适合。在三个数据集上的实验结果证明了我们提出的算法相对于其他现有技术的有效性，就区域提议的平均召回和对象检测的平均精度而言。

##### URL
[https://arxiv.org/abs/1709.04347](https://arxiv.org/abs/1709.04347)

