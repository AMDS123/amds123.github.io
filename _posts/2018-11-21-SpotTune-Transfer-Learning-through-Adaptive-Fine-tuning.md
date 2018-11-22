---
layout: post
title: "SpotTune: Transfer Learning through Adaptive Fine-tuning"
date: 2018-11-21 14:02:03
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning
author: Yunhui Guo, Honghui Shi, Abhishek Kumar, Kristen Grauman, Tajana Rosing, Rogerio Feris
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer learning, which allows a source task to affect the inductive bias of the target task, is widely used in computer vision. The typical way of conducting transfer learning with deep neural networks is to fine-tune a model pre-trained on the source task using data from the target task. In this paper, we propose an adaptive fine-tuning approach, called SpotTune, which finds the optimal fine-tuning strategy per instance for the target data. In SpotTune, given an image from the target task, a policy network is used to make routing decisions on whether to pass the image through the fine-tuned layers or the pre-trained layers. We conduct extensive experiments to demonstrate the effectiveness of the proposed approach. Our method outperforms the traditional fine-tuning approach on 12 out of 14 standard datasets.We also compare SpotTune with other state-of-the-art fine-tuning strategies, showing superior performance. On the Visual Decathlon datasets, our method achieves the highest score across the board without bells and whistles.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08737](http://arxiv.org/abs/1811.08737)

##### PDF
[http://arxiv.org/pdf/1811.08737](http://arxiv.org/pdf/1811.08737)

