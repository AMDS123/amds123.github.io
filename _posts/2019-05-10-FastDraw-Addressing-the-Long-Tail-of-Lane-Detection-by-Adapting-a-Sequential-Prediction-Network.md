---
layout: post
title: "FastDraw: Addressing the Long Tail of Lane Detection by Adapting a Sequential Prediction Network"
date: 2019-05-10 19:39:32
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Inference RNN Prediction Quantitative Detection
author: Jonah Philion
mathjax: true
---

* content
{:toc}

##### Abstract
The search for predictive models that generalize to the long tail of sensor inputs is the central difficulty when developing data-driven models for autonomous vehicles. In this paper, we use lane detection to study modeling and training techniques that yield better performance on real world test drives. On the modeling side, we introduce a novel fully convolutional model of lane detection that learns to decode lane structures instead of delegating structure inference to post-processing. In contrast to previous works, our convolutional decoder is able to represent an arbitrary number of lanes per image, preserves the polyline representation of lanes without reducing lanes to polynomials, and draws lanes iteratively without requiring the computational and temporal complexity of recurrent neural networks. Because our model includes an estimate of the joint distribution of neighboring pixels belonging to the same lane, our formulation includes a natural and computationally cheap definition of uncertainty. On the training side, we demonstrate a simple yet effective approach to adapt the model to new environments using unsupervised style transfer. By training FastDraw to make predictions of lane structure that are invariant to low-level stylistic differences between images, we achieve strong performance at test time in weather and lighting conditions that deviate substantially from those of the annotated datasets that are publicly available. We quantitatively evaluate our approach on the CVPR 2017 Tusimple lane marking challenge, difficult CULane datasets, and a small labeled dataset of our own and achieve competitive accuracy while running at 90 FPS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04354](http://arxiv.org/abs/1905.04354)

##### PDF
[http://arxiv.org/pdf/1905.04354](http://arxiv.org/pdf/1905.04354)

