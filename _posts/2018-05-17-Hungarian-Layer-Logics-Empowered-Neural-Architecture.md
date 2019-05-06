---
layout: post
title: "Hungarian Layer: Logics Empowered Neural Architecture"
date: 2018-05-17 07:56:28
categories: arXiv_CV
tags: arXiv_CV RNN
author: Han Xiao, Yidong Chen, Xiaodong Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture is a purely numeric framework, which fits the data as a continuous function. However, lacking of logic flow (e.g. \textit{if, for, while}), traditional algorithms (e.g. \textit{Hungarian algorithm, A$^*$ searching, decision tress algorithm}) could not be embedded into this paradigm, which limits the theories and applications. In this paper, we reform the calculus graph as a dynamic process, which is guided by logic flow. Within our novel methodology, traditional algorithms could empower numerical neural network. Specifically, regarding the subject of sentence matching, we reformulate this issue as the form of task-assignment, which is solved by Hungarian algorithm. First, our model applies BiLSTM to parse the sentences. Then Hungarian layer aligns the matching positions. Last, we transform the matching results for soft-max regression by another BiLSTM. Extensive experiments show that our model outperforms other state-of-the-art baselines substantially.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.02555](https://arxiv.org/abs/1712.02555)

##### PDF
[https://arxiv.org/pdf/1712.02555](https://arxiv.org/pdf/1712.02555)

