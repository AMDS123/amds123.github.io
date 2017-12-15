---
layout: post
title: "Efficient Segmental Cascades for Speech Recognition"
date: 2016-08-02 18:45:53
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Hao Tang, Weiran Wang, Kevin Gimpel, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative segmental models offer a way to incorporate flexible feature functions into speech recognition. However, their appeal has been limited by their computational requirements, due to the large number of possible segments to consider. Multi-pass cascades of segmental models introduce features of increasing complexity in different passes, where in each pass a segmental model rescores lattices produced by a previous (simpler) segmental model. In this paper, we explore several ways of making segmental cascades efficient and practical: reducing the feature set in the first pass, frame subsampling, and various pruning approaches. In experiments on phonetic recognition, we find that with a combination of such techniques, it is possible to maintain competitive performance while greatly reducing decoding, pruning, and training time.

##### Abstract (translated by Google)
判别式分段模型提供了一种将灵活的特征函数结合到语音识别中的方法。然而，由于需要考虑大量可能的细分，所以它们的吸引力受到了计算要求的限制。分段模型的多遍级联引入了不同遍次中增加复杂性的特征，其中在每次遍历中，分段模型重新定义由先前（较简单）的分段模型产生的格子。在本文中，我们探讨了几种使分段级联高效实用的方法：减少第一遍中的特征集，帧子采样和各种修剪方法。在语音识别的实验中，我们发现，通过这些技术的组合，可以保持竞争性能，同时大大减少解码，修剪和训练时间。

##### URL
[https://arxiv.org/abs/1608.00929](https://arxiv.org/abs/1608.00929)

##### PDF
[https://arxiv.org/pdf/1608.00929](https://arxiv.org/pdf/1608.00929)

