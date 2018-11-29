---
layout: post
title: "A Deep Cascade Model for Multi-Document Reading Comprehension"
date: 2018-11-28 03:48:34
categories: arXiv_CL
tags: arXiv_CL QA Tracking
author: Ming Yan, Jiangnan Xia, Chen Wu, Bin Bi, Zhongzhou Zhao, Ji Zhang, Luo Si, Rui Wang, Wei Wang, Haiqing Chen
mathjax: true
---

* content
{:toc}

##### Abstract
A fundamental trade-off between effectiveness and efficiency needs to be balanced when designing an online question answering system. Effectiveness comes from sophisticated functions such as extractive machine reading comprehension (MRC), while efficiency is obtained from improvements in preliminary retrieval components such as candidate document selection and paragraph ranking. Given the complexity of the real-world multi-document MRC scenario, it is difficult to jointly optimize both in an end-to-end system. To address this problem, we develop a novel deep cascade learning model, which progressively evolves from the document-level and paragraph-level ranking of candidate texts to more precise answer extraction with machine reading comprehension. Specifically, irrelevant documents and paragraphs are first filtered out with simple functions for efficiency consideration. Then we jointly train three modules on the remaining texts for better tracking the answer: the document extraction, the paragraph extraction and the answer extraction. Experiment results show that the proposed method outperforms the previous state-of-the-art methods on two large-scale multi-document benchmark datasets, i.e., TriviaQA and DuReader. In addition, our online system can stably serve typical scenarios with millions of daily requests in less than 50ms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11374](http://arxiv.org/abs/1811.11374)

##### PDF
[http://arxiv.org/pdf/1811.11374](http://arxiv.org/pdf/1811.11374)

