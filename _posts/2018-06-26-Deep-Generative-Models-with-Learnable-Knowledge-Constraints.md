---
layout: post
title: "Deep Generative Models with Learnable Knowledge Constraints"
date: 2018-06-26 02:31:35
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Reinforcement_Learning
author: Zhiting Hu, Zichao Yang, Ruslan Salakhutdinov, Xiaodan Liang, Lianhui Qin, Haoye Dong, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
The broad set of deep generative models (DGMs) has achieved remarkable advances. However, it is often difficult to incorporate rich structured domain knowledge with the end-to-end DGMs. Posterior regularization (PR) offers a principled framework to impose structured constraints on probabilistic models, but has limited applicability to the diverse DGMs that can lack a Bayesian formulation or even explicit density evaluation. PR also requires constraints to be fully specified {\it a priori}, which is impractical or suboptimal for complex knowledge with learnable uncertain parts. In this paper, we establish mathematical correspondence between PR and reinforcement learning (RL), and, based on the connection, expand PR to learn constraints as the extrinsic reward in RL. The resulting algorithm is model-agnostic to apply to any DGMs, and is flexible to adapt arbitrary constraints with the model jointly. Experiments on human image generation and templated sentence generation show models with learned knowledge constraints by our algorithm greatly improve over base generative models.

##### Abstract (translated by Google)
广泛的深层生成模式（DGM）取得了显着的进步。但是，将丰富的结构化领域知识与端到端DGM结合起来往往很困难。后向正则化（PR）提供了一个原则性的框架来对概率模型施加结构化的约束，但是对于可能缺乏贝叶斯公式或甚至是显式密度评估的各种DGMs的适用性有限。 PR还要求约束条件被完全指定，这对于具有可学习的不确定部分的复杂知识来说是不切实际或次优的。在本文中，我们建立了PR与强化学习（RL）之间的数学对应关系，并基于这种关系扩展PR来学习约束作为RL中的外部奖励。所得到的算法与模型无关，适用于任何DGM，并且可以灵活地与模型共同调整任意约束条件。对人类图像生成和模板化句子生成的实验表明，通过我们的算法，学习知识约束的模型大大改善了基本生成模型。

##### URL
[http://arxiv.org/abs/1806.09764](http://arxiv.org/abs/1806.09764)

##### PDF
[http://arxiv.org/pdf/1806.09764](http://arxiv.org/pdf/1806.09764)

