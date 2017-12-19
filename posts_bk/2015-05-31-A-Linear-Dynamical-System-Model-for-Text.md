---
layout: post
title: "A Linear Dynamical System Model for Text"
date: 2015-05-31 20:04:53
categories: arXiv_CL
tags: arXiv_CL Embedding Inference Language_Model
author: David Belanger, Sham Kakade
mathjax: true
---

* content
{:toc}

##### Abstract
Low dimensional representations of words allow accurate NLP models to be trained on limited annotated data. While most representations ignore words' local context, a natural way to induce context-dependent representations is to perform inference in a probabilistic latent-variable sequence model. Given the recent success of continuous vector space word representations, we provide such an inference procedure for continuous states, where words' representations are given by the posterior mean of a linear dynamical system. Here, efficient inference can be performed using Kalman filtering. Our learning algorithm is extremely scalable, operating on simple cooccurrence counts for both parameter initialization using the method of moments and subsequent iterations of EM. In our experiments, we employ our inferred word embeddings as features in standard tagging tasks, obtaining significant accuracy improvements. Finally, the Kalman filter updates can be seen as a linear recurrent neural network. We demonstrate that using the parameters of our model to initialize a non-linear recurrent neural network language model reduces its training time by a day and yields lower perplexity.

##### Abstract (translated by Google)
词的低维表示允许准确的NLP模型在有限的注释数据上进行训练。虽然大多数表示忽略了单词的本地语境，但引起语境相关表示的一种自然方式是在概率潜变量序列模型中进行推理。考虑到连续向量空间词表示的最近成功，我们提供了连续状态的推理过程，其中词语的表示由线性动态系统的后验均值给出。这里，可以使用卡尔曼滤波进行有效的推断。我们的学习算法具有极高的可扩展性，使用矩量法和随后的EM迭代对参数初始化进行简单的一致计数操作。在我们的实验中，我们使用推断的词嵌入作为标准标记任务的特征，获得显着的准确性改进。最后，卡尔曼滤波器的更新可以看作是一个线性递归神经网络。我们证明，使用我们的模型参数来初始化一个非线性递归神经网络语言模型减少了一天的培训时间，并产生较低的困惑。

##### URL
[https://arxiv.org/abs/1502.04081](https://arxiv.org/abs/1502.04081)

##### PDF
[https://arxiv.org/pdf/1502.04081](https://arxiv.org/pdf/1502.04081)

