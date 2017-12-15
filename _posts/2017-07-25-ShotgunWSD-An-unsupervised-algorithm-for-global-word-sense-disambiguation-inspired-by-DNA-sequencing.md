---
layout: post
title: "ShotgunWSD: An unsupervised algorithm for global word sense disambiguation inspired by DNA sequencing"
date: 2017-07-25 16:56:53
categories: arXiv_CL
tags: arXiv_CL
author: Andrei M. Butnaru, Radu Tudor Ionescu, Florentina Hristea
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel unsupervised algorithm for word sense disambiguation (WSD) at the document level. Our algorithm is inspired by a widely-used approach in the field of genetics for whole genome sequencing, known as the Shotgun sequencing technique. The proposed WSD algorithm is based on three main steps. First, a brute-force WSD algorithm is applied to short context windows (up to 10 words) selected from the document in order to generate a short list of likely sense configurations for each window. In the second step, these local sense configurations are assembled into longer composite configurations based on suffix and prefix matching. The resulted configurations are ranked by their length, and the sense of each word is chosen based on a voting scheme that considers only the top k configurations in which the word appears. We compare our algorithm with other state-of-the-art unsupervised WSD algorithms and demonstrate better performance, sometimes by a very large margin. We also show that our algorithm can yield better performance than the Most Common Sense (MCS) baseline on one data set. Moreover, our algorithm has a very small number of parameters, is robust to parameter tuning, and, unlike other bio-inspired methods, it gives a deterministic solution (it does not involve random choices).

##### Abstract (translated by Google)
在本文中，我们提出了一种新的无监督算法在文档层面的词义消歧（WSD）。我们的算法受到全基因组测序遗传学领域中广泛使用的方法的启发，称为鸟枪测序技术。所提出的WSD算法基于三个主要步骤。首先，蛮力WSD算法被应用于从文档中选择的短的上下文窗口（最多10个字），以便为每个窗口生成可能的感知配置的短列表。在第二步中，这些本地感知配置被组合成基于后缀和前缀匹配的更长的合成配置。得到的配置按其长度排列，每个单词的意义是根据仅考虑单词出现的前k个配置的投票方案来选择的。我们将我们的算法与其他最先进的无监督WSD算法进行比较，并且表现出更好的性能，有时甚至是非常大的。我们还表明，我们的算法可以比一个数据集上的最常见检测（MCS）基线产生更好的性能。此外，我们的算法具有非常少的参数，对参数调整具有鲁棒性，并且与其他生物启发式方法不同，它提供了确定性的解决方案（它不涉及随机选择）。

##### URL
[https://arxiv.org/abs/1707.08084](https://arxiv.org/abs/1707.08084)

##### PDF
[https://arxiv.org/pdf/1707.08084](https://arxiv.org/pdf/1707.08084)

