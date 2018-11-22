---
layout: post
title: "Dynamic-Net: Tuning the Objective Without Re-training"
date: 2018-11-21 14:49:34
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Alon Shoshan, Roey Mechrez, Lihi Zelnik-Manor
mathjax: true
---

* content
{:toc}

##### Abstract
One of the key ingredients for successful optimization of modern CNNs is identifying a suitable objective. To date, the objective is fixed a-priori at training time, and any variation to it requires re-training a new network. In this paper we present a first attempt at alleviating the need for re-training. Rather than fixing the network at training time, we train a "Dynamic-Net" that can be modified at inference time. Our approach considers an "objective-space" as the space of all linear combinations of two objectives, and the Dynamic-Net can traverse this objective-space at test-time, without any further training. We show that this upgrades pre-trained networks by providing an out-of-learning extension, while maintaining the performance quality. The solution we propose is fast and allows a user to interactively modify the network, in real-time, in order to obtain the result he/she desires. We show the benefits of such an approach via several different applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08760](http://arxiv.org/abs/1811.08760)

##### PDF
[http://arxiv.org/pdf/1811.08760](http://arxiv.org/pdf/1811.08760)

