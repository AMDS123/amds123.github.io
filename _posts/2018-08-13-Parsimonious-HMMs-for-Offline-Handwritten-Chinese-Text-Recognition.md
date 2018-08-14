---
layout: post
title: "Parsimonious HMMs for Offline Handwritten Chinese Text Recognition"
date: 2018-08-13 10:26:56
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Wenchao Wang, Jun Du, Zi-Rui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, hidden Markov models (HMMs) have achieved promising results for offline handwritten Chinese text recognition. However, due to the large vocabulary of Chinese characters with each modeled by a uniform and fixed number of hidden states, a high demand of memory and computation is required. In this study, to address this issue, we present parsimonious HMMs via the state tying which can fully utilize the similarities among different Chinese characters. Two-step algorithm with the data-driven question-set is adopted to generate the tied-state pool using the likelihood measure. The proposed parsimonious HMMs with both Gaussian mixture models (GMMs) and deep neural networks (DNNs) as the emission distributions not only lead to a compact model but also improve the recognition accuracy via the data sharing for the tied states and the confusion decreasing among state classes. Tested on ICDAR-2013 competition database, in the best configured case, the new parsimonious DNN-HMM can yield a relative character error rate (CER) reduction of 6.2%, 25% reduction of model size and 60% reduction of decoding time over the conventional DNN-HMM. In the compact setting case of average 1-state HMM, our parsimonious DNN-HMM significantly outperforms the conventional DNN-HMM with a relative CER reduction of 35.5%.

##### Abstract (translated by Google)
最近，隐马尔可夫模型（HMM）已经取得了有希望的离线手写中文文本识别结果。然而，由于汉字的大词汇量每个都由统一和固定数量的隐藏状态建模，因此需要大量的存储器和计算。在这项研究中，为了解决这个问题，我们通过状态绑定呈现简约的HMM，它可以充分利用不同汉字之间的相似性。采用具有数据驱动问题集的两步算法，使用似然度量生成绑定状态池。所提出的具有高斯混合模型（GMM）和深度神经网络（DNN）作为发射分布的简约HMM不仅导致紧凑模型，而且通过数据共享为绑定状态和状态之间的混乱减少提高识别准确度。类。在ICDAR-2013竞争数据库上进行测试，在配置最佳的情况下，新的简约DNN-HMM可以使相对字符错误率（CER）降低6.2％，模型大小减少25％，解码时间减少60％。传统的DNN-HMM。在平均1态HMM的紧凑设置情况下，我们的简约DNN-HMM明显优于传统的DNN-HMM，相对CER减少35.5％。

##### URL
[http://arxiv.org/abs/1808.04138](http://arxiv.org/abs/1808.04138)

##### PDF
[http://arxiv.org/pdf/1808.04138](http://arxiv.org/pdf/1808.04138)

