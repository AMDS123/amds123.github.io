---
layout: post
title: "Attentional Network for Visual Object Detection"
date: 2017-02-06 00:50:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Reinforcement_Learning Detection
author: Kota Hara, Ming-Yu Liu, Oncel Tuzel, Amir-massoud Farahmand
mathjax: true
---

* content
{:toc}

##### Abstract
We propose augmenting deep neural networks with an attention mechanism for the visual object detection task. As perceiving a scene, humans have the capability of multiple fixation points, each attended to scene content at different locations and scales. However, such a mechanism is missing in the current state-of-the-art visual object detection methods. Inspired by the human vision system, we propose a novel deep network architecture that imitates this attention mechanism. As detecting objects in an image, the network adaptively places a sequence of glimpses of different shapes at different locations in the image. Evidences of the presence of an object and its location are extracted from these glimpses, which are then fused for estimating the object class and bounding box coordinates. Due to lacks of ground truth annotations of the visual attention mechanism, we train our network using a reinforcement learning algorithm with policy gradients. Experiment results on standard object detection benchmarks show that the proposed network consistently outperforms the baseline networks that does not model the attention mechanism.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.01478](https://arxiv.org/abs/1702.01478)

##### PDF
[https://arxiv.org/pdf/1702.01478](https://arxiv.org/pdf/1702.01478)

