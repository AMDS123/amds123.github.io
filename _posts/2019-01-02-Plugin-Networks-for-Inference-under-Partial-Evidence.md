---
layout: post
title: "Plugin Networks for Inference under Partial Evidence"
date: 2019-01-02 11:30:19
categories: arXiv_CV
tags: arXiv_CV CNN Inference Relation
author: Michal Koperski, Tomasz Konopczynski, Piotr Semberecki, Tomasz Trzcinski
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel method to incorporate partial evidence in the inference of deep convolutional neural networks. Contrary to the existing methods, which either iteratively modify the input of the network or exploit external label taxonomy to take partial evidence into account, we add separate network modules to the intermediate layers of a pre-trained convolutional network. The goal of those modules is to incorporate additional signal - information about known labels - into the inference procedure and adjust the predicted outputs accordingly. Since the attached "Plugin Networks", have a simple structure consisting of only fully connected layers, we drastically reduce the computational cost of training and inference. At the same time, the proposed architecture allows to propagate the information about known labels directly to the intermediate layers that are trained to intrinsically model correlations between the labels. Extensive evaluation of the proposed method confirms that our Plugin Networks outperform the state-of-the-art in a variety of tasks, including scene categorization and multi-label image annotation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.00326](https://arxiv.org/abs/1901.00326)

##### PDF
[https://arxiv.org/pdf/1901.00326](https://arxiv.org/pdf/1901.00326)

