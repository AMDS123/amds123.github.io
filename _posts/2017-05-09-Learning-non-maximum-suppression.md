---
layout: post
title: "Learning non-maximum suppression"
date: 2017-05-09 12:52:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jan Hosang, Rodrigo Benenson, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors have hugely profited from moving towards an end-to-end learning paradigm: proposals, features, and the classifier becoming one neural network improved results two-fold on general object detection. One indispensable component is non-maximum suppression (NMS), a post-processing algorithm responsible for merging all detections that belong to the same object. The de facto standard NMS algorithm is still fully hand-crafted, suspiciously simple, and -- being based on greedy clustering with a fixed distance threshold -- forces a trade-off between recall and precision. We propose a new network architecture designed to perform NMS, using only boxes and their score. We report experiments for person detection on PETS and for general object categories on the COCO dataset. Our approach shows promise providing improved localization and occlusion handling.

##### Abstract (translated by Google)
对象检测器从迈向端到端的学习范式中获益匪浅：提议，特征以及成为一个神经网络的分类器的改进对于一般对象检测来说是双重的结果。一个不可缺少的组件是非最大抑制（NMS），后处理算法负责合并属于同一对象的所有检测。事实上标准的NMS算法仍然是完全手工制作的，可疑的简单，并且基于具有固定距离阈值的贪婪聚类 - 强制在召回和精度之间进行权衡。我们提出了一个新的网络体系结构，旨在执行NMS，只使用框和他们的分数。我们报告PETS上的人体检测实验和COCO数据集上的一般对象类别实验。我们的方法显示了承诺提供改进的本地化和遮挡处理。

##### URL
[https://arxiv.org/abs/1705.02950](https://arxiv.org/abs/1705.02950)

##### PDF
[https://arxiv.org/pdf/1705.02950](https://arxiv.org/pdf/1705.02950)

