---
layout: post
title: "Oracle-free Detection of Translation Issue for Neural Machine Translation"
date: 2018-07-06 10:17:44
categories: arXiv_AI
tags: arXiv_AI Face NMT Detection
author: Wujie Zheng, Wenyu Wang, Dian Liu, Changrong Zhang, Qinsong Zeng, Yuetang Deng, Wei Yang, Tao Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) has been widely adopted over recent years due to its advantages on various translation tasks. However, NMT systems can be error-prone due to the intractability of natural languages and the design of neural networks, bringing issues to their translations. These issues could potentially lead to information loss, wrong semantics, and low readability in translations, compromising the usefulness of NMT and leading to potential non-trivial consequences. Although there are existing approaches, such as using the BLEU score, on quality assessment and issue detection for NMT, such approaches face two serious limitations. First, such solutions require oracle translations, i.e., reference translations, which are often unavailable, e.g., in production environments. Second, such approaches cannot pinpoint the issue types and locations within translations. To address such limitations, we propose a new approach aiming to precisely detect issues in translations without requiring oracle translations. Our approach focuses on two most prominent issues in NMT translations by including two detection algorithms. Our experimental results show that our new approach could achieve high effectiveness on real-world datasets. Our successful experience on deploying the proposed algorithms in both the development and production environments of WeChat, a messenger app with over one billion of monthly active users, helps eliminate numerous defects of our NMT model, monitor the effectiveness on real-world translation tasks, and collect in-house test cases, producing high industry impact.

##### Abstract (translated by Google)
神经机器翻译（NMT）近年来因其在各种翻译任务中的优势而被广泛采用。然而，由于自然语言的难以处理和神经网络的设计，NMT系统可能容易出错，从而给翻译带来问题。这些问题可能导致信息丢失，语义错误，翻译可读性低，损害NMT的有用性并导致潜在的重大后果。尽管存在诸如使用BLEU评分的现有方法，用于NMT的质量评估和问题检测，但是这些方法面临两个严重的限制。首先，这样的解决方案需要oracle翻译，即参考翻译，其通常在例如生产环境中不可用。其次，这些方法无法确定翻译中的问题类型和位置。为了解决这些限制，我们提出了一种新方法，旨在精确检测翻译中的问题，而无需oracle翻译。我们的方法通过包括两种检测算法来关注NMT翻译中的两个最突出的问题。我们的实验结果表明，我们的新方法可以在真实世界的数据集上实现高效。我们在微信的开发和生产环境中部署所提算法的成功经验，微信是一个拥有超过10亿月活跃用户的信使应用程序，有助于消除我们NMT模型的众多缺陷，监控实际翻译任务的有效性，以及收集内部测试用例，产生高度的行业影响。

##### URL
[http://arxiv.org/abs/1807.02340](http://arxiv.org/abs/1807.02340)

##### PDF
[http://arxiv.org/pdf/1807.02340](http://arxiv.org/pdf/1807.02340)

