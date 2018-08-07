---
layout: post
title: "Visual Reference Resolution using Attention Memory for Visual Dialog"
date: 2017-11-20 18:09:07
categories: arXiv_CV
tags: arXiv_CV QA Attention Prediction VQA
author: Paul Hongsuck Seo, Andreas Lehrmann, Bohyung Han, Leonid Sigal
mathjax: true
---

* content
{:toc}

##### Abstract
Visual dialog is a task of answering a series of inter-dependent questions given an input image, and often requires to resolve visual references among the questions. This problem is different from visual question answering (VQA), which relies on spatial attention (a.k.a. visual grounding) estimated from an image and question pair. We propose a novel attention mechanism that exploits visual attentions in the past to resolve the current reference in the visual dialog scenario. The proposed model is equipped with an associative attention memory storing a sequence of previous (attention, key) pairs. From this memory, the model retrieves the previous attention, taking into account recency, which is most relevant for the current question, in order to resolve potentially ambiguous references. The model then merges the retrieved attention with a tentative one to obtain the final attention for the current question; specifically, we use dynamic parameter prediction to combine the two attentions conditioned on the question. Through extensive experiments on a new synthetic visual dialog dataset, we show that our model significantly outperforms the state-of-the-art (by ~16 % points) in situations, where visual reference resolution plays an important role. Moreover, the proposed model achieves superior performance (~ 2 % points improvement) in the Visual Dialog dataset, despite having significantly fewer parameters than the baselines.

##### Abstract (translated by Google)
视觉对话是在给定输入图像的情况下回答一系列相互依赖的问题的任务，并且通常需要解决问题中的视觉参考。这个问题不同于视觉问答（VQA），它依赖于从图像和问题对估计的空间注意力（例如视觉基础）。我们提出了一种新颖的注意机制，它利用过去的视觉注意来解决视觉对话场景中的当前参考。所提出的模型配备有关联注意记忆，其存储先前（注意，关键）对的序列。从该存储器中，模型检索先前的注意力，考虑与当前问题最相关的新近度，以便解决可能模糊的引用。然后，模型将检索到的注意力与暂定的注意力合并，以获得对当前问题的最终关注;具体来说，我们使用动态参数预测来结合这个问题的两个注意事项。通过对新的合成视觉对话数据集的大量实验，我们证明我们的模型在视觉参考分辨率起重要作用的情况下明显优于最新技术（约16％）。此外，尽管参数明显少于基线，但所提出的模型在Visual Dialog数据集中实现了卓越的性能（约2％的点改进）。

##### URL
[https://arxiv.org/abs/1709.07992](https://arxiv.org/abs/1709.07992)

##### PDF
[https://arxiv.org/pdf/1709.07992](https://arxiv.org/pdf/1709.07992)

