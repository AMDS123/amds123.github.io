---
layout: post
title: "Boosting Self-Supervised Learning via Knowledge Transfer"
date: 2018-05-01 15:08:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Quantitative Detection
author: Mehdi Noroozi, Ananth Vinjimoor, Paolo Favaro, Hamed Pirsiavash
mathjax: true
---

* content
{:toc}

##### Abstract
In self-supervised learning, one trains a model to solve a so-called pretext task on a dataset without the need for human annotation. The main objective, however, is to transfer this model to a target domain and task. Currently, the most effective transfer strategy is fine-tuning, which restricts one to use the same model or parts thereof for both pretext and target tasks. In this paper, we present a novel framework for self-supervised learning that overcomes limitations in designing and comparing different tasks, models, and data domains. In particular, our framework decouples the structure of the self-supervised model from the final task-specific fine-tuned model. This allows us to: 1) quantitatively assess previously incompatible models including handcrafted features; 2) show that deeper neural network models can learn better representations from the same pretext task; 3) transfer knowledge learned with a deep model to a shallower one and thus boost its learning. We use this framework to design a novel self-supervised task, which achieves state-of-the-art performance on the common benchmarks in PASCAL VOC 2007, ILSVRC12 and Places by a significant margin. Our learned features shrink the mAP gap between models trained via self-supervised learning and supervised learning from 5.9% to 2.6% in object detection on PASCAL VOC 2007.

##### Abstract (translated by Google)
在自我监督学习中，人们训练一个模型来解决数据集中所谓的借口任务，而无需人工注释。但是，主要目标是将此模型转移到目标域和任务。目前，最有效的转移策略是微调，这限制了一个人使用相同的模型或其部分来进行借口和目标任务。在本文中，我们提出了一种新的自我监督学习框架，克服了设计和比较不同任务，模型和数据域的限制。特别是，我们的框架将自我监督模型的结构与最终的任务特定的微调模型分离开来。这使我们能够：1）定量评估以前不兼容的模型，包括手工制作的特征; 2）表明，更深的神经网络模型可以从同样的借口任务中学习更好的表征; 3）将深入学习的知识转移到较浅的知识中，从而促进学习。我们使用这个框架来设计一种新型的自我监督任务，在PASCAL VOC 2007，ILSVRC12和Places中的公共基准上达到了最高水平的性能表现。我们的学习功能缩小了PASCAL VOC 2007中通过自我监督学习和监督学习训练的模型之间的差距，从5.9％减少到2.6％。

##### URL
[https://arxiv.org/abs/1805.00385](https://arxiv.org/abs/1805.00385)

##### PDF
[https://arxiv.org/pdf/1805.00385](https://arxiv.org/pdf/1805.00385)

