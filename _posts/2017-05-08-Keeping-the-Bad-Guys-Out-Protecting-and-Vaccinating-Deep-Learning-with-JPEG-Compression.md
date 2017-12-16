---
layout: post
title: "Keeping the Bad Guys Out: Protecting and Vaccinating Deep Learning with JPEG Compression"
date: 2017-05-08 14:55:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Classification Deep_Learning Recognition
author: Nilaksh Das, Madhuri Shanbhogue, Shang-Tse Chen, Fred Hohman, Li Chen, Michael E. Kounavis, Duen Horng Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have achieved great success in solving a variety of machine learning (ML) problems, especially in the domain of image recognition. However, recent research showed that DNNs can be highly vulnerable to adversarially generated instances, which look seemingly normal to human observers, but completely confuse DNNs. These adversarial samples are crafted by adding small perturbations to normal, benign images. Such perturbations, while imperceptible to the human eye, are picked up by DNNs and cause them to misclassify the manipulated instances with high confidence. In this work, we explore and demonstrate how systematic JPEG compression can work as an effective pre-processing step in the classification pipeline to counter adversarial attacks and dramatically reduce their effects (e.g., Fast Gradient Sign Method, DeepFool). An important component of JPEG compression is its ability to remove high frequency signal components, inside square blocks of an image. Such an operation is equivalent to selective blurring of the image, helping remove additive perturbations. Further, we propose an ensemble-based technique that can be constructed quickly from a given well-performing DNN, and empirically show how such an ensemble that leverages JPEG compression can protect a model from multiple types of adversarial attacks, without requiring knowledge about the model.

##### Abstract (translated by Google)
深度神经网络（DNNs）在解决各种机器学习（ML）问题方面取得了巨大的成功，特别是在图像识别领域。然而，最近的研究表明，DNN可能非常容易受到对手生成的事件的影响，这看起来似乎对人类观察者来说是正常的，但完全混淆了DNN。这些敌对样本是通过对正常，良性图像添加小扰动而制成的。这样的扰动虽然对人眼不可察觉，但是被DNN拾取并使它们高度置信地错误分类被操纵的实例。在这项工作中，我们探索并展示了系统的JPEG压缩如何在分类流水线中作为一个有效的预处理步骤，以抵消敌对攻击并大幅降低其效应（例如，快速梯度符号法，DeepFool）。 JPEG压缩的一个重要组成部分是能够去除图像的方块内的高频信号成分。这样的操作相当于图像的选择性模糊，有助于消除添加剂的干扰。此外，我们提出了一个基于集合的技术，可以从一个性能良好的DNN快速构建，并且凭经验显示如何利用JPEG压缩的这样一个集合可以保护模型免受多种类型的敌对攻击，而不需要关于模型的知识。

##### URL
[https://arxiv.org/abs/1705.02900](https://arxiv.org/abs/1705.02900)

##### PDF
[https://arxiv.org/pdf/1705.02900](https://arxiv.org/pdf/1705.02900)

