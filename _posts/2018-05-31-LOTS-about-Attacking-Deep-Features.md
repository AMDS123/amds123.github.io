---
layout: post
title: "LOTS about Attacking Deep Features"
date: 2018-05-31 16:12:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Recognition
author: Andras Rozsa, Manuel G&#xfc;nther, Terrance E. Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks provide state-of-the-art performance on various tasks and are, therefore, widely used in real world applications. DNNs are becoming frequently utilized in biometrics for extracting deep features, which can be used in recognition systems for enrolling and recognizing new individuals. It was revealed that deep neural networks suffer from a fundamental problem, namely, they can unexpectedly misclassify examples formed by slightly perturbing correctly recognized inputs. Various approaches have been developed for generating these so-called adversarial examples, but they aim at attacking end-to-end networks. For biometrics, it is natural to ask whether systems using deep features are immune to or, at least, more resilient to attacks than end-to-end networks. In this paper, we introduce a general technique called the layerwise origin-target synthesis (LOTS) that can be efficiently used to form adversarial examples that mimic the deep features of the target. We analyze and compare the adversarial robustness of the end-to-end VGG Face network with systems that use Euclidean or cosine distance between gallery templates and extracted deep features. We demonstrate that iterative LOTS is very effective and show that systems utilizing deep features are easier to attack than the end-to-end network.

##### Abstract (translated by Google)
深层神经网络提供了各种任务的最新性能，因此被广泛用于现实世界的应用。 DNN在生物识别中被越来越多地用于提取深度特征，其可用于识别系统用于登记和识别新个体。据揭示，深层神经网络存在一个基本问题，即它们可能会意外地错误分类由微扰正确识别的输入而形成的示例。已经开发了各种方法来生成这些所谓的对抗性例子，但它们旨在攻击端到端网络。对于生物识别技术而言，很自然地问，使用深度特征的系统是否比端对端网络免疫或至少比攻击更具弹性。在本文中，我们介绍一种称为分层原点 - 目标综合（LOTS）的通用技术，可以有效地用于形成模仿目标深层特征的敌对示例。我们分析并比较端到端VGG Face网络与使用库模板之间的欧几里得或余弦距离并提取深层特征的系统的对抗鲁棒性。我们证明迭代LOTS非常有效，并且表明使用深度特征的系统比端到端网络更容易受到攻击。

##### URL
[http://arxiv.org/abs/1611.06179](http://arxiv.org/abs/1611.06179)

##### PDF
[http://arxiv.org/pdf/1611.06179](http://arxiv.org/pdf/1611.06179)

