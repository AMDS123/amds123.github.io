---
layout: post
title: "Skeleton-Based Action Recognition with Spatial Reasoning and Temporal Stack Learning"
date: 2018-05-07 03:54:28
categories: arXiv_CV
tags: arXiv_CV Action_Recognition RNN Recognition
author: Chenyang Si, Ya Jing, Wei Wang, Liang Wang, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Skeleton-based action recognition has made great progress recently, but many problems still remain unsolved. For example, most of the previous methods model the representations of skeleton sequences without abundant spatial structure information and detailed temporal dynamics features. In this paper, we propose a novel model with spatial reasoning and temporal stack learning (SR-TSL) for skeleton based action recognition, which consists of a spatial reasoning network (SRN) and a temporal stack learning network (TSLN). The SRN can capture the high-level spatial structural information within each frame by a residual graph neural network, while the TSLN can model the detailed temporal dynamics of skeleton sequences by a composition of multiple skip-clip LSTMs. During training, we propose a clip-based incremental loss to optimize the model. We perform extensive experiments on the SYSU 3D Human-Object Interaction dataset and NTU RGB+D dataset and verify the effectiveness of each network of our model. The comparison results illustrate that our approach achieves much better results than state-of-the-art methods.

##### Abstract (translated by Google)
基于骨架的动作识别近来取得了很大进展，但许多问题仍未解决。例如，大多数先前的方法对骨架序列的表示进行建模，没有丰富的空间结构信息和详细的时间动态特征。在本文中，我们提出了一种基于空间推理网络（SRN）和时间堆栈学习网络（TSLN）的基于骨架的动作识别的空间推理和时间堆栈学习（SR-TSL）的新模型。 SRN可以通过残差图形神经网络捕获每个帧内的高层空间结构信息，而TSLN可以通过多个跳跃片段LSTM的组合构建骨架序列的详细时间动态。在培训期间，我们提出了一个基于剪辑的增量损失来优化模型。我们在SYSU 3D人体对象交互数据集和NTU RGB + D数据集上进行了大量实验，并验证了我们模型的每个网络的有效性。比较结果表明，我们的方法比最先进的方法取得更好的结果。

##### URL
[http://arxiv.org/abs/1805.02335](http://arxiv.org/abs/1805.02335)

##### PDF
[http://arxiv.org/pdf/1805.02335](http://arxiv.org/pdf/1805.02335)

