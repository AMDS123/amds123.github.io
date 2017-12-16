---
layout: post
title: "Image Matching via Loopy RNN"
date: 2017-06-18 15:58:23
categories: arXiv_CV
tags: arXiv_CV RNN Relation
author: Donghao Luo, Bingbing Ni, Yichao Yan, Xiaokang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing matching algorithms are one-off algorithms, i.e., they usually measure the distance between the two image feature representation vectors for only one time. In contrast, human's vision system achieves this task, i.e., image matching, by recursively looking at specific/related parts of both images and then making the final judgement. Towards this end, we propose a novel loopy recurrent neural network (Loopy RNN), which is capable of aggregating relationship information of two input images in a progressive/iterative manner and outputting the consolidated matching score in the final iteration. A Loopy RNN features two uniqueness. First, built on conventional long short-term memory (LSTM) nodes, it links the output gate of the tail node to the input gate of the head node, thus it brings up symmetry property required for matching. Second, a monotonous loss designed for the proposed network guarantees increasing confidence during the recursive matching process. Extensive experiments on several image matching benchmarks demonstrate the great potential of the proposed method.

##### Abstract (translated by Google)
大多数现有的匹配算法是一次性算法，即它们通常只测量两个图像特征表示向量之间的距离一次。相比之下，人类的视觉系统通过递归地查看两幅图像的特定/相关部分，然后作出最终判断来实现这个任务，即图像匹配。为此，本文提出了一种新的循环递归神经网络（Loopy RNN），它能够以渐进/迭代的方式对两幅输入图像的关系信息进行聚合，并在最终的迭代中输出合并后的匹配分数。 Loopy RNN具有两个独特之处。首先，在传统的长时间短内存（LSTM）节点的基础上，将尾节点的输出门连接到头节点的输入门，从而带来了匹配所需的对称性。其次，为所提议的网络设计的单调损失保证递归匹配过程中增加的信心。在几个图像匹配基准上的大量实验证明了所提出方法的巨大潜力。

##### URL
[https://arxiv.org/abs/1706.03190](https://arxiv.org/abs/1706.03190)

##### PDF
[https://arxiv.org/pdf/1706.03190](https://arxiv.org/pdf/1706.03190)

