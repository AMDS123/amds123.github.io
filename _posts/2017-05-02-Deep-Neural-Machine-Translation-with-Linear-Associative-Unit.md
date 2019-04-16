---
layout: post
title: "Deep Neural Machine Translation with Linear Associative Unit"
date: 2017-05-02 08:58:17
categories: arXiv_CL
tags: arXiv_CL Optimization NMT RNN
author: Mingxuan Wang, Zhengdong Lu, Jie Zhou, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have provably enhanced the state-of-the-art Neural Machine Translation (NMT) with their capability in modeling complex functions and capturing complex linguistic structures. However NMT systems with deep architecture in their encoder or decoder RNNs often suffer from severe gradient diffusion due to the non-linear recurrent activations, which often make the optimization much more difficult. To address this problem we propose novel linear associative units (LAU) to reduce the gradient propagation length inside the recurrent unit. Different from conventional approaches (LSTM unit and GRU), LAUs utilizes linear associative connections between input and output of the recurrent unit, which allows unimpeded information flow through both space and time direction. The model is quite simple, but it is surprisingly effective. Our empirical study on Chinese-English translation shows that our model with proper configuration can improve by 11.7 BLEU upon Groundhog and the best reported results in the same setting. On WMT14 English-German task and a larger WMT14 English-French task, our model achieves comparable results with the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.00861](https://arxiv.org/abs/1705.00861)

##### PDF
[https://arxiv.org/pdf/1705.00861](https://arxiv.org/pdf/1705.00861)

