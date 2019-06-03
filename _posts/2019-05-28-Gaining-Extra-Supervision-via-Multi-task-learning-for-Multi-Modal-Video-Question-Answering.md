---
layout: post
title: "Gaining Extra Supervision via Multi-task learning for Multi-Modal Video Question Answering"
date: 2019-05-28 01:46:20
categories: arXiv_CV
tags: arXiv_CV QA Multi_Task VQA
author: Junyeong Kim, Minuk Ma, Kyungsu Kim, Sungjin Kim, Chang D. Yoo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method to gain extra supervision via multi-task learning for multi-modal video question answering. Multi-modal video question answering is an important task that aims at the joint understanding of vision and language. However, establishing large scale dataset for multi-modal video question answering is expensive and the existing benchmarks are relatively small to provide sufficient supervision. To overcome this challenge, this paper proposes a multi-task learning method which is composed of three main components: (1) multi-modal video question answering network that answers the question based on the both video and subtitle feature, (2) temporal retrieval network that predicts the time in the video clip where the question was generated from and (3) modality alignment network that solves metric learning problem to find correct association of video and subtitle modalities. By simultaneously solving related auxiliary tasks with hierarchically shared intermediate layers, the extra synergistic supervisions are provided. Motivated by curriculum learning, multi task ratio scheduling is proposed to learn easier task earlier to set inductive bias at the beginning of the training. The experiments on publicly available dataset TVQA shows state-of-the-art results, and ablation studies are conducted to prove the statistical validity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13540](http://arxiv.org/abs/1905.13540)

##### PDF
[http://arxiv.org/pdf/1905.13540](http://arxiv.org/pdf/1905.13540)

