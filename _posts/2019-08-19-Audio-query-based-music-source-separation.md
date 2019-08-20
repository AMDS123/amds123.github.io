---
layout: post
title: "Audio query-based music source separation"
date: 2019-08-19 04:56:56
categories: arXiv_SD
tags: arXiv_SD Deep_Learning
author: Jie Hwan Lee, Hyeong-Seok Choi, Kyogu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, music source separation has been one of the most intensively studied research areas in music information retrieval. Improvements in deep learning lead to a big progress in music source separation performance. However, most of the previous studies are restricted to separating a few limited number of sources, such as vocals, drums, bass, and other. In this study, we propose a network for audio query-based music source separation that can explicitly encode the source information from a query signal regardless of the number and/or kind of target signals. The proposed method consists of a Query-net and a Separator: given a query and a mixture, the Query-net encodes the query into the latent space, and the Separator estimates masks conditioned by the latent vector, which is then applied to the mixture for separation. The Separator can also generate masks using the latent vector from the training samples, allowing separation in the absence of a query. We evaluate our method on the MUSDB18 dataset, and experimental results show that the proposed method can separate multiple sources with a single network. In addition, through further investigation of the latent space we demonstrate that our method can generate continuous outputs via latent vector interpolation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06593](http://arxiv.org/abs/1908.06593)

##### PDF
[http://arxiv.org/pdf/1908.06593](http://arxiv.org/pdf/1908.06593)

