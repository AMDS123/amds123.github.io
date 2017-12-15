---
layout: post
title: "Representation Stability as a Regularizer for Improved Text Analytics Transfer Learning"
date: 2017-04-12 04:38:18
categories: arXiv_CL
tags: arXiv_CL Sentiment Knowledge Transfer_Learning
author: Matthew Riemer, Elham Khabiri, Richard Goodwin
mathjax: true
---

* content
{:toc}

##### Abstract
Although neural networks are well suited for sequential transfer learning tasks, the catastrophic forgetting problem hinders proper integration of prior knowledge. In this work, we propose a solution to this problem by using a multi-task objective based on the idea of distillation and a mechanism that directly penalizes forgetting at the shared representation layer during the knowledge integration phase of training. We demonstrate our approach on a Twitter domain sentiment analysis task with sequential knowledge transfer from four related tasks. We show that our technique outperforms networks fine-tuned to the target task. Additionally, we show both through empirical evidence and examples that it does not forget useful knowledge from the source task that is forgotten during standard fine-tuning. Surprisingly, we find that first distilling a human made rule based sentiment engine into a recurrent neural network and then integrating the knowledge with the target task data leads to a substantial gain in generalization performance. Our experiments demonstrate the power of multi-source transfer techniques in practical text analytics problems when paired with distillation. In particular, for the SemEval 2016 Task 4 Subtask A (Nakov et al., 2016) dataset we surpass the state of the art established during the competition with a comparatively simple model architecture that is not even competitive when trained on only the labeled task specific data.

##### Abstract (translated by Google)
虽然神经网络非常适合顺序转移学习任务，但是灾难性遗忘问题阻碍了现有知识的正确整合。在这项工作中，我们提出了一个解决这个问题的方法，即使用基于蒸馏思想的多任务目标和直接惩罚知识整合阶段遗忘共享表示层的机制。我们在Twitter域情感分析任务中展示了我们的方法，从四个相关的任务中顺序传递知识。我们表明，我们的技术胜过了微调到目标任务的网络。另外，我们通过经验证据和实例展示了它们不会忘记在标准微调期间被遗忘的源任务中的有用知识。令人惊讶的是，我们发现首先将基于人工规则的情感引擎提炼成循环神经网络，然后将知识与目标任务数据相结合，可以大大提高泛化性能。我们的实验证明了与蒸馏配对时，实际文本分析问题中多源转移技术的强大功能。尤其是，对于2016年下半年任务4子任务（Nakov等人，2016年）数据集，我们超越了在竞争中建立的最先进的技术水平，相对简单的模型体系结构甚至不具有竞争力数据。

##### URL
[https://arxiv.org/abs/1704.03617](https://arxiv.org/abs/1704.03617)

##### PDF
[https://arxiv.org/pdf/1704.03617](https://arxiv.org/pdf/1704.03617)

