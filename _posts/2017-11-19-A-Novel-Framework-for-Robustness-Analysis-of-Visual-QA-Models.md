---
layout: post
title: "A Novel Framework for Robustness Analysis of Visual QA Models"
date: 2017-11-19 05:47:07
categories: arXiv_CV
tags: arXiv_CV Adversarial VQA
author: Jia-Hong Huang, Cuong Duc Dao, Modar Alfadly, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have been playing an essential role in many computer vision tasks including Visual Question Answering (VQA). Until recently, the study of their accuracy has been the main focus of research and now there is a huge trend toward assessing the robustness of these models against adversarial attacks by evaluating the accuracy of these models under increasing levels of noisiness. In VQA, the attack can target the image and/or the proposed main question and yet there is a lack of proper analysis of this aspect of VQA. In this work, we propose a new framework that uses semantically relevant questions, dubbed basic questions, acting as noise to evaluate the robustness of VQA models. We hypothesize that as the similarity of a basic question to the main question decreases, the level of noise increases. So, to generate a reasonable noise level for a given main question, we rank a pool of basic questions based on their similarity with this main question. We cast this ranking problem as a LASSO optimization problem. We also propose a novel robustness measure R_score and two large-scale question datasets, General Basic Question Dataset and Yes/No Basic Question Dataset in order to standardize robustness analysis of VQA models. We analyze the robustness of several state-of-the-art VQA models and show that attention-based VQA models are more robust than other methods in general. The main goal of this framework is to serve as a benchmark to help the community in building more accurate and robust VQA models.

##### Abstract (translated by Google)
深度神经网络在包括视觉问答（VQA）在内的许多计算机视觉任务中一直扮演着重要的角色。直到最近，对其准确性的研究一直是研究的主要焦点，而现在通过评估这些模型在不断增加的噪音水平下的准确性来评估这些模型对敌对攻击的稳健性有巨大的趋势。在VQA中，攻击可以针对图像和/或提出的主要问题，但对VQA的这个方面缺乏适当的分析。在这项工作中，我们提出了一个新的框架，使用语义相关的问题，被称为基本问题，作为噪声评估VQA模型的鲁棒性。我们推测，当一个基本问题与主要问题的相似度降低时，噪音水平会增加。因此，要为给定的主要问题产生一个合理的噪音水平，我们根据它们与这个主要问题的相似性来排列一系列基本问题。我们把这个排名问题作为一个LASSO优化问题。为了规范VQA模型的鲁棒性分析，我们还提出了一个新的鲁棒性度量R_score和两个大规模问题数据集，一般基本问题数据集和是/否基本问题数据集。我们分析了几个最先进的VQA模型的鲁棒性，并且显示出基于注意的VQA模型比其他方法更加稳健。该框架的主要目标是作为帮助社区构建更加准确和强大的VQA模型的基准。

##### URL
[https://arxiv.org/abs/1711.06232](https://arxiv.org/abs/1711.06232)

##### PDF
[https://arxiv.org/pdf/1711.06232](https://arxiv.org/pdf/1711.06232)

