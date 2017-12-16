---
layout: post
title: "Regularizing deep networks using efficient layerwise adversarial training"
date: 2017-05-22 15:55:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Swami Sankaranarayanan, Arpit Jain, Rama Chellappa, Ser Nam Lim
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial training has been shown to regularize deep neural networks in addition to increasing their robustness to adversarial examples. However, its impact on very deep state of the art networks has not been fully investigated. In this paper, we present an efficient approach to perform adversarial training by perturbing intermediate layer activations and study the use of such perturbations as a regularizer during training. We use these perturbations to train very deep models such as ResNets and show improvement in performance both on adversarial and original test data. Our experiments highlight the benefits of perturbing intermediate layer activations compared to perturbing only the inputs. The results on CIFAR-10 and CIFAR-100 datasets show the merits of the proposed adversarial training approach. Additional results on WideResNets show that our approach provides significant improvement in classification accuracy for a given base model, outperforming dropout and other base models of larger size.

##### Abstract (translated by Google)
已经显示对抗训练能够调节深度神经网络，同时增加对抗性的例子的鲁棒性。然而，它对深度现状网络的影响还没有得到充分的调查。在本文中，我们提出了一个有效的方法来进行扰动中间层激活进行对抗训练，并研究在训练过程中使用这样的扰动作为正规化者。我们使用这些扰动来训练ResNet等非常深的模型，并在对抗性和原始测试数据上显示性能的改善。我们的实验突出了干扰中间层激活的好处，而不是扰乱输入。 CIFAR-10和CIFAR-100数据集的结果显示了提出的对抗性训练方法的优点。 WideResNets上的其他结果表明，我们的方法在给定基础模型的分类准确性方面提供了显着的改进，优于脱落和其他更大尺寸的基础模型。

##### URL
[https://arxiv.org/abs/1705.07819](https://arxiv.org/abs/1705.07819)

##### PDF
[https://arxiv.org/pdf/1705.07819](https://arxiv.org/pdf/1705.07819)

