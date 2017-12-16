---
layout: post
title: "Reducing Complexity of HEVC: A Deep Learning Approach"
date: 2017-09-19 02:02:00
categories: arXiv_CV
tags: arXiv_CV CNN Optimization RNN Deep_Learning Relation
author: Mai Xu, Tianyi Li, Zulin Wang, Xin Deng, Zhenyu Guan
mathjax: true
---

* content
{:toc}

##### Abstract
High Efficiency Video Coding (HEVC) significantly reduces bit-rates over the proceeding H.264 standard but at the expense of extremely high encoding complexity. In HEVC, the quad-tree partition of coding unit (CU) consumes a large proportion of the HEVC encoding complexity, due to the bruteforce search for rate-distortion optimization (RDO). Therefore, this paper proposes a deep learning approach to predict the CU partition for reducing the HEVC complexity at both intraand inter-modes, which is based on convolutional neural network (CNN) and long- and short-term memory (LSTM) network. First, we establish a large-scale database including substantial CU partition data for HEVC intra- and inter-modes. This enables deep learning on the CU partition. Second, we represent the CU partition of an entire coding tree unit (CTU) in the form of a hierarchical CU partition map (HCPM). Then, we propose an early-terminated hierarchical CNN (ETH-CNN) for learning to predict the HCPM. Consequently, the encoding complexity of intra-mode HEVC can be drastically reduced by replacing the brute-force search with ETH-CNN to decide the CU partition. Third, an early-terminated hierarchical LSTM (ETH-LSTM) is proposed to learn the temporal correlation of the CU partition. Then, we combine ETH-LSTM and ETH-CNN to predict the CU partition for reducing the HEVC complexity for intermode. Finally, experimental results show that our approach outperforms other state-of-the-art approaches in reducing the HEVC complexity at both intra- and inter-modes.

##### Abstract (translated by Google)
高效率视频编码（HEVC）显着降低了正在进行的H.264标准的比特率，但代价是非常高的编码复杂度。在HEVC中，由于对速率失真优化（RDO）的强力搜索，编码单元（CU）的四叉树分区消耗HEVC编码复杂度的大部分。因此，本文提出了一种基于卷积神经网络（CNN）和长短期记忆（LSTM）网络的深度学习方法来预测用于降低HEVC复杂度的CU划分。首先，我们建立一个大规模的数据库，包括HEVC模式内部和模式间的CU分区数据。这使得CU分区上的深入学习成为可能。其次，我们以分层CU分区映射（HCPM）的形式表示整个编码树单元（CTU）的CU分区。然后，我们提出一个早期终止的层次CNN（ETH-CNN）来学习预测HCPM。因此，通过用ETH-CNN代替蛮力搜索来确定CU分区，可以大大降低帧内模式HEVC的编码复杂度。第三，为了学习CU分区的时间相关性，提出了一个提前终止的分层LSTM（ETH-LSTM）。然后，我们结合ETH-LSTM和ETH-CNN来预测用于减少HEVC复杂度的CU分区。最后，实验结果表明，我们的方法在降低帧内和帧间模式下的HEVC复杂度方面优于其他现有技术的方法。

##### URL
[https://arxiv.org/abs/1710.01218](https://arxiv.org/abs/1710.01218)

##### PDF
[https://arxiv.org/pdf/1710.01218](https://arxiv.org/pdf/1710.01218)

