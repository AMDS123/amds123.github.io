---
layout: post
title: "Integrated Deep and Shallow Networks for Salient Object Detection"
date: 2017-06-02 00:52:55
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Jing Zhang, Bo Li, Yuchao Dai, Fatih Porikli, Mingyi He
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network (CNN) based salient object detection methods have achieved state-of-the-art performance and outperform those unsupervised methods with a wide margin. In this paper, we propose to integrate deep and unsupervised saliency for salient object detection under a unified framework. Specifically, our method takes results of unsupervised saliency (Robust Background Detection, RBD) and normalized color images as inputs, and directly learns an end-to-end mapping between inputs and the corresponding saliency maps. The color images are fed into a Fully Convolutional Neural Networks (FCNN) adapted from semantic segmentation to exploit high-level semantic cues for salient object detection. Then the results from deep FCNN and RBD are concatenated to feed into a shallow network to map the concatenated feature maps to saliency maps. Finally, to obtain a spatially consistent saliency map with sharp object boundaries, we fuse superpixel level saliency map at multi-scale. Extensive experimental results on 8 benchmark datasets demonstrate that the proposed method outperforms the state-of-the-art approaches with a margin.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.00530](https://arxiv.org/abs/1706.00530)

##### PDF
[https://arxiv.org/pdf/1706.00530](https://arxiv.org/pdf/1706.00530)

