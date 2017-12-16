---
layout: post
title: "Feature Enhancement Network: A Refined Scene Text Detector"
date: 2017-11-12 08:12:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Sheng Zhang, Yuliang Liu, Lianwen Jin, Canjie Luo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a refined scene text detector with a \textit{novel} Feature Enhancement Network (FEN) for Region Proposal and Text Detection Refinement. Retrospectively, both region proposal with \textit{only} $3\times 3$ sliding-window feature and text detection refinement with \textit{single scale} high level feature are insufficient, especially for smaller scene text. Therefore, we design a new FEN network with \textit{task-specific}, \textit{low} and \textit{high} level semantic features fusion to improve the performance of text detection. Besides, since \textit{unitary} position-sensitive RoI pooling in general object detection is unreasonable for variable text regions, an \textit{adaptively weighted} position-sensitive RoI pooling layer is devised for further enhancing the detecting accuracy. To tackle the \textit{sample-imbalance} problem during the refinement stage, we also propose an effective \textit{positives mining} strategy for efficiently training our network. Experiments on ICDAR 2011 and 2013 robust text detection benchmarks demonstrate that our method can achieve state-of-the-art results, outperforming all reported methods in terms of F-measure.

##### Abstract (translated by Google)
在本文中，我们提出了一个改进的场景文本检测器，用于区域建议和文本检测细化的特征增强网络（FEN）。回顾性地，对于\ textit {only} $ 3 \ times 3 $滑动窗口特征的区域建议和\ textit {单个比例}高级特征的文本检测细化是不够的，尤其是对于较小的场景文本。因此，我们设计了一个新的FEN网络，该网络具有\ textit {任务特定}，\ textit {低}和\ textit {高}级语义特征融合，以提高文本检测的性能。此外，由于在一般对象检测中的\ textit {统一}位置敏感RoI池对于可变文本区域是不合理的，因此设计了一种自适应加权的位置敏感RoI池层以进一步提高检测精度。为了在精化阶段解决“样本不平衡”问题，我们还提出了一个有效的正文挖掘策略来有效地培训我们的网络。在ICDAR 2011和2013强健文本检测基准上进行的实验表明，我们的方法可以达到最新的结果，在F-measure方面优于所有已报告的方法。

##### URL
[https://arxiv.org/abs/1711.04249](https://arxiv.org/abs/1711.04249)

##### PDF
[https://arxiv.org/pdf/1711.04249](https://arxiv.org/pdf/1711.04249)

