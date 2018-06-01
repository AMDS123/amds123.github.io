---
layout: post
title: "Scaling provable adversarial defenses"
date: 2018-05-31 15:25:10
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Eric Wong, Frank Schmidt, Jan Hendrik Metzen, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has developed methods for learning deep network classifiers that are provably robust to norm-bounded adversarial perturbation; however, these methods are currently only possible for relatively small feedforward networks. In this paper, in an effort to scale these approaches to substantially larger models, we extend previous work in three main directions. First, we present a technique for extending these training procedures to much more general networks, with skip connections (such as ResNets) and general nonlinearities; the approach is fully modular, and can be implemented automatically (analogous to automatic differentiation). Second, in the specific case of $\ell_\infty$ adversarial perturbations and networks with ReLU nonlinearities, we adopt a nonlinear random projection for training, which scales linearly in the number of hidden units (previous approaches scaled quadratically). Third, we show how to further improve robust error through cascade models. On both MNIST and CIFAR data sets, we train classifiers that improve substantially on the state of the art in provable robust adversarial error bounds: from 5.8% to 3.1% on MNIST (with $\ell_\infty$ perturbations of $\epsilon=0.1$), and from 80% to 36.4% on CIFAR (with $\ell_\infty$ perturbations of $\epsilon=2/255$). Code for all experiments in the paper is available at https://github.com/locuslab/convex_adversarial/.

##### Abstract (translated by Google)
最近的工作已经开发出用于学习深度网络分类器的方法，这些分类器对于范数有界的对抗扰动是可靠的;然而，目前这些方法仅适用于相对较小的前馈网络。在本文中，为了将这些方法扩展到更大的模型，我们将以前的工作扩展到三个主要方向。首先，我们介绍一种将这些训练过程扩展到更一般网络的技术，包括跳过连接（例如ResNets）和一般非线性;该方法是完全模块化的，可以自动实现（类似于自动分化）。其次，在具有ReLU非线性的$ \ ell_ \ infty $对抗扰动和网络的特定情况下，我们采用非线性随机投影进行训练，该训练在隐藏单位数量（先前的方法按比例缩放）中线性缩放。第三，我们展示了如何通过级联模型进一步改善鲁棒误差。在MNIST和CIFAR数据集上，我们训练能够在可证明的鲁棒对抗误差范围内大幅提高现有技术水平的分类器：在MNIST上从5.8％到3.1％（$ \ ell_ \ infty $扰动$ \ epsilon = 0.1 $），从CIFAR的80％到36.4％（$ \ ell_ \ infty $扰动$ \ epsilon = 2/255 $）。 https://github.com/locuslab/convex_adversarial/上提供了论文中所有实验的代码。

##### URL
[http://arxiv.org/abs/1805.12514](http://arxiv.org/abs/1805.12514)

##### PDF
[http://arxiv.org/pdf/1805.12514](http://arxiv.org/pdf/1805.12514)

