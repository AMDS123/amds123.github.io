---
layout: post
title: "Phrase Table as Recommendation Memory for Neural Machine Translation"
date: 2018-05-25 03:14:27
categories: arXiv_CL
tags: arXiv_CL Attention NMT Prediction Recommendation
author: Yang Zhao, Yining Wang, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) has drawn much attention due to its promising translation performance recently. However, several studies indicate that NMT often generates fluent but unfaithful translations. In this paper, we propose a method to alleviate this problem by using a phrase table as recommendation memory. The main idea is to add bonus to words worthy of recommendation, so that NMT can make correct predictions. Specifically, we first derive a prefix tree to accommodate all the candidate target phrases by searching the phrase translation table according to the source sentence. Then, we construct a recommendation word set by matching between candidate target phrases and previously translated target words by NMT. After that, we determine the specific bonus value for each recommendable word by using the attention vector and phrase translation probability. Finally, we integrate this bonus value into NMT to improve the translation results. The extensive experiments demonstrate that the proposed methods obtain remarkable improvements over the strong attentionbased NMT.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.09960](https://arxiv.org/abs/1805.09960)

##### PDF
[https://arxiv.org/pdf/1805.09960](https://arxiv.org/pdf/1805.09960)

