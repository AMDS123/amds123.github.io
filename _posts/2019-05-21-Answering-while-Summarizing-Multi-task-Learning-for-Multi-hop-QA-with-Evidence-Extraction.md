---
layout: post
title: "Answering while Summarizing: Multi-task Learning for Multi-hop QA with Evidence Extraction"
date: 2019-05-21 09:23:56
categories: arXiv_CL
tags: arXiv_CL QA Attention Summarization RNN
author: Kosuke Nishida, Kyosuke Nishida, Masaaki Nagata, Atsushi Otsuka, Itsumi Saito, Hisako Asano, Junji Tomita
mathjax: true
---

* content
{:toc}

##### Abstract
Question answering (QA) using textual sources such as reading comprehension (RC) has attracted much attention recently. This study focuses on the task of explainable multi-hop QA, which requires the system to return the answer with evidence sentences by reasoning and gathering disjoint pieces of the reference texts. For evidence extraction of explainable multi-hop QA, the existed method extracted evidence sentences by evaluating the importance of each sentence independently. In this study, we propose the Query Focused Extractor (QFE) model and introduce the multi-task learning of the QA model for answer selection and the QFE model for evidence extraction. QFE sequentially extracts the evidence sentences by an RNN with an attention mechanism to the question sentence, which is inspired by extractive summarization models. It enables QFE to consider the dependency among the evidence sentences and cover the important information in the question sentence. Experimental results show that QFE with the simple RC baseline model achieves a state-of-the-art evidence extraction score on HotpotQA. Although designed for RC, QFE also achieves a state-of-the-art evidence extraction score on FEVER, which is a recognizing textual entailment task on a large textual database.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08511](http://arxiv.org/abs/1905.08511)

##### PDF
[http://arxiv.org/pdf/1905.08511](http://arxiv.org/pdf/1905.08511)

