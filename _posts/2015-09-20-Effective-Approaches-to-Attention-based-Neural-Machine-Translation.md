---
layout: post
title: "Effective Approaches to Attention-based Neural Machine Translation"
date: 2015-09-20 08:25:52
categories: arXiv_CL
tags: arXiv_CL NMT
author: Minh-Thang Luong, Hieu Pham, Christopher D. Manning
mathjax: true
---

* content
{:toc}

##### Abstract
An attentional mechanism has lately been used to improve neural machine translation (NMT) by selectively focusing on parts of the source sentence during translation. However, there has been little work exploring useful architectures for attention-based NMT. This paper examines two simple and effective classes of attentional mechanism: a global approach which always attends to all source words and a local one that only looks at a subset of source words at a time. We demonstrate the effectiveness of both approaches over the WMT translation tasks between English and German in both directions. With local attention, we achieve a significant gain of 5.0 BLEU points over non-attentional systems which already incorporate known techniques such as dropout. Our ensemble model using different attention architectures has established a new state-of-the-art result in the WMT'15 English to German translation task with 25.9 BLEU points, an improvement of 1.0 BLEU points over the existing best system backed by NMT and an n-gram reranker.

##### Abstract (translated by Google)
注意机制近来被用来改善神经机器翻译（NMT），通过在翻译过程中选择性地关注部分源句子。然而，基于注意力的NMT探索有用的体系结构却很少有工作。本文考察了两个简单而有效的注意机制类别：一个始终注意所有源词的全局方法，一个只注视一个源词的子集的本地方法。我们在两个方向上展示了两种方法在WMT翻译任务中的效果。在当地关注的情况下，我们比已经包含已知技术（如退出）的非注意系统显着增加5.0 BLEU点。我们使用不同关注架构的集成模式已经在WMT'15英语到德语翻译任务中建立了新的最新结果，其中25.9个BLEU点，比现有的由NMT支持的最佳系统提高1.0 BLEU点， n-gram reranker。

##### URL
[https://arxiv.org/abs/1508.04025](https://arxiv.org/abs/1508.04025)

##### PDF
[https://arxiv.org/pdf/1508.04025](https://arxiv.org/pdf/1508.04025)

