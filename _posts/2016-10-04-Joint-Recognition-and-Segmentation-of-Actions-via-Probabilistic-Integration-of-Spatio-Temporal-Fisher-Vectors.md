---
layout: post
title: "Joint Recognition and Segmentation of Actions via Probabilistic Integration of Spatio-Temporal Fisher Vectors"
date: 2016-10-04 07:30:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Action_Recognition Classification Recognition
author: Johanna Carvajal, Chris McCool, Brian Lovell, Conrad Sanderson
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a hierarchical approach to multi-action recognition that performs joint classification and segmentation. A given video (containing several consecutive actions) is processed via a sequence of overlapping temporal windows. Each frame in a temporal window is represented through selective low-level spatio-temporal features which efficiently capture relevant local dynamics. Features from each window are represented as a Fisher vector, which captures first and second order statistics. Instead of directly classifying each Fisher vector, it is converted into a vector of class probabilities. The final classification decision for each frame is then obtained by integrating the class probabilities at the frame level, which exploits the overlapping of the temporal windows. Experiments were performed on two datasets: s-KTH (a stitched version of the KTH dataset to simulate multi-actions), and the challenging CMU-MMAC dataset. On s-KTH, the proposed approach achieves an accuracy of 85.0%, significantly outperforming two recent approaches based on GMMs and HMMs which obtained 78.3% and 71.2%, respectively. On CMU-MMAC, the proposed approach achieves an accuracy of 40.9%, outperforming the GMM and HMM approaches which obtained 33.7% and 38.4%, respectively. Furthermore, the proposed system is on average 40 times faster than the GMM based approach.

##### Abstract (translated by Google)
我们提出了一个多层次的行动识别方法，执行联合分类和分割。一个给定的视频（包含几个连续的动作）通过一系列重叠的时间窗口进行处理。时间窗口中的每个帧都通过选择性的低层次时空特征来表示，其有效地捕捉相关的局部动态。来自每个窗口的特征被表示为Fisher向量，其捕捉一阶和二阶统计量。它不是直接对每个Fisher向量进行分类，而是转换成一个类概率向量。然后通过整合帧级别的类别概率来获得每个帧的最终分类决策，这利用了时间窗口的重叠。对两个数据集进行实验：s-KTH（KTH数据集的拼接版本以模拟多个动作）以及具有挑战性的CMU-MMAC数据集。对于s-KTH，提出的方法达到了85.0％的准确率，明显优于最近两种基于GMM和HMM的方法，分别获得了78.3％和71.2％。在CMU-MMAC中，所提出的方法达到了40.9％的准确度，优于GMM和HMM方法，分别获得了33.7％和38.4％。此外，所提出的系统平均比基于GMM的方法快40倍。

##### URL
[https://arxiv.org/abs/1602.01601](https://arxiv.org/abs/1602.01601)

##### PDF
[https://arxiv.org/pdf/1602.01601](https://arxiv.org/pdf/1602.01601)

