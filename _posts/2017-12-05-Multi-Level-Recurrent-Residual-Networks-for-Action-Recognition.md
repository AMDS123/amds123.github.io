---
layout: post
title: 'Multi-Level Recurrent Residual Networks for Action Recognition'
date: 2017-12-06 09:54:14
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Recognition
author: Zhenxing Zheng, Gaoyun An, Qiuqi Ruan
---

* content
{:toc}

##### Abstract
Most existing Convolutional Neural Networks(CNNs) used for action recognition are either difficult to optimize or underuse crucial temporal information. Inspired by the fact that LSTM consistently makes breakthrough in the task related to sequence, we propose a novel Multi-Level Recurrent Residual Networks(MRRN) model which incorporates three separate recognition streams. The proposed model could capture spatiotemporal information by employing ResNets to learn spatial representations from static frames and stacked SRUs to learn temporal dynamics. Three distinct-level models are fused by averaging their softmax scores to obtain the complementary video representations. They are trained end-to-end with greater efficiency compared to state-of-the-art models. Our contributions are shown as follows: First, we analyze the effect of diverse hyper-parameter settings qualitatively to illustrate the general tendency of performance. Additionally, we experiment with low-, mid-, high-level representations of the video in various time pooling manners, experimentally demonstrating how well different level representations contribute to action recognition. Besides, we also make comparisons of computation complexity between competitive methods to verify the efficiency. Finally, A series of experiments are carried out on two standard video action benchmarks of HMDB-51 and UCF-101 dataset. Experimental results show MRRN exceeds the majority of models which only take RGB data as input and obtains comparable performances with the state-of-the-art without additional data, achieving 51.3% on HMDB-51 and 81.9% on UCF-101.

##### Abstract (translated by Google)
用于动作识别的大多数现有的卷积神经网络（CNN）要么难以优化，要么使用不重要的时间信息。受到LSTM在序列相关任务方面不断突破的启发，本文提出了一种新的多级递归残差网络（MRRN）模型，该模型包含三个独立的识别流。所提出的模型可以捕获时空信息，通过采用ResNets来学习静态帧和堆叠SRU的空间表示来学习时间动态。通过平均他们的softmax分数来融合三个不同级别的模型以获得互补的视频表示。与最先进的模型相比，它们的端到端训练效率更高。我们的贡献如下：首先，定性地分析各种超参数设置的影响，以说明性能的总体趋势。另外，我们以各种时间池方式试验视频的低，中，高层表示，通过实验证明不同层次的表示对行为识别的贡献程度。此外，我们还对竞争方法之间的计算复杂性进行比较以验证效率。最后，对HMDB-51和UCF-101数据集的两个标准视频动作基准进行了一系列的实验。实验结果表明，MRRN超过了大部分仅以RGB数据为输入的模型，在没有附加数据的情况下获得与现有技术相当的性能，在HMDB-51上达到51.3％，在UCF-101上达到81.9％。

##### URL
[http://arxiv.org/abs/1711.08238](http://arxiv.org/abs/1711.08238)

