---
layout: post
title: "Patient representation learning and interpretable evaluation using clinical notes"
date: 2018-07-03 23:20:49
categories: arXiv_CL
tags: arXiv_CL Sparse Represenation_Learning Classification
author: Madhumita Sushil, Simon &#x160;uster, Kim Luyckx, Walter Daelemans
mathjax: true
---

* content
{:toc}

##### Abstract
We have three contributions in this work: 1. We explore the utility of a stacked denoising autoencoder and a paragraph vector model to learn task-independent dense patient representations directly from clinical notes. To analyze if these representations are transferable across tasks, we evaluate them in multiple supervised setups to predict patient mortality, primary diagnostic and procedural category, and gender. We compare their performance with sparse representations obtained from a bag-of-words model. We observe that the learned generalized representations significantly outperform the sparse representations when we have few positive instances to learn from, and there is an absence of strong lexical features. 2. We compare the model performance of the feature set constructed from a bag of words to that obtained from medical concepts. In the latter case, concepts represent problems, treatments, and tests. We find that concept identification does not improve the classification performance. 3. We propose novel techniques to facilitate model interpretability. To understand and interpret the representations, we explore the best encoded features within the patient representations obtained from the autoencoder model. Further, we calculate feature sensitivity across two networks to identify the most significant input features for different classification tasks when we use these pretrained representations as the supervised input. We successfully extract the most influential features for the pipeline using this technique.

##### Abstract (translated by Google)
我们在这项工作中有三个贡献：1。我们探索堆叠去噪自动编码器和段落矢量模型的效用，以直接从临床记录中学习与任务无关的密集患者表示。为了分析这些表示是否可以跨任务转移，我们在多个监督设置中对它们进行评估，以预测患者死亡率，主要诊断和程序类别以及性别。我们将它们的性能与从词袋模型中获得的稀疏表示进行比较。我们观察到，当我们很少有积极的实例需要学习时，学习的广义表示明显优于稀疏表示，并且缺乏强大的词汇特征。我们将从一袋单词构建的特征集的模型性能与从医学概念中获得的特征集进行比较。在后一种情况下，概念代表问题，治疗和测试。我们发现概念识别不会提高分类性能。我们提出了促进模型可解释性的新技术。为了理解和解释表示，我们探索从自动编码器模型获得的患者表示中的最佳编码特征。此外，当我们使用这些预训练表示作为监督输入时，我们计算两个网络的特征灵敏度，以识别不同分类任务的最重要输入特征。我们使用这种技术成功地为管道提取了最具影响力的特征。

##### URL
[http://arxiv.org/abs/1807.01395](http://arxiv.org/abs/1807.01395)

##### PDF
[http://arxiv.org/pdf/1807.01395](http://arxiv.org/pdf/1807.01395)

