---
layout: post
title: "Learning and Refining of Privileged Information-based RNNs for Action Recognition from Depth Sequences"
date: 2017-08-08 11:49:02
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Embedding RNN Classification Recognition
author: Zhiyuan Shi, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Existing RNN-based approaches for action recognition from depth sequences require either skeleton joints or hand-crafted depth features as inputs. An end-to-end manner, mapping from raw depth maps to action classes, is non-trivial to design due to the fact that: 1) single channel map lacks texture thus weakens the discriminative power; 2) relatively small set of depth training data. To address these challenges, we propose to learn an RNN driven by privileged information (PI) in three-steps: An encoder is pre-trained to learn a joint embedding of depth appearance and PI (i.e. skeleton joints). The learned embedding layers are then tuned in the learning step, aiming to optimize the network by exploiting PI in a form of multi-task loss. However, exploiting PI as a secondary task provides little help to improve the performance of a primary task (i.e. classification) due to the gap between them. Finally, a bridging matrix is defined to connect two tasks by discovering latent PI in the refining step. Our PI-based classification loss maintains a consistency between latent PI and predicted distribution. The latent PI and network are iteratively estimated and updated in an expectation-maximization procedure. The proposed learning process provides greater discriminative power to model subtle depth difference, while helping avoid overfitting the scarcer training data. Our experiments show significant performance gains over state-of-the-art methods on three public benchmark datasets and our newly collected Blanket dataset.

##### Abstract (translated by Google)
现有的基于RNN的深度序列动作识别方法需要骨架关节或手工制作的深度特征作为输入。一个端到端的方式，从原始的深度映射到动作类的映射，由于以下事实是非常重要的：1）单通道映射缺乏纹理，从而削弱了判别能力; 2）相对较小的一组深度训练数据。为了解决这些挑战，我们建议通过三步学习由特权信息（PI）驱动的RNN：编码器被预先训练以学习深度外观和PI（即骨架关节）的联合嵌入。然后在学习步骤中对学习到的嵌入层进行调整，以通过以多任务丢失的形式利用PI来优化网络。然而，利用PI作为次要任务，由于它们之间的差距，对于改善主要任务（即分类）的性能几乎没有帮助。最后，定义桥接矩阵，通过在精炼步骤中发现潜在的PI来连接两个任务。我们基于PI的分类损失保持了潜在的PI和预测分配之间的一致性。潜在的PI和网络在期望最大化过程中迭代地估计和更新。所提出的学习过程提供了更大的区分能力来模拟细微的深度差异，同时帮助避免过度拟合稀缺的训练数据。我们的实验显示，在三个公共基准数据集和我们新收集的Blanket数据集上，相比于最先进的方法，性能显着提高。

##### URL
[https://arxiv.org/abs/1703.09625](https://arxiv.org/abs/1703.09625)

##### PDF
[https://arxiv.org/pdf/1703.09625](https://arxiv.org/pdf/1703.09625)

