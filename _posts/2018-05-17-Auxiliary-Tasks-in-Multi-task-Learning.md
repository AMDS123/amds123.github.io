---
layout: post
title: "Auxiliary Tasks in Multi-task Learning"
date: 2018-05-17 16:12:16
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Semantic_Segmentation NMT
author: Lukas Liebel, Marco K&#xf6;rner
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task convolutional neural networks (CNNs) have shown impressive results for certain combinations of tasks, such as single-image depth estimation (SIDE) and semantic segmentation. This is achieved by pushing the network towards learning a robust representation that generalizes well to different atomic tasks. We extend this concept by adding auxiliary tasks, which are of minor relevance for the application, to the set of learned tasks. As a kind of additional regularization, they are expected to boost the performance of the ultimately desired main tasks. To study the proposed approach, we picked vision-based road scene understanding (RSU) as an exemplary application. Since multi-task learning requires specialized datasets, particularly when using extensive sets of tasks, we provide a multi-modal dataset for multi-task RSU, called synMT. More than 2.5 $\cdot$ 10^5 synthetic images, annotated with 21 different labels, were acquired from the video game Grand Theft Auto V (GTA V). Our proposed deep multi-task CNN architecture was trained on various combination of tasks using synMT. The experiments confirmed that auxiliary tasks can indeed boost network performance, both in terms of final results and training time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.06334](http://arxiv.org/abs/1805.06334)

##### PDF
[http://arxiv.org/pdf/1805.06334](http://arxiv.org/pdf/1805.06334)

