---
layout: post
title: "A Biologically Plausible Supervised Learning Method for Spiking Neural Networks Using the Symmetric STDP Rule"
date: 2019-07-01 03:33:43
categories: arXiv_AI
tags: arXiv_AI Embedding Classification Recognition
author: Yunzhe Hao, Xuhui Huang, Meng Dong, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Spiking neural networks (SNNs) possess energy-efficient potential due to event-based computation. However, supervised training of SNNs remains a challenge as spike activities are non-differentiable. Previous SNNs training methods can be generally categorized into two basic classes, i.e., backpropagation-like training methods and plasticity-based learning methods. The former methods are dependent on energy-inefficient real-valued computation and non-local transmission, as also required in artificial neural networks (ANNs), whereas the latter are either considered to be biologically implausible or exhibit poor performance. Hence, biologically plausible (bio-plausible) high-performance supervised learning (SL) methods for SNNs remain deficient. In this paper, we proposed a novel bio-plausible SNN model for SL based on the symmetric spike-timing dependent plasticity (sym-STDP) rule found in neuroscience. By combining the sym-STDP rule with bio-plausible synaptic scaling and intrinsic plasticity of the dynamic threshold, our SNN model implemented SL well and achieved good performance in the benchmark recognition task (MNIST dataset). To reveal the underlying mechanism of our SL model, we visualized both layer-based activities and synaptic weights using the t-distributed stochastic neighbor embedding (t-SNE) method after training and found that they were well clustered, thereby demonstrating excellent classification ability. Furthermore, to verify the robustness of our model, we trained it on another more realistic dataset (Fashion-MNIST), which also showed good performance. As the learning rules were bio-plausible and based purely on local spike events, our model could be easily applied to neuromorphic hardware for online training and may be helpful for understanding SL information processing at the synaptic level in biological neural systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06574](http://arxiv.org/abs/1812.06574)

##### PDF
[http://arxiv.org/pdf/1812.06574](http://arxiv.org/pdf/1812.06574)

