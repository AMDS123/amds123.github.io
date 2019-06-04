---
layout: post
title: "AutoSlim: Towards One-Shot Architecture Search for Channel Numbers"
date: 2019-06-01 03:19:54
categories: arXiv_CV
tags: arXiv_CV NAS Reinforcement_Learning Classification
author: Jiahui Yu, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We study how to set channel numbers in a neural network to achieve better accuracy under constrained resources (e.g., FLOPs, latency, memory footprint or model size). A simple and one-shot solution, named AutoSlim, is presented. Instead of training many network samples and searching with reinforcement learning, we train a single slimmable network to approximate the network accuracy of different channel configurations. We then iteratively evaluate the trained slimmable model and greedily slim the layer with minimal accuracy drop. By this single pass, we can obtain the optimized channel configurations under different resource constraints. We present experiments with MobileNet v1, MobileNet v2, ResNet-50 and RL-searched MNasNet on ImageNet classification. We show significant improvements over their default channel configurations. We also achieve better accuracy than recent channel pruning methods and neural architecture search methods. Notably, by setting optimized channel numbers, our AutoSlim-MobileNet-v2 at 305M FLOPs achieves 74.2% top-1 accuracy, 2.4% better than default MobileNet-v2 (301M FLOPs), and even 0.2% better than RL-searched MNasNet (317M FLOPs). Our AutoSlim-ResNet-50 at 570M FLOPs, without depthwise convolutions, achieves 1.3% better accuracy than MobileNet-v1 (569M FLOPs). Code and models will be available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.11728](https://arxiv.org/abs/1903.11728)

##### PDF
[https://arxiv.org/pdf/1903.11728](https://arxiv.org/pdf/1903.11728)

