---
layout: post
title: "Automatic Open Knowledge Acquisition via Long Short-Term Memory Networks with Feedback Negative Sampling"
date: 2016-05-25 14:59:46
categories: arXiv_CV
tags: arXiv_CV Knowledge RNN Deep_Learning Relation Memory_Networks
author: Byungsoo Kim, Hwanjo Yu, Gary Geunbae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Previous studies in Open Information Extraction (Open IE) are mainly based on extraction patterns. They manually define patterns or automatically learn them from a large corpus. However, these approaches are limited when grasping the context of a sentence, and they fail to capture implicit relations. In this paper, we address this problem with the following methods. First, we exploit long short-term memory (LSTM) networks to extract higher-level features along the shortest dependency paths, connecting headwords of relations and arguments. The path-level features from LSTM networks provide useful clues regarding contextual information and the validity of arguments. Second, we constructed samples to train LSTM networks without the need for manual labeling. In particular, feedback negative sampling picks highly negative samples among non-positive samples through a model trained with positive samples. The experimental results show that our approach produces more precise and abundant extractions than state-of-the-art open IE systems. To the best of our knowledge, this is the first work to apply deep learning to Open IE.

##### Abstract (translated by Google)
以前在Open Information Extraction（Open IE）中的研究主要基于提取模式。他们手动定义模式或从大型语料库自动学习。但是，这些方法在掌握一个句子的语境时是有限的，而且不能捕捉到隐含的关系。在本文中，我们用下面的方法来解决这个问题。首先，我们利用长时间的短时记忆（LSTM）网络，沿着最短的依赖路径提取更高层次的特征，连接关系和争论的词条。来自LSTM网络的路径级特征提供了关于上下文信息和参数有效性的有用线索。其次，我们构建样本来训练LSTM网络，而不需要手动标记。特别是，反馈负样本通过正样本训练的模型在非正样本中选取高度负样本。实验结果表明，我们的方法比最先进的开放式IE系统产生更精确和更丰富的提取。就我们所知，这是第一个将深度学习应用于Open IE的工作。

##### URL
[https://arxiv.org/abs/1605.07918](https://arxiv.org/abs/1605.07918)

##### PDF
[https://arxiv.org/pdf/1605.07918](https://arxiv.org/pdf/1605.07918)

