---
layout: post
title: "Deep Control - a simple automatic gain control for memory efficient and high performance training of deep convolutional neural networks"
date: 2017-06-13 05:29:05
categories: arXiv_CV
tags: arXiv_CV CNN Inference Gradient_Descent
author: Brendan Ruff
mathjax: true
---

* content
{:toc}

##### Abstract
Training a deep convolutional neural net typically starts with a random initialisation of all filters in all layers which severely reduces the forward signal and back-propagated error and leads to slow and sub-optimal training. Techniques that counter that focus on either increasing the signal or increasing the gradients adaptively but the model behaves very differently at the beginning of training compared to later when stable pathways through the net have been established. To compound this problem the effective minibatch size varies greatly between layers at different depths and between individual filters as activation sparsity typically increases with depth leading to a reduction in effective learning rate since gradients may superpose rather than add and this further compounds the covariate shift problem as deeper neurons are less able to adapt to upstream shift. Proposed here is a method of automatic gain control of the signal built into each convolutional neuron that achieves equivalent or superior performance than batch normalisation and is compatible with single sample or minibatch gradient descent. The same model is used both for training and inference. The technique comprises a scaled per sample map mean subtraction from the raw convolutional filter output followed by scaling of the difference.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.03907](https://arxiv.org/abs/1706.03907)

##### PDF
[https://arxiv.org/pdf/1706.03907](https://arxiv.org/pdf/1706.03907)

