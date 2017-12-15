---
layout: post
title: "DiSAN: Directional Self-Attention Network for RNN/CNN-Free Language Understanding"
date: 2017-11-20 23:39:11
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Knowledge QA Attention Embedding CNN Inference RNN Classification Prediction
author: Tao Shen, Tianyi Zhou, Guodong Long, Jing Jiang, Shirui Pan, Chengqi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural nets (RNN) and convolutional neural nets (CNN) are widely used on NLP tasks to capture the long-term and local dependencies, respectively. Attention mechanisms have recently attracted enormous interest due to their highly parallelizable computation, significantly less training time, and flexibility in modeling dependencies. We propose a novel attention mechanism in which the attention between elements from input sequence(s) is directional and multi-dimensional (i.e., feature-wise). A light-weight neural net, "Directional Self-Attention Network (DiSAN)", is then proposed to learn sentence embedding, based solely on the proposed attention without any RNN/CNN structure. DiSAN is only composed of a directional self-attention with temporal order encoded, followed by a multi-dimensional attention that compresses the sequence into a vector representation. Despite its simple form, DiSAN outperforms complicated RNN models on both prediction quality and time efficiency. It achieves the best test accuracy among all sentence encoding methods and improves the most recent best result by 1.02% on the Stanford Natural Language Inference (SNLI) dataset, and shows state-of-the-art test accuracy on the Stanford Sentiment Treebank (SST), Multi-Genre natural language inference (MultiNLI), Sentences Involving Compositional Knowledge (SICK), Customer Review, MPQA, TREC question-type classification and Subjectivity (SUBJ) datasets.

##### Abstract (translated by Google)
递归神经网络（RNN）和卷积神经网络（CNN）被广泛应用于NLP任务以分别捕获长期和局部依赖性。注意机制最近引起了极大的兴趣，由于其高度可并行化的计算，显着减少培训时间，并在建模依赖的灵活性。我们提出了一种新颖的注意机制，其中来自输入序列的元素之间的关注是定向的和多维的（即，特征明智的）。然后提出一个轻量级的神经网络“定向自注意网络（DiSAN）”来学习句子嵌入，而不需要任何RNN / CNN结构。 DiSAN仅由时间顺序编码的方向性自我注意组成，随后是将该顺序压缩成矢量表示的多维注意力。尽管形式简单，但在预测质量和时间效率方面，DiSAN优于复杂的RNN模型。它在所有句子编码方法中达到了最好的测试精度，并且在斯坦福自然语言推理（SNLI）数据集中将最近的最好结果提高了1.02％，并且在斯坦福情绪树库（SST）上显示了最新的测试精度），Multi-Genre自然语言推理（MultiNLI），涉及构成知识的句子（SICK），顾客评论，MPQA，TREC问题类型分类和主观性（SUBJ）数据集。

##### URL
[https://arxiv.org/abs/1709.04696](https://arxiv.org/abs/1709.04696)

##### PDF
[https://arxiv.org/pdf/1709.04696](https://arxiv.org/pdf/1709.04696)

