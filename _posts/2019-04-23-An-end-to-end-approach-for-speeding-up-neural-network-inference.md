---
layout: post
title: "An end-to-end approach for speeding up neural network inference"
date: 2019-04-23 21:44:10
categories: arXiv_CV
tags: arXiv_CV Inference Classification
author: Charles Herrmann, Richard Strong Bowen, Ramin Zabih
mathjax: true
---

* content
{:toc}

##### Abstract
Important applications such as mobile computing require reducing the computational costs of neural network inference. Ideally, applications would specify their preferred tradeoff between accuracy and speed, and the network would optimize this end-to-end, using classification error to remove parts of the network \cite{lecun1990optimal,mozer1989skeletonization,BMVC2016_104}. Increasing speed can be done either during training -- e.g., pruning filters \cite{li2016pruning} -- or during inference -- e.g., conditionally executing a subset of the layers \cite{aig}. We propose a single end-to-end framework that can improve inference efficiency in both settings. We introduce a batch activation loss and use Gumbel reparameterization to learn network structure \cite{aig,jang2016categorical}. We train end-to-end against batch activation loss combined with classification loss, and the same technique supports pruning as well as conditional computation. We obtain promising experimental results for ImageNet classification with ResNet \cite{he2016resnet} (45-52\% less computation) and MobileNetV2 \cite{sandler2018mobilenetv2} (19-37\% less computation).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04180](http://arxiv.org/abs/1812.04180)

##### PDF
[http://arxiv.org/pdf/1812.04180](http://arxiv.org/pdf/1812.04180)

