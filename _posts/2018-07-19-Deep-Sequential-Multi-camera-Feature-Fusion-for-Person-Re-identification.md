---
layout: post
title: "Deep Sequential Multi-camera Feature Fusion for Person Re-identification"
date: 2018-07-19 08:52:19
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Navaneet Murthy, Ravi Kiran Sarvadevabhatla, R. Venkatesh Babu, Anirban Chakraborty
mathjax: true
---

* content
{:toc}

##### Abstract
Given a target image as query, person re-identification systems retrieve a ranked list of candidate matches from other camera field-of-views. Re-identification is typically performed independently for each gallery camera across the network. However, images of the same target from a subset of cameras often provide complementary appearance information which, if aggregated judiciously, can lead to better re-id performance in the remaining cameras. This motivates us to investigate the novel problem of multi-camera feature fusion for person re-id. We propose an intelligent sequential fusion technique, designed to not only improve re-id accuracy but to also learn increasingly better feature representations as observations from additional cameras are fused. The fusion function is modeled using a Gated Recurrent Unit (GRU) with modification on default GRU training regime to achieve the aforementioned improvements. Extensive experimentation validates that the proposed fusion scheme substantially boosts identification performance when combined with off-the-shelf feature extraction methods for re-id.

##### Abstract (translated by Google)
给定目标图像作为查询，人员重新识别系统从其他相机视野中检索候选匹配的排序列表。通常通过网络为每个图库摄像机独立地执行重新识别。然而，来自相机子集的相同目标的图像通常提供互补的外观信息，如果明智地聚合，则可以在剩余的相机中产生更好的重新识别性能。这促使我们研究人物重新识别多相机特征融合的新问题。我们提出了一种智能序列融合技术，其设计不仅可以提高重新定位精度，还可以学习越来越好的特征表示，因为来自其他摄像机的观察融合在一起。融合功能使用门控循环单元（GRU）建模，并对默认GRU训练方案进行修改以实现上述改进。广泛的实验验证了所提出的融合方案与用于重新识别的现成特征提取方法相结合时大大提高了识别性能。

##### URL
[https://arxiv.org/abs/1807.07295](https://arxiv.org/abs/1807.07295)

##### PDF
[https://arxiv.org/pdf/1807.07295](https://arxiv.org/pdf/1807.07295)

