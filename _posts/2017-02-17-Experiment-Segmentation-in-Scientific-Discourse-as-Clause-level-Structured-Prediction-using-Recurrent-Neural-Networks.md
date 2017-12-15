---
layout: post
title: "Experiment Segmentation in Scientific Discourse as Clause-level Structured Prediction using Recurrent Neural Networks"
date: 2017-02-17 15:39:21
categories: arXiv_SD
tags: arXiv_SD Segmentation Attention RNN Deep_Learning Prediction
author: Pradeep Dasigi, Gully A.P.C. Burns, Eduard Hovy, Anita de Waard
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep learning model for identifying structure within experiment narratives in scientific literature. We take a sequence labeling approach to this problem, and label clauses within experiment narratives to identify the different parts of the experiment. Our dataset consists of paragraphs taken from open access PubMed papers labeled with rhetorical information as a result of our pilot annotation. Our model is a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) cells that labels clauses. The clause representations are computed by combining word representations using a novel attention mechanism that involves a separate RNN. We compare this model against LSTMs where the input layer has simple or no attention and a feature rich CRF model. Furthermore, we describe how our work could be useful for information extraction from scientific literature.

##### Abstract (translated by Google)
我们提出了一个深入的学习模式，用于识别科学文献中实验叙述的结构。我们采用序列标签的方法来解决这个问题，并且在实验叙述中标记子句来识别实验的不同部分。我们的数据集包括从开放获取的PubMed论文中摘录的带有修辞信息的段落作为我们的试点注解的结果。我们的模型是带有长短期记忆（LSTM）细胞的递归神经网络（RNN），其标记子句。子句表示是通过使用涉及单独的RNN的新颖注意机制组合词语表示来计算的。我们将此模型与输入层简单或不重视的LSTM进行比较，并将其与特征丰富的CRF模型进行比较。此外，我们描述了我们的工作如何能够从科学文献中提取信息。

##### URL
[https://arxiv.org/abs/1702.05398](https://arxiv.org/abs/1702.05398)

##### PDF
[https://arxiv.org/pdf/1702.05398](https://arxiv.org/pdf/1702.05398)

