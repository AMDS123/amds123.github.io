---
layout: post
title: "Regularizing deep networks using efficient layerwise adversarial training"
date: 2018-05-29 02:27:51
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
已经证明对抗训练能够调整深度神经网络，并增强其对抗性例子的鲁棒性。然而，其对非常深入的先进网络的影响尚未得到充分调查。在本文中，我们提出了一种有效的方法来通过干扰中间层激活来执行对抗训练并且研究在训练期间使用这种扰动作为正规化者。我们使用这些扰动来训练ResNet等非常深的模型，并显示对抗性和原始测试数据的性能都有所提高。我们的实验强调了干扰中间层激活的好处，而不是扰乱输入。 CIFAR-10和CIFAR-100数据集的结果显示了所提出的对抗训练方法的优点。 WideResNets上的其他结果表明，我们的方法在给定基础模型的分类精度方面提供了显着的改进，优于脱落和其他更大尺寸的基础模型。

##### URL
[http://arxiv.org/abs/1705.07819](http://arxiv.org/abs/1705.07819)

##### PDF
[http://arxiv.org/pdf/1705.07819](http://arxiv.org/pdf/1705.07819)

