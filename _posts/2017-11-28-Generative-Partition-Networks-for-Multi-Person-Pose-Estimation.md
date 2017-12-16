---
layout: post
title: "Generative Partition Networks for Multi-Person Pose Estimation"
date: 2017-11-28 12:10:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Pose_Estimation Embedding Optimization Inference Detection
author: Xuecheng Nie, Jiashi Feng, Junliang Xing, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new Generative Partition Network (GPN) to address the challenging multi-person pose estimation problem. Different from existing models that are either completely top-down or bottom-up, the proposed GPN introduces a novel strategy--it generates partitions for multiple persons from their global joint candidates and infers instance-specific joint configurations simultaneously. The GPN is favorably featured by low complexity and high accuracy of joint detection and re-organization. In particular, GPN designs a generative model that performs one feed-forward pass to efficiently generate robust person detections with joint partitions, relying on dense regressions from global joint candidates in an embedding space parameterized by centroids of persons. In addition, GPN formulates the inference procedure for joint configurations of human poses as a graph partition problem, and conducts local optimization for each person detection with reliable global affinity cues, leading to complexity reduction and performance improvement. GPN is implemented with the Hourglass architecture as the backbone network to simultaneously learn joint detector and dense regressor. Extensive experiments on benchmarks MPII Human Pose Multi-Person, extended PASCAL-Person-Part, and WAF, show the efficiency of GPN with new state-of-the-art performance.

##### Abstract (translated by Google)
本文提出了一种新的生成分区网络（GPN）来解决具有挑战性的多人姿态估计问题。与现有的完全自上而下或自下而上的模型不同，提议的GPN引入了一种新的策略 - 它从全局联合候选者中为多个人生成分区，并同时推断出特定于实例的联合配置。 GPN具有低复杂度和高联合检测和重组准确性的优势。具体来说，GPN设计一个生成模型，执行一个前馈通道，以有效地生成具有联合分区的鲁棒人员检测，依赖于由人员质心参数化的嵌入空间中全局联合候选人的密集回归。另外，GPN将人体姿态联合配置的推理过程作为图分区问题进行制定，并对可靠的全局亲和性线索进行每个人的检测进行局部优化，从而降低复杂度，提高性能。 GPN以沙漏体系结构作为骨干网络同时学习联合检测器和密集回归器。基准测试MPII Human Pose Multi-Person，扩展的PASCAL-Person-Part和WAF的广泛实验以最新的最新性能展现了GPN的效率。

##### URL
[https://arxiv.org/abs/1705.07422](https://arxiv.org/abs/1705.07422)

##### PDF
[https://arxiv.org/pdf/1705.07422](https://arxiv.org/pdf/1705.07422)

