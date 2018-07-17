---
layout: post
title: "Towards Single-phase Single-stage Detection of Pulmonary Nodules in Chest CT Imaging"
date: 2018-07-16 17:10:11
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Deep_Learning Detection
author: Zhongliu Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of pulmonary nodules in chest CT imaging plays a crucial role in early diagnosis of lung cancer. Manual examination is highly time-consuming and error prone, calling for computer-aided detection, both to improve efficiency and reduce misdiagnosis. Over the years, a range of systems have been proposed, mostly following a two-phase paradigm with: 1) candidate detection, 2) false positive reduction. Recently, deep learning has become a dominant force in algorithm development. As for candidate detection, prior art was mainly based on the two-stage Faster R-CNN framework, which starts with an initial sub-net to generate a set of class-agnostic region proposals, followed by a second sub-net to perform classification and bounding-box regression. In contrast, we abandon the conventional two-phase paradigm and two-stage framework altogether and propose to train a single network for end-to-end nodule detection instead, without transfer learning or further post-processing. Our feature learning model is a modification of the ResNet and feature pyramid network combined, powered by RReLU activation. The major challenge is the condition of extreme inter-class and intra-class sample imbalance, where the positives are overwhelmed by a large negative pool, which is mostly composed of easy and a handful of hard negatives. Direct training on all samples can seriously undermine training efficacy. We propose a patch-based sampling strategy over a set of regularly updating anchors, which narrows sampling scope to all positives and only hard negatives, effectively addressing this issue. As a result, our approach substantially outperforms prior art in terms of both accuracy and speed. Finally, the prevailing FROC evaluation over [1/8, 1/4, 1/2, 1, 2, 4, 8] false positives per scan, is far from ideal in real clinical environments. We suggest FROC over [1, 2, 4] false positives as a better metric.

##### Abstract (translated by Google)
胸部CT成像中肺结节的检测在肺癌的早期诊断中起着至关重要的作用。手动检查非常耗时且容易出错，需要进行计算机辅助检测，以提高效率并减少误诊。多年来，已经提出了一系列系统，主要遵循两阶段范例：1）候选检测，2）假阳性减少。最近，深度学习已经成为算法开发的主导力量。对于候选检测，现有技术主要基于两阶段更快的R-CNN框架，其以初始子网开始以生成一组类别不可知区域提议，接着是第二子网以执行分类。和边界框回归。相比之下，我们完全放弃了传统的两阶段范式和两阶段框架，并建议在没有转移学习或进一步后处理的情况下训练单个网络进行端到端结节检测。我们的特征学习模型是对ResNet和功能金字塔网络的修改，由RReLU激活提供支持。主要挑战是极端阶级间和阶级内部样本不平衡的情况，其中积极因素被大量负面池所压倒，这种负面池主要由简单和少量的硬性负面组成。对所有样本进行直接培训会严重影响培训效果。我们针对一组定期更新的锚点提出了基于补丁的采样策略，这样可以将采样范围缩小到所有正面和只有硬性负面，从而有效地解决了这个问题。结果，我们的方法在准确性和速度方面基本上优于现有技术。最后，对于每次扫描的[1/8,1 / 4,1 / 2,1,2,4,8]误报，主流的FROC评估在实际临床环境中远非理想。我们建议FROC超过[1,2,4]误报作为更好的指标。

##### URL
[http://arxiv.org/abs/1807.05972](http://arxiv.org/abs/1807.05972)

##### PDF
[http://arxiv.org/pdf/1807.05972](http://arxiv.org/pdf/1807.05972)

