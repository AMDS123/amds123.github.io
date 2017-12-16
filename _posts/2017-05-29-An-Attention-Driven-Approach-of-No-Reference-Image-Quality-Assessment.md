---
layout: post
title: "An Attention-Driven Approach of No-Reference Image Quality Assessment"
date: 2017-05-29 02:42:28
categories: arXiv_CV
tags: arXiv_CV QA Attention Reinforcement_Learning Represenation_Learning Prediction
author: Diqi Chen, Yizhou Wang, Tianfu Wu, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel method of no-reference image quality assessment (NR-IQA), which is to predict the perceptual quality score of a given image without using any reference image. The proposed method harnesses three functions (i) the visual attention mechanism, which affects many aspects of visual perception including image quality assessment, however, is overlooked in the NR-IQA literature. The method assumes that the fixation areas on an image contain key information to the process of IQA. (ii) the robust averaging strategy, which is a means \--- supported by psychology studies \--- to integrating multiple/step-wise evidence to make a final perceptual judgment. (iii) the multi-task learning, which is believed to be an effectual means to shape representation learning and could result in a more generalized model. To exploit the synergy of the three, we consider the NR-IQA as a dynamic perception process, in which the model samples a sequence of "informative" areas and aggregates the information to learn a representation for the tasks of jointly predicting the image quality score and the distortion type. The model learning is implemented by a reinforcement strategy, in which the rewards of both tasks guide the learning of the optimal sampling policy to acquire the "task-informative" image regions so that the predictions can be made accurately and efficiently (in terms of the sampling steps). The reinforcement learning is realized by a deep network with the policy gradient method and trained through back-propagation. In experiments, the model is tested on the TID2008 dataset and it outperforms several state-of-the-art methods. Furthermore, the model is very efficient in the sense that a small number of fixations are used in NR-IQA.

##### Abstract (translated by Google)
在本文中，我们提出了一种无参考图像质量评估（NR-IQA）的新方法，它是预测给定图像的感知质量评分而不使用任何参考图像。所提出的方法具有三个功能：（i）视觉注意机制，其影响视觉感知的许多方面，包括图像质量评估，然而在NR-IQA文献中被忽略。该方法假定图像上的注视区域包含IQA过程的关键信息。 （ii）稳健的平均策略，这是一种被心理学研究支持的方法，以整合多个/逐步的证据来作出最后的感性判断。 （3）多任务学习，这被认为是形成表征学习的有效手段，并可能导致更广义的模型。为了发挥三者之间的协同作用，我们将NR-IQA作为动态感知过程，在该过程中，模型对一系列“信息”区域进行采样并聚合信息，以学习联合预测图像质量评分和失真类型。模型学习是通过强化策略实现的，其中两项任务的奖励指导最优采样策略的学习，以获取“任务信息”图像区域，从而可以准确有效地进行预测（就采样步骤）。强化学习是通过策略梯度法的深层网络实现的，通过反向传播进行训练。在实验中，模型在TID2008数据集上进行了测试，并且胜过了几种最先进的方法。此外，该模型在NR-IQA中使用少量固定的意义上是非常有效的。

##### URL
[https://arxiv.org/abs/1612.03530](https://arxiv.org/abs/1612.03530)

##### PDF
[https://arxiv.org/pdf/1612.03530](https://arxiv.org/pdf/1612.03530)

