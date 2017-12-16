---
layout: post
title: "Multiple Instance Detection Network with Online Instance Classifier Refinement"
date: 2017-04-01 08:32:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Deep_Learning Detection Recognition
author: Peng Tang, Xinggang Wang, Xiang Bai, Wenyu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Of late, weakly supervised object detection is with great importance in object recognition. Based on deep learning, weakly supervised detectors have achieved many promising results. However, compared with fully supervised detection, it is more challenging to train deep network based detectors in a weakly supervised manner. Here we formulate weakly supervised detection as a Multiple Instance Learning (MIL) problem, where instance classifiers (object detectors) are put into the network as hidden nodes. We propose a novel online instance classifier refinement algorithm to integrate MIL and the instance classifier refinement procedure into a single deep network, and train the network end-to-end with only image-level supervision, i.e., without object location information. More precisely, instance labels inferred from weak supervision are propagated to their spatially overlapped instances to refine instance classifier online. The iterative instance classifier refinement procedure is implemented using multiple streams in deep network, where each stream supervises its latter stream. Weakly supervised object detection experiments are carried out on the challenging PASCAL VOC 2007 and 2012 benchmarks. We obtain 47% mAP on VOC 2007 that significantly outperforms the previous state-of-the-art.

##### Abstract (translated by Google)
最近，弱监督目标检测对于目标识别具有重要意义。基于深度学习，弱监督探测器取得了许多有希望的结果。然而，与完全监督检测相比，以弱监督方式训练基于深度网络的检测器更具挑战性。在这里，我们将弱监督检测制定为多实例学习（MIL）问题，其中实例分类器（对象检测器）作为隐藏节点被放入网络中。我们提出了一种新的在线实例分类器细化算法，将MIL和实例分类器细化过程整合到一个单独的深度网络中，并且仅通过图像级监督（即没有对象位置信息）来端对端地训练网络。更确切地说，从弱监督推断出的实例标签被传播到它们的空间重叠实例，以在线细化实例分类器。迭代实例分类器细化过程使用深度网络中的多个流来实现，其中每个流监视其后面的流。对具有挑战性的PASCAL VOC 2007和2012基准进行弱监督对象检测实验。我们在VOC 2007上获得了47％的mAP，明显优于以前的最新技术。

##### URL
[https://arxiv.org/abs/1704.00138](https://arxiv.org/abs/1704.00138)

##### PDF
[https://arxiv.org/pdf/1704.00138](https://arxiv.org/pdf/1704.00138)

