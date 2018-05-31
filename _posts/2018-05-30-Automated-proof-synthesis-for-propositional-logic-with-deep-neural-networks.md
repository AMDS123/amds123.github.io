---
layout: post
title: "Automated proof synthesis for propositional logic with deep neural networks"
date: 2018-05-30 04:22:51
categories: arXiv_AI
tags: arXiv_AI Inference Deep_Learning
author: Taro Sekiyama, Kohei Suenaga
mathjax: true
---

* content
{:toc}

##### Abstract
This work explores the application of deep learning, a machine learning technique that uses deep neural networks (DNN) in its core, to an automated theorem proving (ATP) problem. To this end, we construct a statistical model which quantifies the likelihood that a proof is indeed a correct one of a given proposition. Based on this model, we give a proof-synthesis procedure that searches for a proof in the order of the likelihood. This procedure uses an estimator of the likelihood of an inference rule being applied at each step of a proof. As an implementation of the estimator, we propose a proposition-to-proof architecture, which is a DNN tailored to the automated proof synthesis problem. To empirically demonstrate its usefulness, we apply our model to synthesize proofs of propositional logic. We train the proposition-to-proof model using a training dataset of proposition-proof pairs. The evaluation against a benchmark set shows the very high accuracy and an improvement to the recent work of neural proof synthesis.

##### Abstract (translated by Google)
这项工作探讨了深度学习的应用，这是一种在其核心使用深度神经网络（DNN）的机器学习技术，用于自动化定理证明（ATP）问题。为此，我们构建了一个统计模型，用于量化证明确实是给定命题的正确一个的可能性。基于这个模型，我们给出一个证明合成程序，以可能性的顺序搜索一个证明。这个程序使用推理规则在证明的每一步中应用的可能性的估计量。作为估计器的一个实现，我们提出了一个可抗命题的体系结构，它是一个适合自动化证明综合问题的DNN。为了凭经验证明它的有用性，我们应用我们的模型来综合命题逻辑的证明。我们使用命题证明对的训练数据集训练了抗命题模型。针对基准集的评估显示出非常高的准确性以及对近期神经证明合成工作的改进。

##### URL
[https://arxiv.org/abs/1805.11799](https://arxiv.org/abs/1805.11799)

##### PDF
[https://arxiv.org/pdf/1805.11799](https://arxiv.org/pdf/1805.11799)

