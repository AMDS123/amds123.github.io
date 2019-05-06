---
layout: post
title: "Peacock: Learning Long-Tail Topic Features for Industrial Applications"
date: 2014-12-06 09:54:43
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Yi Wang, Xuemin Zhao, Zhenlong Sun, Hao Yan, Lifeng Wang, Zhihui Jin, Liubin Wang, Yang Gao, Ching Law, Jia Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Latent Dirichlet allocation (LDA) is a popular topic modeling technique in academia but less so in industry, especially in large-scale applications involving search engine and online advertising systems. A main underlying reason is that the topic models used have been too small in scale to be useful; for example, some of the largest LDA models reported in literature have up to $10^3$ topics, which cover difficultly the long-tail semantic word sets. In this paper, we show that the number of topics is a key factor that can significantly boost the utility of topic-modeling systems. In particular, we show that a "big" LDA model with at least $10^5$ topics inferred from $10^9$ search queries can achieve a significant improvement on industrial search engine and online advertising systems, both of which serving hundreds of millions of users. We develop a novel distributed system called Peacock to learn big LDA models from big data. The main features of Peacock include hierarchical distributed architecture, real-time prediction and topic de-duplication. We empirically demonstrate that the Peacock system is capable of providing significant benefits via highly scalable LDA topic models for several industrial applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1405.4402](https://arxiv.org/abs/1405.4402)

##### PDF
[https://arxiv.org/pdf/1405.4402](https://arxiv.org/pdf/1405.4402)

