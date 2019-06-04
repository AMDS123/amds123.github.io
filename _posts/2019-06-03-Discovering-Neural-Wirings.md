---
layout: post
title: "Discovering Neural Wirings"
date: 2019-06-03 05:58:33
categories: arXiv_CV
tags: arXiv_CV NAS
author: Mitchell Wortsman, Ali Farhadi, Mohammad Rastegari
mathjax: true
---

* content
{:toc}

##### Abstract
The success of neural networks has driven a shift in focus from feature engineering to architecture engineering. However, successful networks today are constructed using a small and manually defined set of building blocks. Even in methods of neural architecture search (NAS) the network connectivity patterns are largely constrained. In this work we propose a method for discovering neural wirings. We relax the typical notion of layers and instead enable channels to form connections independent of each other. This allows for a much larger space of possible networks. The wiring of our network is not fixed during training -- as we learn the network parameters we also learn the structure itself. Our experiments demonstrate that our learned connectivity outperforms hand engineered and randomly wired networks. By learning the connectivity of MobileNetV1 [9] we boost the ImageNet accuracy by 10% at ~41M FLOPs. Moreover, we show that our method generalizes to recurrent and continuous time networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00586](http://arxiv.org/abs/1906.00586)

##### PDF
[http://arxiv.org/pdf/1906.00586](http://arxiv.org/pdf/1906.00586)

