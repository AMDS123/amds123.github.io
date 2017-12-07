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
视觉对话是一个任务，回答一系列相互依赖的问题给予一个输入图像，往往需要解决问题之间的视觉引用。这个问题不同于视觉问题回答（VQA），其依赖于从图像和问题对估计的空间关注（又名视觉基础）。我们提出了一个新颖的注意机制，利用过去的视觉注意力来解决目前在视觉对话场景中的参考。所提出的模型配备有存储一系列先前（注意，关键）对的关联注意记忆。从这个记忆中，模型检索以前的注意力，考虑与当前问题最相关的新近性，以便解决潜在的模棱两可的引用。该模型然后将检索到的注意力与一个试探性的注意力相结合，以获得当前问题的最后关注;具体而言，我们使用动态参数预测来结合关注问题的两个注意点。通过对新的合成视觉对话数据集进行广泛的实验，我们发现，在视觉参考分辨率起着重要作用的情况下，我们的模型显着优于现有技术（约16％）。此外，所提出的模型在Visual Dialog数据集中实现了优异的性能（约2％的提高），尽管参数比基线少得多。

##### URL
[https://arxiv.org/abs/1709.07992](https://arxiv.org/abs/1709.07992)

##### PDF
[https://arxiv.org/pdf/1709.07992](https://arxiv.org/pdf/1709.07992)

