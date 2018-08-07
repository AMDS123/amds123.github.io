---
layout: post
title: "A Novel Framework for Robustness Analysis of Visual QA Models"
date: 2017-11-19 05:47:07
categories: arXiv_CV
tags: arXiv_CV Adversarial QA Attention Optimization VQA
author: Jia-Hong Huang, Cuong Duc Dao, Modar Alfadly, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have been playing an essential role in many computer vision tasks including Visual Question Answering (VQA). Until recently, the study of their accuracy has been the main focus of research and now there is a huge trend toward assessing the robustness of these models against adversarial attacks by evaluating the accuracy of these models under increasing levels of noisiness. In VQA, the attack can target the image and/or the proposed main question and yet there is a lack of proper analysis of this aspect of VQA. In this work, we propose a new framework that uses semantically relevant questions, dubbed basic questions, acting as noise to evaluate the robustness of VQA models. We hypothesize that as the similarity of a basic question to the main question decreases, the level of noise increases. So, to generate a reasonable noise level for a given main question, we rank a pool of basic questions based on their similarity with this main question. We cast this ranking problem as a LASSO optimization problem. We also propose a novel robustness measure R_score and two large-scale question datasets, General Basic Question Dataset and Yes/No Basic Question Dataset in order to standardize robustness analysis of VQA models. We analyze the robustness of several state-of-the-art VQA models and show that attention-based VQA models are more robust than other methods in general. The main goal of this framework is to serve as a benchmark to help the community in building more accurate and robust VQA models.

##### Abstract (translated by Google)
深度神经网络在许多计算机视觉任务中发挥着重要作用，包括视觉问答（VQA）。直到最近，对其准确性的研究一直是研究的主要焦点，现在通过在不断增加的噪声水平下评估这些模型的准确性来评估这些模型对抗对抗性攻击的稳健性的巨大趋势。在VQA中，攻击可以针对图像和/或提出的主要问题，但是对VQA的这个方面缺乏适当的分析。在这项工作中，我们提出了一个新的框架，它使用语义相关的问题，称为基本问题，充当噪声来评估VQA模型的稳健性。我们假设随着基本问题与主要问题的相似性降低，噪声水平增加。因此，为了给出给定主要问题的合理噪声水平，我们根据它们与这个主要问题的相似性对基本问题进行排序。我们将此排名问题视为LASSO优化问题。我们还提出了一种新的鲁棒性度量R_score和两个大规模问题数据集，通用基本问题数据集和是/否基本问题数据集，以标准化VQA模型的稳健性分析。我们分析了几种最先进的VQA模型的稳健性，并表明基于注意力的VQA模型比其他方法更加稳健。该框架的主要目标是作为基准，帮助社区构建更准确，更强大的VQA模型。

##### URL
[https://arxiv.org/abs/1711.06232](https://arxiv.org/abs/1711.06232)

##### PDF
[https://arxiv.org/pdf/1711.06232](https://arxiv.org/pdf/1711.06232)

