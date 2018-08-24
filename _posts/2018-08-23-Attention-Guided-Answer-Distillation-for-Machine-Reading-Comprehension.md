---
layout: post
title: "Attention-Guided Answer Distillation for Machine Reading Comprehension"
date: 2018-08-23 06:27:58
categories: arXiv_CL
tags: arXiv_CL Adversarial Knowledge QA Attention Inference Prediction
author: Minghao Hu, Yuxing Peng, Furu Wei, Zhen Huang, Dongsheng Li, Nan Yang, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Despite that current reading comprehension systems have achieved significant advancements, their promising performances are often obtained at the cost of making an ensemble of numerous models. Besides, existing approaches are also vulnerable to adversarial attacks. This paper tackles these problems by leveraging knowledge distillation, which aims to transfer knowledge from an ensemble model to a single model. We first demonstrate that vanilla knowledge distillation applied to answer span prediction is effective for reading comprehension systems. We then propose two novel approaches that not only penalize the prediction on confusing answers but also guide the training with alignment information distilled from the ensemble. Experiments show that our best student model has only a slight drop of 0.4% F1 on the SQuAD test set compared to the ensemble teacher, while running 12x faster during inference. It even outperforms the teacher on adversarial SQuAD datasets and NarrativeQA benchmark.

##### Abstract (translated by Google)
尽管当前的阅读理解系统已经取得了显着的进步，但是它们的有希望的性能通常是以制造众多模型的集合为代价获得的。此外，现有方法也容易受到对抗性攻击。本文通过利用知识蒸馏来解决这些问题，旨在将知识从集合模型转移到单一模型。我们首先证明应用于答案跨度预测的香草知识蒸馏对于阅读理解系统是有效的。然后，我们提出两种新颖的方法，不仅惩罚对混乱答案的预测，而且还引导训练与从整体中提取的对齐信息。实验表明，与合奏教师相比，我们最好的学生模型在SQUAD测试装置上仅有0.4％的轻微下降，而在推理过程中跑得快了12倍。它甚至在对抗性SQuAD数据集和NarrativeQA基准测试中优于教师。

##### URL
[http://arxiv.org/abs/1808.07644](http://arxiv.org/abs/1808.07644)

##### PDF
[http://arxiv.org/pdf/1808.07644](http://arxiv.org/pdf/1808.07644)

