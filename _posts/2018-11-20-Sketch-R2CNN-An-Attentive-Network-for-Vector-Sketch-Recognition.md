---
layout: post
title: "Sketch-R2CNN: An Attentive Network for Vector Sketch Recognition"
date: 2018-11-20 10:44:34
categories: arXiv_CV
tags: arXiv_CV Attention RNN Classification Recognition
author: Lei Li, Changqing Zou, Youyi Zheng, Qingkun Su, Hongbo Fu, Chiew-Lan Tai
mathjax: true
---

* content
{:toc}

##### Abstract
Freehand sketching is a dynamic process where points are sequentially sampled and grouped as strokes for sketch acquisition on electronic devices. To recognize a sketched object, most existing methods discard such important temporal ordering and grouping information from human and simply rasterize sketches into binary images for classification. In this paper, we propose a novel single-branch attentive network architecture RNN-Rasterization-CNN (Sketch-R2CNN for short) to fully leverage the dynamics in sketches for recognition. Sketch-R2CNN takes as input only a vector sketch with grouped sequences of points, and uses an RNN for stroke attention estimation in the vector space and a CNN for 2D feature extraction in the pixel space respectively. To bridge the gap between these two spaces in neural networks, we propose a neural line rasterization module to convert the vector sketch along with the attention estimated by RNN into a bitmap image, which is subsequently consumed by CNN. The neural line rasterization module is designed in a differentiable way to yield a unified pipeline for end-to-end learning. We perform experiments on existing large-scale sketch recognition benchmarks and show that by exploiting the sketch dynamics with the attention mechanism, our method is more robust and achieves better performance than the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08170](http://arxiv.org/abs/1811.08170)

##### PDF
[http://arxiv.org/pdf/1811.08170](http://arxiv.org/pdf/1811.08170)

