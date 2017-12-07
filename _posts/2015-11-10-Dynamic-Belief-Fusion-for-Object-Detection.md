---
layout: post
title: "Dynamic Belief Fusion for Object Detection"
date: 2015-11-10 17:03:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hyungtae Lee, Heesung Kwon, Ryan M. Robinson, William d. Nothwang, Amar M. Marathe
mathjax: true
---

* content
{:toc}

##### Abstract
A novel approach for the fusion of heterogeneous object detection methods is proposed. In order to effectively integrate the outputs of multiple detectors, the level of ambiguity in each individual detection score is estimated using the precision/recall relationship of the corresponding detector. The main contribution of the proposed work is a novel fusion method, called Dynamic Belief Fusion (DBF), which dynamically assigns probabilities to hypotheses (target, non-target, intermediate state (target or non-target)) based on confidence levels in the detection results conditioned on the prior performance of individual detectors. In DBF, a joint basic probability assignment, optimally fusing information from all detectors, is determined by the Dempster's combination rule, and is easily reduced to a single fused detection score. Experiments on ARL and PASCAL VOC 07 datasets demonstrate that the detection accuracy of DBF is considerably greater than conventional fusion approaches as well as individual detectors used for the fusion.

##### Abstract (translated by Google)
提出了一种异构目标检测方法融合的新方法。为了有效地整合多个检测器的输出，使用相应检测器的精度/回忆关系来估计每个单独检测分数的模糊度水平。所提出的工作的主要贡献是一种被称为动态信任融合（DBF）的新型融合方法，该方法基于置信水平中的置信水平动态地将概率分配给假设（目标，非目标，中间状态（目标或非目标））检测结果取决于各个检测器的先前性能。在DBF中，联合基本概率分配，最优融合来自所有检测器的信息，由Dempster组合规则确定，并且很容易减少到单个融合检测分数。 ARL和PASCAL VOC 07数据集上的实验表明，DBF的检测精度远远高于传统的融合方法以及用于融合的单个检测器。

##### URL
[https://arxiv.org/abs/1511.03183](https://arxiv.org/abs/1511.03183)

##### PDF
[https://arxiv.org/pdf/1511.03183](https://arxiv.org/pdf/1511.03183)

