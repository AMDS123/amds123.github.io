---
layout: post
title: "Towards Deep Modeling of Music Semantics using EEG Regularizers"
date: 2017-12-14 12:27:11
categories: arXiv_SD
tags: arXiv_SD Embedding Transfer_Learning Relation
author: Francisco Raposo, David Martins de Matos, Ricardo Ribeiro, Suhua Tang, Yi Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling of music audio semantics has been previously tackled through learning of mappings from audio data to high-level tags or latent unsupervised spaces. The resulting semantic spaces are theoretically limited, either because the chosen high-level tags do not cover all of music semantics or because audio data itself is not enough to determine music semantics. In this paper, we propose a generic framework for semantics modeling that focuses on the perception of the listener, through EEG data, in addition to audio data. We implement this framework using a novel end-to-end 2-view Neural Network (NN) architecture and a Deep Canonical Correlation Analysis (DCCA) loss function that forces the semantic embedding spaces of both views to be maximally correlated. We also detail how the EEG dataset was collected and use it to train our proposed model. We evaluate the learned semantic space in a transfer learning context, by using it as an audio feature extractor in an independent dataset and proxy task: music audio-lyrics cross-modal retrieval. We show that our embedding model outperforms Spotify features and performs comparably to a state-of-the-art embedding model that was trained on 700 times more data. We further propose improvements to the model that are likely to improve its performance.

##### Abstract (translated by Google)
音乐音频语义的建模先前已经通过学习从音频数据到高级标签或潜在的无监督空间的映射来解决。由此产生的语义空间在理论上是有限的，或者是因为所选择的高级标签没有覆盖所有的音乐语义，或者是因为音频数据本身不足以确定音乐语义。在本文中，我们提出了一个通用的语义建模框架，除了音频数据之外，我们还通过EEG数据来关注聆听者的感知。我们使用一种新颖的端到端2视图神经网络（NN）体系结构和深度典型相关分析（DCCA）损失函数来实现这个框架，强制两个视图的语义嵌入空间是最大相关的。我们还详细介绍了如何收集EEG数据集，并用它来训练我们提出的模型。我们通过在独立的数据集和代理任务中使用它作为音频特征提取器来评估在学习环境中学习的语义空间：音乐音频 - 歌词跨模式检索。我们展示了我们的嵌入模型胜过Spotify特性，并且在700倍以上的数据上训练出最先进的嵌入模型。我们进一步提出可能改进其性能的模型的改进。

##### URL
[http://arxiv.org/abs/1712.05197](http://arxiv.org/abs/1712.05197)

##### PDF
[http://arxiv.org/pdf/1712.05197](http://arxiv.org/pdf/1712.05197)

