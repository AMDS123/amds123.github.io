---
layout: post
title: "Approximated Oracle Filter Pruning for Destructive CNN Width Optimization"
date: 2019-05-12 17:14:19
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Optimization Inference
author: Xiaohan Ding, Guiguang Ding, Yuchen Guo, Jungong Han, Chenggang Yan
mathjax: true
---

* content
{:toc}

##### Abstract
It is not easy to design and run Convolutional Neural Networks (CNNs) due to: 1) finding the optimal number of filters (i.e., the width) at each layer is tricky, given an architecture; and 2) the computational intensity of CNNs impedes the deployment on computationally limited devices. Oracle Pruning is designed to remove the unimportant filters from a well-trained CNN, which estimates the filters' importance by ablating them in turn and evaluating the model, thus delivers high accuracy but suffers from intolerable time complexity, and requires a given resulting width but cannot automatically find it. To address these problems, we propose Approximated Oracle Filter Pruning (AOFP), which keeps searching for the least important filters in a binary search manner, makes pruning attempts by masking out filters randomly, accumulates the resulting errors, and finetunes the model via a multi-path framework. As AOFP enables simultaneous pruning on multiple layers, we can prune an existing very deep CNN with acceptable time cost, negligible accuracy drop, and no heuristic knowledge, or re-design a model which exerts higher accuracy and faster inference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04748](http://arxiv.org/abs/1905.04748)

##### PDF
[http://arxiv.org/pdf/1905.04748](http://arxiv.org/pdf/1905.04748)

