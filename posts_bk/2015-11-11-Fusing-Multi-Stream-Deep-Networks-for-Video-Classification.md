---
layout: post
title: "Fusing Multi-Stream Deep Networks for Video Classification"
date: 2015-11-11 01:29:44
categories: arXiv_CV
tags: arXiv_CV CNN Video_Classification Classification Prediction Relation Memory_Networks
author: Zuxuan Wu, Yu-Gang Jiang, Xi Wang, Hao Ye, Xiangyang Xue, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies deep network architectures to address the problem of video classification. A multi-stream framework is proposed to fully utilize the rich multimodal information in videos. Specifically, we first train three Convolutional Neural Networks to model spatial, short-term motion and audio clues respectively. Long Short Term Memory networks are then adopted to explore long-term temporal dynamics. With the outputs of the individual streams, we propose a simple and effective fusion method to generate the final predictions, where the optimal fusion weights are learned adaptively for each class, and the learning process is regularized by automatically estimated class relationships. Our contributions are two-fold. First, the proposed multi-stream framework is able to exploit multimodal features that are more comprehensive than those previously attempted. Second, we demonstrate that the adaptive fusion method using the class relationship as a regularizer outperforms traditional alternatives that estimate the weights in a "free" fashion. Our framework produces significantly better results than the state of the arts on two popular benchmarks, 92.2\% on UCF-101 (without using audio) and 84.9\% on Columbia Consumer Videos.

##### Abstract (translated by Google)
本文研究深度网络体系结构来解决视频分类问题。为了充分利用视频中丰富的多模信息，提出了一种多流的框架。具体而言，我们首先训练三个卷积神经网络分别对空间，短期运动和音频线索进行建模。然后采用长期短期记忆网络来探索长期的时间动态。利用单个流的输出，我们提出了一种简单而有效的融合方法来生成最终的预测结果，其中每个类自适应学习最优融合权重，学习过程通过自动估计的类别关系进行规则化。我们的贡献是双重的。首先，所提出的多流式框架能够利用比先前所尝试的更全面的多模式特征。其次，我们证明了使用类关系作为正规化的自适应融合方法胜过了以“自由”方式估计权重的传统方法。我们的框架比两个流行的基准测试的技术水平明显好于UCF-101（不使用音频）的92.2％和哥伦比亚消费者视频的84.9％。

##### URL
[https://arxiv.org/abs/1509.06086](https://arxiv.org/abs/1509.06086)

##### PDF
[https://arxiv.org/pdf/1509.06086](https://arxiv.org/pdf/1509.06086)

