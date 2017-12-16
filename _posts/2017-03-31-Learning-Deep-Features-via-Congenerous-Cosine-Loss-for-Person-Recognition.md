---
layout: post
title: "Learning Deep Features via Congenerous Cosine Loss for Person Recognition"
date: 2017-03-31 17:27:50
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Yu Liu, Hongyang Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Person recognition aims at recognizing the same identity across time and space with complicated scenes and similar appearance. In this paper, we propose a novel method to address this task by training a network to obtain robust and representative features. The intuition is that we directly compare and optimize the cosine distance between two features - enlarging inter-class distinction as well as alleviating inner-class variance. We propose a congenerous cosine loss by minimizing the cosine distance between samples and their cluster centroid in a cooperative way. Such a design reduces the complexity and could be implemented via softmax with normalized inputs. Our method also differs from previous work in person recognition that we do not conduct a second training on the test subset. The identity of a person is determined by measuring the similarity from several body regions in the reference set. Experimental results show that the proposed approach achieves better classification accuracy against previous state-of-the-arts.

##### Abstract (translated by Google)
人物识别的目的在于识别跨越时间和空间的相同身份，复杂的场景和相似的外观。在本文中，我们提出了一种新的方法来解决这个任务，通过训练一个网络来获得强大和代表性的特征。直觉是我们直接比较和优化两个特征之间的余弦距离 - 扩大阶级间的区分以及缓解内部阶级的方差。我们通过合作的方式最小化样本与它们的质心之间的余弦距离来提出一个相合的余弦损失。这样的设计降低了复杂性，并且可以通过具有标准化输入的softmax来实现。我们的方法也不同于以前的人际识别工作，我们不对测试子集进行第二次训练。通过测量参考集中几个身体部位的相似性来确定一个人的身份。实验结果表明，所提出的方法实现了更好的分类准确性对先前的艺术状态。

##### URL
[https://arxiv.org/abs/1702.06890](https://arxiv.org/abs/1702.06890)

##### PDF
[https://arxiv.org/pdf/1702.06890](https://arxiv.org/pdf/1702.06890)

