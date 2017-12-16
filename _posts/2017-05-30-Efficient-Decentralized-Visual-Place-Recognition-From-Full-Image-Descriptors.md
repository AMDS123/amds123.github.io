---
layout: post
title: "Efficient Decentralized Visual Place Recognition From Full-Image Descriptors"
date: 2017-05-30 16:43:57
categories: arXiv_CV
tags: arXiv_CV Image_Caption Recognition
author: Titus Cieslewski, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we discuss the adaptation of our decentralized place recognition method described in [1] to full image descriptors. As we had shown, the key to making a scalable decentralized visual place recognition lies in exploting deterministic key assignment in a distributed key-value map. Through this, it is possible to reduce bandwidth by up to a factor of n, the robot count, by casting visual place recognition to a key-value lookup problem. In [1], we exploited this for the bag-of-words method [3], [4]. Our method of casting bag-of-words, however, results in a complex decentralized system, which has inherently worse recall than its centralized counterpart. In this paper, we instead start from the recent full-image description method NetVLAD [5]. As we show, casting this to a key-value lookup problem can be achieved with k-means clustering, and results in a much simpler system than [1]. The resulting system still has some flaws, albeit of a completely different nature: it suffers when the environment seen during deployment lies in a different distribution in feature space than the environment seen during training.

##### Abstract (translated by Google)
在本文中，我们讨论[1]中描述的分散式场所识别方法适应全图像描述符。正如我们已经表明的那样，做一个可扩展的分散式视觉地点识别的关键在于在分布式键值映射中显示确定性键分配。通过这种方式，通过将视觉位置识别转换为键值查找问题，可以将带宽降低高达n倍（机器人计数）。在文献[1]中，我们利用这个方法来进行文字袋方法[3]，[4]。然而，我们的方法是建立一个复杂的分散体系，这种分散体系本质上比中央体系的召回能力差。在本文中，我们从最近的全图描述方法NetVLAD [5]开始。正如我们所展示的，将这个转换为键值查找问题可以通过k-means聚类来实现，并且导致比[1]更简单的系统。由此产生的系统仍然有一些缺陷，虽然性质完全不同：当部署过程中看到的环境在特征空间中所处的环境与在训练过程中看到的环境不同时，会受到影响。

##### URL
[https://arxiv.org/abs/1705.10739](https://arxiv.org/abs/1705.10739)

##### PDF
[https://arxiv.org/pdf/1705.10739](https://arxiv.org/pdf/1705.10739)

