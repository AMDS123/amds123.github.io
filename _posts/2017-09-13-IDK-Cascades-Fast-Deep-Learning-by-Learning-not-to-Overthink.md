---
layout: post
title: "IDK Cascades: Fast Deep Learning by Learning not to Overthink"
date: 2017-09-13 17:19:04
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification Deep_Learning Prediction
author: Xin Wang, Yujia Luo, Daniel Crankshaw, Alexey Tumanov, Fisher Yu, Joseph E. Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
Advances in deep learning have led to substantial increases in prediction accuracy but have been accompanied by increases in the cost of rendering predictions. We conjecture that for a majority of real-world inputs, the recent advances in deep learning have created models that effectively "over-think" on simple inputs. In this paper we revisit the question of how to effectively build model cascades to reduce prediction costs. While classic cascade techniques primarily leverage class asymmetry to reduce cost, we extend this approach to arbitrary multi-class prediction tasks. We introduce the "I Don't Know" (IDK) prediction cascades framework, a general framework for composing a set of pre-trained models to accelerate inference without a loss in prediction accuracy. We propose two search based methods for constructing cascades as well as a new cost-aware objective within this framework. We evaluate these techniques on a range of both benchmark and real-world datasets and demonstrate that prediction cascades can reduce computation by 37%, resulting in up to 1.6x speedups in image classification tasks over state-of-the-art models without a loss in accuracy. Furthermore, on a driving motion prediction task evaluated on a large scale autonomous driving dataset, prediction cascades achieved 95% accuracy when combined with human experts, while requiring human intervention on less than 30% of the queries.

##### Abstract (translated by Google)
深度学习的进展导致了预测准确度的显着提高，但伴随着渲染预测成本的增加。我们猜想，对于大多数现实世界的投入来说，最近深度学习的进展已经创造出了对简单输入有效“过度思考”的模型。在本文中，我们将重新探讨如何有效地建立模型级联来降低预测成本的问题。虽然经典级联技术主要是利用类不对称来降低成本，但我们将这种方法扩展到任意多类预测任务。我们介绍了“我不知道”（IDK）预测级联框架，这是一个构建一组预先训练的模型以加速推理而不损失预测准确性的一般框架。我们提出两种基于搜索的方法来构建级联，并在此框架内提出一个新的成本感知目标。我们在基准和实际数据集的范围内评估这些技术，并证明预测级联可以减少37％的计算量，从而使图像分类任务的速度提高1.6倍，而不会损失最先进的模型精确度。此外，在大规模自主驾驶数据集上评估的驾驶运动预测任务中，与人类专家结合时，预测级联达到95％的准确度，而需要人工干预的查询不到30％。

##### URL
[https://arxiv.org/abs/1706.00885](https://arxiv.org/abs/1706.00885)

##### PDF
[https://arxiv.org/pdf/1706.00885](https://arxiv.org/pdf/1706.00885)

