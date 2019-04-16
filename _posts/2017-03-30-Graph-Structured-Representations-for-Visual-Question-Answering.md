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


##### URL
[https://arxiv.org/abs/1609.05600](https://arxiv.org/abs/1609.05600)

##### PDF
[https://arxiv.org/pdf/1609.05600](https://arxiv.org/pdf/1609.05600)

