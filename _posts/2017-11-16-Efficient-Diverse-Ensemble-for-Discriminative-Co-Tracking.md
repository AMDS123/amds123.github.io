---
layout: post
title: "Efficient Diverse Ensemble for Discriminative Co-Tracking"
date: 2017-11-16 08:34:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking
author: Kourosh Meshgi, Shigeyuki Oba, Shin Ishii
mathjax: true
---

* content
{:toc}

##### Abstract
Ensemble discriminative tracking utilizes a committee of classifiers, to label data samples, which are in turn, used for retraining the tracker to localize the target using the collective knowledge of the committee. Committee members could vary in their features, memory update schemes, or training data, however, it is inevitable to have committee members that excessively agree because of large overlaps in their version space. To remove this redundancy and have an effective ensemble learning, it is critical for the committee to include consistent hypotheses that differ from one-another, covering the version space with minimum overlaps. In this study, we propose an online ensemble tracker that directly generates a diverse committee by generating an efficient set of artificial training. The artificial data is sampled from the empirical distribution of the samples taken from both target and background, whereas the process is governed by query-by-committee to shrink the overlap between classifiers. The experimental results demonstrate that the proposed scheme outperforms conventional ensemble trackers on public benchmarks.

##### Abstract (translated by Google)
集合判别式跟踪利用一个分类器委员会来标记数据样本，这些数据样本又被用来对跟踪器进行再训练，以使用委员会的集体知识来定位目标。委员会成员的特征，记忆更新方案或培训数据可能会有所不同，但由于版本空间的重叠，导致委员会成员过度认同是不可避免的。为了消除这种冗余并进行有效的集成学习，委员会必须包含一致的假设，这些假设彼此不同，覆盖版本空间的重叠最小。在这项研究中，我们提出了一个在线集成跟踪器，通过生成一组高效的人工培训，直接生成一个多样化的委员会。人工数据是从取自目标和背景的样本的经验分布中采样的，而该过程由委员会查询来控制，以缩小分类器之间的重叠。实验结果表明，该方案优于传统的公共基准跟踪器。

##### URL
[https://arxiv.org/abs/1711.06564](https://arxiv.org/abs/1711.06564)

##### PDF
[https://arxiv.org/pdf/1711.06564](https://arxiv.org/pdf/1711.06564)

