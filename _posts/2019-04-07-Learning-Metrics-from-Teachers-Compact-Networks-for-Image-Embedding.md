---
layout: post
title: "Learning Metrics from Teachers: Compact Networks for Image Embedding"
date: 2019-04-07 11:12:07
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Attention Face Embedding Image_Classification Classification Recognition Face_Recognition
author: Lu Yu, Vacit Oguz Yazici, Xialei Liu, Joost van de Weijer, Yongmei Cheng, Arnau Ramisa
mathjax: true
---

* content
{:toc}

##### Abstract
Metric learning networks are used to compute image embeddings, which are widely used in many applications such as image retrieval and face recognition. In this paper, we propose to use network distillation to efficiently compute image embeddings with small networks. Network distillation has been successfully applied to improve image classification, but has hardly been explored for metric learning. To do so, we propose two new loss functions that model the communication of a deep teacher network to a small student network. We evaluate our system in several datasets, including CUB-200-2011, Cars-196, Stanford Online Products and show that embeddings computed using small student networks perform significantly better than those computed using standard networks of similar size. Results on a very compact network (MobileNet-0.25), which can be used on mobile devices, show that the proposed method can greatly improve Recall@1 results from 27.5\% to 44.6\%. Furthermore, we investigate various aspects of distillation for embeddings, including hint and attention layers, semi-supervised learning and cross quality distillation. (Code is available at https://github.com/yulu0724/EmbeddingDistillation.)

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03624](http://arxiv.org/abs/1904.03624)

##### PDF
[http://arxiv.org/pdf/1904.03624](http://arxiv.org/pdf/1904.03624)

