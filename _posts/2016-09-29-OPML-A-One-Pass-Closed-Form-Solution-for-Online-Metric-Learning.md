---
layout: post
title: "OPML: A One-Pass Closed-Form Solution for Online Metric Learning"
date: 2016-09-29 02:18:06
categories: arXiv_CV
tags: arXiv_CV Face Classification Detection
author: Wenbin Li, Yang Gao, Lei Wang, Luping Zhou, Jing Huo, Yinghuan Shi
mathjax: true
---

* content
{:toc}

##### Abstract
To achieve a low computational cost when performing online metric learning for large-scale data, we present a one-pass closed-form solution namely OPML in this paper. Typically, the proposed OPML first adopts a one-pass triplet construction strategy, which aims to use only a very small number of triplets to approximate the representation ability of whole original triplets obtained by batch-manner methods. Then, OPML employs a closed-form solution to update the metric for new coming samples, which leads to a low space (i.e., $O(d)$) and time (i.e., $O(d^2)$) complexity, where $d$ is the feature dimensionality. In addition, an extension of OPML (namely COPML) is further proposed to enhance the robustness when in real case the first several samples come from the same class (i.e., cold start problem). In the experiments, we have systematically evaluated our methods (OPML and COPML) on three typical tasks, including UCI data classification, face verification, and abnormal event detection in videos, which aims to fully evaluate the proposed methods on different sample number, different feature dimensionalities and different feature extraction ways (i.e., hand-crafted and deeply-learned). The results show that OPML and COPML can obtain the promising performance with a very low computational cost. Also, the effectiveness of COPML under the cold start setting is experimentally verified.

##### Abstract (translated by Google)
为了在实现大规模数据的在线度量学习时达到较低的计算成本，本文提出了一种OPML封闭形式的解决方案。通常，所提出的OPML首先采用单程三重构建策略，其目的是仅使用非常少量的三元组来逼近通过批处理方法获得的整个原始三元组的表示能力。然后，OPML采用封闭形式的解决方案来更新即将到来的新样本的度量，从而导致低空间（即$ O（d）$）和时间（即$ O（d ^ 2）$）其中$ d $是特征维数。此外，当实际情况下，前几个样本来自同一类别（即冷启动问题）时，进一步提出了OPML（即COPML）的扩展以提高鲁棒性。在实验中，我们对视频中的UCI数据分类，人脸验证和异常事件检测三个典型任务进行了系统的评估（OPML和COPML），旨在充分评估不同样本数，不同特征维度和不同的特征提取方式（即手工制作和深度学习）。结果表明，OPML和COPML能够以非常低的计算成本获得有前途的性能。此外，COPML在冷启动设置下的有效性通过实验验证。

##### URL
[https://arxiv.org/abs/1609.09178](https://arxiv.org/abs/1609.09178)

##### PDF
[https://arxiv.org/pdf/1609.09178](https://arxiv.org/pdf/1609.09178)

