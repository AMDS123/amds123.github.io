---
layout: post
title: "Learnable pooling with Context Gating for video classification"
date: 2018-03-05 12:30:37
categories: arXiv_CV
tags: arXiv_CV Video_Caption CNN Video_Classification RNN Classification
author: Antoine Miech, Ivan Laptev, Josef Sivic
mathjax: true
---

* content
{:toc}

##### Abstract
Current methods for video analysis often extract frame-level features using pre-trained convolutional neural networks (CNNs). Such features are then aggregated over time e.g., by simple temporal averaging or more sophisticated recurrent neural networks such as long short-term memory (LSTM) or gated recurrent units (GRU). In this work we revise existing video representations and study alternative methods for temporal aggregation. We first explore clustering-based aggregation layers and propose a two-stream architecture aggregating audio and visual features. We then introduce a learnable non-linear unit, named Context Gating, aiming to model interdependencies among network activations. Our experimental results show the advantage of both improvements for the task of video classification. In particular, we evaluate our method on the large-scale multi-modal Youtube-8M v2 dataset and outperform all other methods in the Youtube 8M Large-Scale Video Understanding challenge.

##### Abstract (translated by Google)
目前用于视频分析的方法通常使用预先训练的卷积神经网络（CNN）来提取帧级特征。随后，例如通过简单的时间平均或更复杂的递归神经网络（例如长期短期记忆（LSTM）或门控循环单元（GRU））随时间聚合这些特征。在这项工作中，我们修改现有视频表示并研究时间聚合的替代方法。我们首先探讨基于聚类的聚合层，并提出一种聚合音频和视觉特征的双流体系结构。然后，我们引入一个名为Context Gating的可学习非线性单元，旨在模拟网络激活之间的相互依赖关系。我们的实验结果显示了视频分类任务的两个改进的优点。特别是，我们在大规模多模式Youtube-8M v2数据集上评估我们的方法，并优于Youtube 8M大规模视频理解挑战中的所有其他方法。

##### URL
[http://arxiv.org/abs/1706.06905](http://arxiv.org/abs/1706.06905)

##### PDF
[http://arxiv.org/pdf/1706.06905](http://arxiv.org/pdf/1706.06905)

