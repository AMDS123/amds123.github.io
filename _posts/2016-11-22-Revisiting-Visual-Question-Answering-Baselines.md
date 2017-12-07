---
layout: post
title: "Revisiting Visual Question Answering Baselines"
date: 2016-11-22 21:26:06
categories: arXiv_CV
tags: arXiv_CV Image_Caption VQA
author: Allan Jabri, Armand Joulin, Laurens van der Maaten
mathjax: true
---

* content
{:toc}

##### Abstract
Visual question answering (VQA) is an interesting learning setting for evaluating the abilities and shortcomings of current systems for image understanding. Many of the recently proposed VQA systems include attention or memory mechanisms designed to support "reasoning". For multiple-choice VQA, nearly all of these systems train a multi-class classifier on image and question features to predict an answer. This paper questions the value of these common practices and develops a simple alternative model based on binary classification. Instead of treating answers as competing choices, our model receives the answer as input and predicts whether or not an image-question-answer triplet is correct. We evaluate our model on the Visual7W Telling and the VQA Real Multiple Choice tasks, and find that even simple versions of our model perform competitively. Our best model achieves state-of-the-art performance on the Visual7W Telling task and compares surprisingly well with the most complex systems proposed for the VQA Real Multiple Choice task. We explore variants of the model and study its transferability between both datasets. We also present an error analysis of our model that suggests a key problem of current VQA systems lies in the lack of visual grounding of concepts that occur in the questions and answers. Overall, our results suggest that the performance of current VQA systems is not significantly better than that of systems designed to exploit dataset biases.

##### Abstract (translated by Google)
视觉问答（VQA）是评估当前图像理解系统的能力和缺点的一个有趣的学习环境。许多最近提出的VQA系统包括旨在支持“推理”的注意或记忆机制。对于多选VQA，几乎所有这些系统都会对图像和问题特征进行多级分类，以预测答案。本文质疑这些通用实践的价值，并开发了一个基于二元分类的简单替代模型。我们的模型不是将答案视为竞争性的选择，而是接受答案作为输入，并预测图像问答三元组是否正确。我们在Visual7W Telling和VQA Real Multiple Choice任务上评估我们的模型，发现即使是我们模型的简单版本也具有竞争力。我们最好的模型在Visual7W的演讲任务上实现了最先进的性能，并与VQA Real Multiple Choice任务中提出的最复杂的系统进行了惊人的比较。我们探索模型的变种，并研究两个数据集之间的可转移性。我们还提出了对我们模型的错误分析，表明当前VQA系统的关键问题在于对问题和答案中出现的概念缺乏视觉基础。总的来说，我们的结果表明，目前的VQA系统的性能并没有明显好于利用数据集偏差设计的系统。

##### URL
[https://arxiv.org/abs/1606.08390](https://arxiv.org/abs/1606.08390)

##### PDF
[https://arxiv.org/pdf/1606.08390](https://arxiv.org/pdf/1606.08390)

