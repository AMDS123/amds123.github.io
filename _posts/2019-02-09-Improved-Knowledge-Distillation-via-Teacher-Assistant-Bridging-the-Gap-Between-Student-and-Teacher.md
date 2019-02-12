---
layout: post
title: "Improved Knowledge Distillation via Teacher Assistant: Bridging the Gap Between Student and Teacher"
date: 2019-02-09 09:06:01
categories: arXiv_AI
tags: arXiv_AI Knowledge GAN
author: Seyed-Iman Mirzadeh, Mehrdad Farajtabar, Ang Li, Hassan Ghasemzadeh
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the fact that deep neural networks are powerful models and achieve appealing results on many tasks, they are too gigantic to be deployed on edge devices like smart-phones or embedded sensor nodes. There has been efforts to compress these networks, and a popular method is knowledge distillation, where a large (a.k.a. teacher) pre-trained network is used to train a smaller (a.k.a. student) network. However, in this paper, we show that the student network performance degrades when the gap between student and teacher is large. Given a fixed student network, one cannot employ an arbitrarily large teacher, or in other words, a teacher can effectively transfer its knowledge to students up to a certain size, not smaller. To alleviate this shortcoming, we introduce multi-step knowledge distillation which employs an intermediate-sized network (a.k.a. teacher assistant) to bridge the gap between the student and the teacher. We study the effect of teacher assistant size and extend the framework to multi-step distillation. Moreover, empirical and theoretical analysis are conducted to analyze the teacher assistant knowledge distillation framework. Extensive experiments on CIFAR-10 and CIFAR-100 datasets and plain CNN and ResNet architectures substantiate the effectiveness of our proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03393](http://arxiv.org/abs/1902.03393)

##### PDF
[http://arxiv.org/pdf/1902.03393](http://arxiv.org/pdf/1902.03393)

