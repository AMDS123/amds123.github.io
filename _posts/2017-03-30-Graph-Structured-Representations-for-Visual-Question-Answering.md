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
本文提出了用场景内容和问题的结构化表示来改进视觉问题回答（VQA）。 VQA的一个关键挑战是需要对视觉和文本领域进行联合推理。基于CNN / LSTM的VQA主导方法受到整体向量表示的限制，这种表示在很大程度上忽略了场景中的结构和问题的形式。 CNN特征向量不能有效地捕捉像多个对象实例一样简单的情况，而LSTM将问题作为一系列的词来处理，这并不能反映语言结构的真实复杂性。我们建议在场景对象和问题单词上建立图形，并且描述一个利用这些表示结构的深层神经网络。这比LSTM的顺序处理显示出显着的好处。我们的方法的总体功效表现在显着的改进，在“抽象场景”多选基准的准确度从71.2％到74.4％，精度从34.7％到39.1％对“平衡”的场景，即具有细微差别的图像和对相同问题的是/否回答。

##### URL
[https://arxiv.org/abs/1609.05600](https://arxiv.org/abs/1609.05600)

##### PDF
[https://arxiv.org/pdf/1609.05600](https://arxiv.org/pdf/1609.05600)

