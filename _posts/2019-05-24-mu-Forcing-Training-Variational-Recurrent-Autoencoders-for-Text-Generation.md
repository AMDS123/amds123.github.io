---
layout: post
title: "mu-Forcing: Training Variational Recurrent Autoencoders for Text Generation"
date: 2019-05-24 07:32:37
categories: arXiv_CL
tags: arXiv_CL Text_Generation Language_Model
author: Dayiheng Liu, Xu Yang, Feng He, Yuanyuan Chen, Jiancheng Lv
mathjax: true
---

* content
{:toc}

##### Abstract
It has been previously observed that training Variational Recurrent Autoencoders (VRAE) for text generation suffers from serious uninformative latent variables problem. The model would collapse into a plain language model that totally ignore the latent variables and can only generate repeating and dull samples. In this paper, we explore the reason behind this issue and propose an effective regularizer based approach to address it. The proposed method directly injects extra constraints on the posteriors of latent variables into the learning process of VRAE, which can flexibly and stably control the trade-off between the KL term and the reconstruction term, making the model learn dense and meaningful latent representations. The experimental results show that the proposed method outperforms several strong baselines and can make the model learn interpretable latent variables and generate diverse meaningful sentences. Furthermore, the proposed method can perform well without using other strategies, such as KL annealing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10072](http://arxiv.org/abs/1905.10072)

##### PDF
[http://arxiv.org/pdf/1905.10072](http://arxiv.org/pdf/1905.10072)

