---
layout: post
title: "'Bilingual Expert' Can Find Translation Errors"
date: 2018-07-25 04:31:21
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference RNN Language_Model
author: Kai Fan, Bo Li, Fengming Zhou, Jiayi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in statistical machine translation via the adoption of neural sequence-to-sequence models empower the end-to-end system to achieve state-of-the-art in many WMT benchmarks. The performance of such machine translation (MT) system is usually evaluated by automatic metric BLEU when the golden references are provided for validation. However, for model inference or production deployment, the golden references are prohibitively available or require expensive human annotation with bilingual expertise. In order to address the issue of quality evaluation (QE) without reference, we propose a general framework for automatic evaluation of translation output for most WMT quality evaluation tasks. We first build a conditional target language model with a novel bidirectional transformer, named neural bilingual expert model, which is pre-trained on large parallel corpora for feature extraction. For QE inference, the bilingual expert model can simultaneously produce the joint latent representation between the source and the translation, and real-valued measurements of possible erroneous tokens based on the prior knowledge learned from parallel data. Subsequently, the features will further be fed into a simple Bi-LSTM predictive model for quality evaluation. The experimental results show that our approach achieves the state-of-the-art performance in the quality estimation track of WMT 2017/2018.

##### Abstract (translated by Google)
通过采用神经序列到序列模型，统计机器翻译的最新进展使端到端系统能够在许多WMT基准测试中实现最先进的技术。当提供用于验证的黄金参考时，通常通过自动度量BLEU来评估这种机器翻译（MT）系统的性能。然而，对于模型推断或生产部署，黄金参考资料令人望而却步，或需要昂贵的人工注释和双语专业知识。为了在没有参考的情况下解决质量评估（QE）问题，我们提出了一个用于大多数WMT质量评估任务的翻译输出自动评估的一般框架。我们首先用一种新颖的双向变换器构建一个条件目标语言模型，该变换器称为神经双语专家模型，它在大型并行语料库上进行预训练，用于特征提取。对于QE推断，双语专家模型可以同时产生源和翻译之间的联合潜在表示，以及基于从并行数据学习的先验知识对可能的错误令牌进行实值测量。随后，将这些特征进一步输入到用于质量评估的简单Bi-LSTM预测模型中。实验结果表明，我们的方法在WMT 2017/2018的质量评估轨道中实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1807.09433](http://arxiv.org/abs/1807.09433)

##### PDF
[http://arxiv.org/pdf/1807.09433](http://arxiv.org/pdf/1807.09433)

