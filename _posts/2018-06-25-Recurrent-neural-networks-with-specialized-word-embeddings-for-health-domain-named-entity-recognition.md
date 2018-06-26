---
layout: post
title: "Recurrent neural networks with specialized word embeddings for health-domain named-entity recognition"
date: 2018-06-25 01:44:25
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Deep_Learning Recognition
author: Inigo Jauregi Unanue, Ehsan Zare Borzeshi, Massimo Piccardi
mathjax: true
---

* content
{:toc}

##### Abstract
Background. Previous state-of-the-art systems on Drug Name Recognition (DNR) and Clinical Concept Extraction (CCE) have focused on a combination of text "feature engineering" and conventional machine learning algorithms such as conditional random fields and support vector machines. However, developing good features is inherently heavily time-consuming. Conversely, more modern machine learning approaches such as recurrent neural networks (RNNs) have proved capable of automatically learning effective features from either random assignments or automated word "embeddings". Objectives. (i) To create a highly accurate DNR and CCE system that avoids conventional, time-consuming feature engineering. (ii) To create richer, more specialized word embeddings by using health domain datasets such as MIMIC-III. (iii) To evaluate our systems over three contemporary datasets. Methods. Two deep learning methods, namely the Bidirectional LSTM and the Bidirectional LSTM-CRF, are evaluated. A CRF model is set as the baseline to compare the deep learning systems to a traditional machine learning approach. The same features are used for all the models. Results. We have obtained the best results with the Bidirectional LSTM-CRF model, which has outperformed all previously proposed systems. The specialized embeddings have helped to cover unusual words in DDI-DrugBank and DDI-MedLine, but not in the 2010 i2b2/VA IRB Revision dataset. Conclusion. We present a state-of-the-art system for DNR and CCE. Automated word embeddings has allowed us to avoid costly feature engineering and achieve higher accuracy. Nevertheless, the embeddings need to be retrained over datasets that are adequate for the domain, in order to adequately cover the domain-specific vocabulary.

##### Abstract (translated by Google)
背景。以前的药物名称识别（DNR）和临床概念提取（CCE）最先进的系统集中于文本“特征工程”和常规机器学习算法（例如条件随机场和支持向量机）的组合。但是，开发好的功能本质上是非常耗时的。相反，更现代的机器学习方法，例如递归神经网络（RNN）已经证明能够自动从随机分配或自动化词语“嵌入”中学习有效特征。目标。 （i）创建高度准确的DNR和CCE系统，避免传统的，耗时的特征工程。 （ii）通过使用MIMIC-III等健康领域数据集创建更丰富，更专业的词嵌入。 （三）评估我们的系统在三个当代数据集。方法。评估两种深度学习方法，即双向LSTM和双向LSTM-CRF。将CRF模型设置为比较深度学习系统与传统机器学习方法的基线。所有模型都使用相同的功能。结果。我们用双向LSTM-CRF模型取得了最好的结果，该模型的表现超过了以前提出的所有系统。专门的嵌入有助于涵盖DDI-DrugBank和DDI-MedLine中的不寻常词汇，但不包含在2010 i2b2 / VA IRB修订数据集中。结论。我们为DNR和CCE提供最先进的系统。自动化词语嵌入使我们能够避免代价高昂的特征工程并实现更高的准确性。尽管如此，为了充分涵盖特定领域的词汇表，需要对数据集重新进行嵌入以适应领域。

##### URL
[http://arxiv.org/abs/1706.09569](http://arxiv.org/abs/1706.09569)

##### PDF
[http://arxiv.org/pdf/1706.09569](http://arxiv.org/pdf/1706.09569)

