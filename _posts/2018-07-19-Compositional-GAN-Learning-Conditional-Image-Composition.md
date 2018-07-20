---
layout: post
title: "Compositional GAN: Learning Conditional Image Composition"
date: 2018-07-19 17:57:16
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Samaneh Azadi, Deepak Pathak, Sayna Ebrahimi, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) can produce images of surprising complexity and realism, but are generally modeled to sample from a single latent source ignoring the explicit spatial interaction between multiple entities that could be present in a scene. Capturing such complex interactions between different objects in the world, including their relative scaling, spatial layout, occlusion, or viewpoint transformation is a challenging problem. In this work, we propose to model object composition in a GAN framework as a self-consistent composition-decomposition network. Our model is conditioned on the object images from their marginal distributions to generate a realistic image from their joint distribution by explicitly learning the possible interactions. We evaluate our model through qualitative experiments and user evaluations in both the scenarios when either paired or unpaired examples for the individual object images and the joint scenes are given during training. Our results reveal that the learned model captures potential interactions between the two object domains given as input to output new instances of composed scene at test time in a reasonable fashion.

##### Abstract (translated by Google)
生成性对抗网络（GAN）可以产生令人惊讶的复杂性和真实性的图像，但通常被建模为从单个潜在源采样，忽略可能存在于场景中的多个实体之间的显式空间交互。捕获世界上不同对象之间的这种复杂交互，包括它们的相对缩放，空间布局，遮挡或视点转换是一个具有挑战性的问题。在这项工作中，我们建议在GAN框架中将对象组合建模为自洽的组合分解网络。我们的模型以其边缘分布的物体图像为条件，通过明确地学习可能的相互作用，从它们的联合分布中生成逼真的图像。我们在两个场景中通过定性实验和用户评估来评估我们的模型，在训练期间给出单个对象图像和关节场景的配对或不配对示例。我们的结果表明，学习模型捕获了两个对象域之间的潜在交互作为输入，以合理的方式在测试时输出组合场景的新实例。

##### URL
[http://arxiv.org/abs/1807.07560](http://arxiv.org/abs/1807.07560)

##### PDF
[http://arxiv.org/pdf/1807.07560](http://arxiv.org/pdf/1807.07560)

