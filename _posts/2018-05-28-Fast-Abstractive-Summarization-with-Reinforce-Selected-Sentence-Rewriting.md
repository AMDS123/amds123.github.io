---
layout: post
title: "Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting"
date: 2018-05-28 17:49:10
categories: arXiv_AI
tags: arXiv_AI Salient Summarization Inference
author: Yen-Chun Chen, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by how humans summarize long documents, we propose an accurate and fast summarization model that first selects salient sentences and then rewrites them abstractively (i.e., compresses and paraphrases) to generate a concise overall summary. We use a novel sentence-level policy gradient method to bridge the non-differentiable computation between these two neural networks in a hierarchical way, while maintaining language fluency. Empirically, we achieve the new state-of-the-art on all metrics (including human evaluation) on the CNN/Daily Mail dataset, as well as significantly higher abstractiveness scores. Moreover, by first operating at the sentence-level and then the word-level, we enable parallel decoding of our neural generative model that results in substantially faster (10-20x) inference speed as well as 4x faster training convergence than previous long-paragraph encoder-decoder models. We also demonstrate the generalization of our model on the test-only DUC-2002 dataset, where we achieve higher scores than a state-of-the-art model.

##### Abstract (translated by Google)
受人类如何总结长文件的启发，我们提出了一个精确而快速的摘要模型，首先选择显着句子，然后以抽象方式重写它们（即压缩和释义）以产生一个简明的总体摘要。我们使用一种新型的句子层次策略梯度方法，以层次的方式来衔接这两个神经网络之间的非可微计算，同时保持语言的流畅性。在经验上，我们实现了CNN /每日邮报数据集上所有指标（包括人类评估）的最新技术水平，以及更高的抽象度分数。此外，通过首先在句级和单词级进行操作，我们可以对我们的神经生成模型进行并行解码，从而使得推理速度明显更快（10-20x），并且训练收敛速度比以前的长段快4倍编码器 - 解码器型号。我们还证明了我们的模型在仅测试DUC-2002数据集上的泛化，我们获得的分数高于最先进的模型。

##### URL
[http://arxiv.org/abs/1805.11080](http://arxiv.org/abs/1805.11080)

##### PDF
[http://arxiv.org/pdf/1805.11080](http://arxiv.org/pdf/1805.11080)

