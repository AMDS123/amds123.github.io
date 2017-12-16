---
layout: post
title: "Adversarial Robustness: Softmax versus Openmax"
date: 2017-08-05 01:44:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Recognition
author: Andras Rozsa, Manuel Günther, Terrance E. Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) provide state-of-the-art results on various tasks and are widely used in real world applications. However, it was discovered that machine learning models, including the best performing DNNs, suffer from a fundamental problem: they can unexpectedly and confidently misclassify examples formed by slightly perturbing otherwise correctly recognized inputs. Various approaches have been developed for efficiently generating these so-called adversarial examples, but those mostly rely on ascending the gradient of loss. In this paper, we introduce the novel logits optimized targeting system (LOTS) to directly manipulate deep features captured at the penultimate layer. Using LOTS, we analyze and compare the adversarial robustness of DNNs using the traditional Softmax layer with Openmax, which was designed to provide open set recognition by defining classes derived from deep representations, and is claimed to be more robust to adversarial perturbations. We demonstrate that Openmax provides less vulnerable systems than Softmax to traditional attacks, however, we show that it can be equally susceptible to more sophisticated adversarial generation techniques that directly work on deep representations.

##### Abstract (translated by Google)
深度神经网络（DNN）在各种任务中提供了最新的结果，并被广泛应用于现实世界的应用中。然而，发现机器学习模型（包括性能最好的DNN）面临一个基本问题：它们可能会出乎意料地自信地错误分类由轻微扰动或其他正确识别的输入形成的示例。为了高效地产生这些所谓的对抗性例子，已经开发了各种方法，但是那些方法主要依赖于提升损失的梯度。在本文中，我们引入了新颖的logits优化瞄准系统（LOTS）来直接操作倒数第二层捕获的深度特征。使用LOTS，我们使用传统的Softmax层与Openmax来分析和比较DNN的对抗性鲁棒性，Openmax被设计为通过定义从深度表示派生的类来提供开放式集合识别，并且声称对抗对抗扰动更强健。我们证明Openmax提供比Softmax更弱的系统来传统攻击，然而，我们表明它可以同样容易受到直接在深度表示上工作的更复杂的敌对生成技术的影响。

##### URL
[https://arxiv.org/abs/1708.01697](https://arxiv.org/abs/1708.01697)

##### PDF
[https://arxiv.org/pdf/1708.01697](https://arxiv.org/pdf/1708.01697)

