---
layout: post
title: "Robust and Efficient Graph Correspondence Transfer for Person Re-identification"
date: 2018-05-15 13:52:01
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Qin Zhou, Heng Fan, Hua Yang, Hang Su, Shibao Zheng, Shuang Wu, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial misalignment caused by variations in poses and viewpoints is one of the most critical issues that hinders the performance improvement in existing person re-identification (Re-ID) algorithms. To address this problem, in this paper, we present a robust and efficient graph correspondence transfer (REGCT) approach for explicit spatial alignment in Re-ID. Specifically, we propose to establish the patch-wise correspondences of positive training pairs via graph matching. By exploiting both spatial and visual contexts of human appearance in graph matching, meaningful semantic correspondences can be obtained. To circumvent the cumbersome \emph{on-line} graph matching in testing phase, we propose to transfer the \emph{off-line} learned patch-wise correspondences from the positive training pairs to test pairs. In detail, for each test pair, the training pairs with similar pose-pair configurations are selected as references. The matching patterns (i.e., the correspondences) of the selected references are then utilized to calculate the patch-wise feature distances of this test pair. To enhance the robustness of correspondence transfer, we design a novel pose context descriptor to accurately model human body configurations, and present an approach to measure the similarity between a pair of pose context descriptors. Meanwhile, to improve testing efficiency, we propose a correspondence template ensemble method using the voting mechanism, which significantly reduces the amount of patch-wise matchings involved in distance calculation. With aforementioned strategies, the REGCT model can effectively and efficiently handle the spatial misalignment problem in Re-ID. Extensive experiments on five challenging benchmarks, including VIPeR, Road, PRID450S, 3DPES and CUHK01, evidence the superior performance of REGCT over other state-of-the-art approaches.

##### Abstract (translated by Google)
由姿态和视点变化引起的空间不对齐是阻碍现有人员重新识别（Re-ID）算法中的性能改进的最重要问题之一。为了解决这个问题，在本文中，我们提出了一个强大而高效的图形对应传输（REGCT）方法，用于在Re-ID中显式空间对齐。具体而言，我们建议通过图匹配来建立正面训练对的面片对应的对应关系。通过在图匹配中利用人类外貌的空间和视觉上下文，可以获得有意义的语义对应。为了避免测试阶段繁琐的\ emph {on-line}图匹配，我们建议将正面训练对中的\ emph {off-line}已学习的面向对象的对应关系转换为测试对。具体而言，对于每个测试对，具有相似姿势对配置的训练对被选作参考。然后利用所选参考的匹配图案（即对应关系）来计算该测试对的面片特征距离。为了提高函数传递的鲁棒性，我们设计了一种新颖的姿态上下文描述符来精确模拟人体配置，并提出了一种测量一对姿势上下文描述符之间相似性的方法。同时，为提高测试效率，我们提出了一种使用投票机制的对应模板集成方法，该方法大大减少了距离计算中涉及的patch-wise匹配量。通过上述策略，REGCT模型可以有效地处理Re-ID中的空间不对齐问题。在包括VIPeR，Road，PRID450S，3DPES和CUHK01在内的五个具有挑战性的基准上进行的大量实验证明了REGCT与其他最先进方法的优越性能。

##### URL
[http://arxiv.org/abs/1805.06323](http://arxiv.org/abs/1805.06323)

##### PDF
[http://arxiv.org/pdf/1805.06323](http://arxiv.org/pdf/1805.06323)

