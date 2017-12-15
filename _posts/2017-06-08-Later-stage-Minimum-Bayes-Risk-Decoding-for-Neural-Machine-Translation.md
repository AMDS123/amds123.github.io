---
layout: post
title: "Later-stage Minimum Bayes-Risk Decoding for Neural Machine Translation"
date: 2017-06-08 08:02:00
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Raphael Shu, Hideki Nakayama
mathjax: true
---

* content
{:toc}

##### Abstract
For extended periods of time, sequence generation models rely on beam search algorithm to generate output sequence. However, the correctness of beam search degrades when the a model is over-confident about a suboptimal prediction. In this paper, we propose to perform minimum Bayes-risk (MBR) decoding for some extra steps at a later stage. In order to speed up MBR decoding, we compute the Bayes risks on GPU in batch mode. In our experiments, we found that MBR reranking works with a large beam size. Later-stage MBR decoding is shown to outperform simple MBR reranking in machine translation tasks.

##### Abstract (translated by Google)
长时间的序列生成模型依赖于波束搜索算法来生成输出序列。然而，当a模型对次优预测过于自信时，波束搜索的正确性降低。在本文中，我们建议在稍后的阶段为一些额外的步骤执行最小贝叶斯风险（MBR）解码。为了加速MBR解码，我们在批处理模式下计算GPU上的贝叶斯风险。在我们的实验中，我们发现MBR的排序工作与一个大光束大小。在机器翻译任务中，后期MBR解码显示优于简单的MBR重新排序。

##### URL
[https://arxiv.org/abs/1704.03169](https://arxiv.org/abs/1704.03169)

##### PDF
[https://arxiv.org/pdf/1704.03169](https://arxiv.org/pdf/1704.03169)

