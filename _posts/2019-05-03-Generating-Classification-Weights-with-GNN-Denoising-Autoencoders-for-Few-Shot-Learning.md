---
layout: post
title: "Generating Classification Weights with GNN Denoising Autoencoders for Few-Shot Learning"
date: 2019-05-03 10:11:54
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Spyros Gidaris, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
Given an initial recognition model already trained on a set of base classes, the goal of this work is to develop a meta-model for few-shot learning. The meta-model, given as input some novel classes with few training examples per class, must properly adapt the existing recognition model into a new model that can correctly classify in a unified way both the novel and the base classes. To accomplish this goal it must learn to output the appropriate classification weight vectors for those two types of classes. To build our meta-model we make use of two main innovations: we propose the use of a Denoising Autoencoder network (DAE) that (during training) takes as input a set of classification weights corrupted with Gaussian noise and learns to reconstruct the target-discriminative classification weights. In this case, the injected noise on the classification weights serves the role of regularizing the weight generating meta-model. Furthermore, in order to capture the co-dependencies between different classes in a given task instance of our meta-model, we propose to implement the DAE model as a Graph Neural Network (GNN). In order to verify the efficacy of our approach, we extensively evaluate it on ImageNet based few-shot benchmarks and we report strong results that surpass prior approaches. The code and models of our paper will be published on: https://github.com/gidariss/wDAE_GNN_FewShot

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01102](http://arxiv.org/abs/1905.01102)

##### PDF
[http://arxiv.org/pdf/1905.01102](http://arxiv.org/pdf/1905.01102)

