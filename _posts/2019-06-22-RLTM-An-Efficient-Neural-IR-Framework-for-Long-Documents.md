---
layout: post
title: "RLTM: An Efficient Neural IR Framework for Long Documents"
date: 2019-06-22 07:32:15
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Chen Zheng, Yu Sun, Shengxian Wan, Dianhai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved significant improvements in information retrieval (IR). However, most existing models are computational costly and can not efficiently scale to long documents. This paper proposes a novel End-to-End neural ranking framework called Reinforced Long Text Matching (RLTM) which matches a query with long documents efficiently and effectively. The core idea behind the framework can be analogous to the human judgment process which firstly locates the relevance parts quickly from the whole document and then matches these parts with the query carefully to obtain the final label. Firstly, we select relevant sentences from the long documents by a coarse and efficient matching model. Secondly, we generate a relevance score by a more sophisticated matching model based on the sentence selected. The whole model is trained jointly with reinforcement learning in a pairwise manner by maximizing the expected score gaps between positive and negative examples. Experimental results demonstrate that RLTM has greatly improved the efficiency and effectiveness of the state-of-the-art models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09404](http://arxiv.org/abs/1906.09404)

##### PDF
[http://arxiv.org/pdf/1906.09404](http://arxiv.org/pdf/1906.09404)

