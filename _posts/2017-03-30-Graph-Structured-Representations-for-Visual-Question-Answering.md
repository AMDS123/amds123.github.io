---
layout: post
title: "Graph-Structured Representations for Visual Question Answering"
date: 2017-03-30 04:26:26
categories: arXiv_CV
tags: arXiv_CV QA RNN VQA
author: Damien Teney, Lingqiao Liu, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes to improve visual question answering (VQA) with structured representations of both scene contents and questions. A key challenge in VQA is to require joint reasoning over the visual and text domains. The predominant CNN/LSTM-based approach to VQA is limited by monolithic vector representations that largely ignore structure in the scene and in the form of the question. CNN feature vectors cannot effectively capture situations as simple as multiple object instances, and LSTMs process questions as series of words, which does not reflect the true complexity of language structure. We instead propose to build graphs over the scene objects and over the question words, and we describe a deep neural network that exploits the structure in these representations. This shows significant benefit over the sequential processing of LSTMs. The overall efficacy of our approach is demonstrated by significant improvements over the state-of-the-art, from 71.2% to 74.4% in accuracy on the "abstract scenes" multiple-choice benchmark, and from 34.7% to 39.1% in accuracy over pairs of "balanced" scenes, i.e. images with fine-grained differences and opposite yes/no answers to a same question.

##### Abstract (translated by Google)
本文提出用场景内容和问题的结构化表示来改进视觉问答（VQA）。 VQA的一个关键挑战是要求对视觉和文本域进行联合推理。主要的基于CNN / LSTM的VQA方法受到单片矢量表示的限制，这些表示在很大程度上忽略了场景中的结构和问题的形式。 CNN特征向量不能有效地捕获像多个对象实例那样简单的情况，并且LSTM将问题作为一系列单词处理，这不能反映语言结构的真实复杂性。我们建议在场景对象和问题词上构建图形，并且我们描述了利用这些表示中的结构的深度神经网络。这显示出相对于LSTM的顺序处理的显着益处。我们的方法的总体效果通过对“抽象场景”多项选择基准的精确度的71.2％到74.4％以及从准确率的34.7％到39.1％的显着改进来证明。成对的“平衡”场景，即具有细粒度差异的图像和对相同问题的相反的是/否答案。

##### URL
[https://arxiv.org/abs/1609.05600](https://arxiv.org/abs/1609.05600)

##### PDF
[https://arxiv.org/pdf/1609.05600](https://arxiv.org/pdf/1609.05600)

