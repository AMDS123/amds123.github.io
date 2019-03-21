---
layout: post
title: "Simple, Fast, Accurate Intent Classification and Slot Labeling"
date: 2019-03-19 21:58:24
categories: arXiv_CL
tags: arXiv_CL Attention CNN Inference Classification
author: Arshit Gupta, John Hewitt, Katrin Kirchhoff
mathjax: true
---

* content
{:toc}

##### Abstract
In real-time dialogue systems running at scale, there is a tradeoff between system performance, time taken for training to converge, and time taken to perform inference. In this work, we study modeling tradeoffs intent classification (IC) and slot labeling (SL), focusing on non-recurrent models. We propose a simple, modular family of neural architectures for joint IC+SL. Using this framework, we explore a number of self-attention, convolutional, and recurrent models, contributing a large-scale analysis of modeling paradigms for IC+SL across two datasets. At the same time, we discuss a class of 'label-recurrent' models, proposing that otherwise non-recurrent models with a 10-dimensional representation of the label history provide multi-point SL improvements. As a result of our analysis, we propose a class of label-recurrent, dilated, convolutional IC+SL systems that are accurate, achieving a 30% error reduction in SL over the state-of-the-art performance on the Snips dataset, as well as fast, at 2x the inference and 2/3 to 1/2 the training time of comparable recurrent models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08268](http://arxiv.org/abs/1903.08268)

##### PDF
[http://arxiv.org/pdf/1903.08268](http://arxiv.org/pdf/1903.08268)

