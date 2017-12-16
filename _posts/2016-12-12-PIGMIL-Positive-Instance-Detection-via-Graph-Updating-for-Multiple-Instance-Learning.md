---
layout: post
title: "PIGMIL: Positive Instance Detection via Graph Updating for Multiple Instance Learning"
date: 2016-12-12 06:12:19
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Dongkuan Xu, Jia Wu, Wei Zhang, Yingjie Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Positive instance detection, especially for these in positive bags (true positive instances, TPIs), plays a key role for multiple instance learning (MIL) arising from a specific classification problem only provided with bag (a set of instances) label information. However, most previous MIL methods on this issue ignore the global similarity among positive instances and that negative instances are non-i.i.d., usually resulting in the detection of TPI not precise and sensitive to outliers. To the end, we propose a positive instance detection via graph updating for multiple instance learning, called PIGMIL, to detect TPI accurately. PIGMIL selects instances from working sets (WSs) of some working bags (WBs) as positive candidate pool (PCP). The global similarity among positive instances and the robust discrimination of instances of PCP from negative instances are measured to construct the consistent similarity and discrimination graph (CSDG). As a result, the primary goal (i.e. TPI detection) is transformed into PCP updating, which is approximated efficiently by updating CSDG with a random walk ranking algorithm and an instance updating strategy. At last bags are transformed into feature representation vector based on the identified TPIs to train a classifier. Extensive experiments demonstrate the high precision of PIGMIL's detection of TPIs and its excellent performance compared to classic baseline MIL methods.

##### Abstract (translated by Google)
正面实例检测，特别是对于正面实例（真正实例，TPI）中的实例检测，对于仅由包（一组实例）标签信息提供的特定分类问题引起的多实例学习（MIL）起着关键作用。然而，在这个问题上大多数以前的MIL方法忽略了正面实例之间的全局相似性，负面实例是非i.i.d。，通常导致TPI的检测对于异常值不精确和敏感。最后，我们提出了一个实例检测，通过图形更新的多实例学习，称为PIGMIL，准确地检测TPI。 PIGMIL从一些工作行李（WBs）的工作集（WSs）中选择实例作为正候选集合（PCP）。测量正实例间的全局相似度和负实例对PCP实例的鲁棒性判别，构建一致的相似度和判别图（CSDG）。结果，主要目标（即TPI检测）被转换成PCP更新，通过用随机游走排名算法和实例更新策略更新CSDG来有效地近似PCP更新。最后根据识别出的TPI将袋子变换为特征表示矢量，训练出一个分类器。大量的实验表明，与传统的基线MIL方法相比，PIGMIL的TPI检测精度高，性能优异。

##### URL
[https://arxiv.org/abs/1612.03550](https://arxiv.org/abs/1612.03550)

##### PDF
[https://arxiv.org/pdf/1612.03550](https://arxiv.org/pdf/1612.03550)

