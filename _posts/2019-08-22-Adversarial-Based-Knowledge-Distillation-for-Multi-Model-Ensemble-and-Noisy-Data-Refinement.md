---
layout: post
title: "Adversarial-Based Knowledge Distillation for Multi-Model Ensemble and Noisy Data Refinement"
date: 2019-08-22 17:51:16
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Recognition
author: Zhiqiang Shen, Zhankui He, Wanyun Cui, Jiahui Yu, Yutong Zheng, Chenchen Zhu, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
Generic Image recognition is a fundamental and fairly important visual problem in computer vision. One of the major challenges of this task lies in the fact that single image usually has multiple objects inside while the labels are still one-hot, another one is noisy and sometimes missing labels when annotated by humans. In this paper, we focus on tackling these challenges accompanying with two different image recognition problems: multi-model ensemble and noisy data recognition with a unified framework. As is well-known, usually the best performing deep neural models are ensembles of multiple base-level networks, as it can mitigate the variation or noise containing in the dataset. Unfortunately, the space required to store these many networks, and the time required to execute them at runtime, prohibit their use in applications where test sets are large (e.g., ImageNet). In this paper, we present a method for compressing large, complex trained ensembles into a single network, where the knowledge from a variety of trained deep neural networks (DNNs) is distilled and transferred to a single DNN. In order to distill diverse knowledge from different trained (teacher) models, we propose to use adversarial-based learning strategy where we define a block-wise training loss to guide and optimize the predefined student network to recover the knowledge in teacher models, and to promote the discriminator network to distinguish teacher vs. student features simultaneously. Extensive experiments on CIFAR-10/100, SVHN, ImageNet and iMaterialist Challenge Dataset demonstrate the effectiveness of our MEAL method. On ImageNet, our ResNet-50 based MEAL achieves top-1/5 21.79%/5.99% val error, which outperforms the original model by 2.06%/1.14%. On iMaterialist Challenge Dataset, our MEAL obtains a remarkable improvement of top-3 1.15% (official evaluation metric) on a strong baseline model of ResNet-101.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08520](https://arxiv.org/abs/1908.08520)

##### PDF
[https://arxiv.org/pdf/1908.08520](https://arxiv.org/pdf/1908.08520)

