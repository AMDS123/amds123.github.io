---
layout: post
title: "Reducing Bias in Production Speech Models"
date: 2017-05-11 23:34:42
categories: arXiv_CL
tags: arXiv_CL Optimization Inference Deep_Learning Recognition
author: Eric Battenberg, Rewon Child, Adam Coates, Christopher Fougner, Yashesh Gaur, Jiaji Huang, Heewoo Jun, Ajay Kannan, Markus Kliegl, Atul Kumar, Hairong Liu, Vinay Rao, Sanjeev Satheesh, David Seetapun, Anuroop Sriram, Zhenyao Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Replacing hand-engineered pipelines with end-to-end deep learning systems has enabled strong results in applications like speech and object recognition. However, the causality and latency constraints of production systems put end-to-end speech models back into the underfitting regime and expose biases in the model that we show cannot be overcome by "scaling up", i.e., training bigger models on more data. In this work we systematically identify and address sources of bias, reducing error rates by up to 20% while remaining practical for deployment. We achieve this by utilizing improved neural architectures for streaming inference, solving optimization issues, and employing strategies that increase audio and label modelling versatility.

##### Abstract (translated by Google)
用端到端的深度学习系统取代手工设计的流水线，在语音和对象识别等应用中取得了很好的效果。然而，生产系统的因果关系和延迟约束使端到端的语言模型回到了欠适合的体系中，并暴露了我们所展示的模型中的偏见，这是“扩大规模”所不能克服的，即对更多数据进行更大的模型训练。在这项工作中，我们系统地识别并解决了偏见的来源，将错误率降低了20％，同时保持实用的部署。我们通过利用改进的神经体系结构进行流式推理，解决优化问题以及采用提高音频和标签建模通用性的策略来实现这一目标。

##### URL
[https://arxiv.org/abs/1705.04400](https://arxiv.org/abs/1705.04400)

##### PDF
[https://arxiv.org/pdf/1705.04400](https://arxiv.org/pdf/1705.04400)

