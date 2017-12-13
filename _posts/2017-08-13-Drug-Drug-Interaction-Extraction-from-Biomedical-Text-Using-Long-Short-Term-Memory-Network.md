---
layout: post
title: "Drug-Drug Interaction Extraction from Biomedical Text Using Long Short Term Memory Network"
date: 2017-08-13 12:56:03
categories: arXiv_CV
tags: arXiv_CV Embedding RNN Classification
author: Sunil Kumar Sahu, Ashish Anand
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous administration of multiple drugs can have synergistic or antagonistic effects as one drug can affect activities of other drugs. Synergistic effects lead to improved therapeutic outcomes, whereas, antagonistic effects can be life-threatening, may lead to increased healthcare cost, or may even cause death. Thus identification of unknown drug-drug interaction (DDI) is an important concern for efficient and effective healthcare. Although multiple resources for DDI exist, they are often unable to keep pace with rich amount of information available in fast growing biomedical texts. Most existing methods model DDI extraction from text as a classification problem and mainly rely on handcrafted features. Some of these features further depend on domain specific tools. Recently neural network models using latent features have been shown to give similar or better performance than the other existing models dependent on handcrafted features. In this paper, we present three models namely, {\it B-LSTM}, {\it AB-LSTM} and {\it Joint AB-LSTM} based on long short-term memory (LSTM) network. All three models utilize word and position embedding as latent features and thus do not rely on explicit feature engineering. Further use of bidirectional long short-term memory (Bi-LSTM) networks allow implicit feature extraction from the whole sentence. The two models, {\it AB-LSTM} and {\it Joint AB-LSTM} also use attentive pooling in the output of Bi-LSTM layer to assign weights to features. Our experimental results on the SemEval-2013 DDI extraction dataset show that the {\it Joint AB-LSTM} model outperforms all the existing methods, including those relying on handcrafted features. The other two proposed LSTM models also perform competitively with state-of-the-art methods.

##### Abstract (translated by Google)
多种药物的同时给药可以具有协同或拮抗作用，因为一种药物可以影响其他药物的活性。协同效应导致改善的治疗结果，而拮抗作用可能危及生命，可能导致增加的医疗成本，甚至可能导致死亡。因此，识别未知的药物相互作用（DDI）是高效和有效的医疗保健的重要关注。尽管存在多种DDI资源，但它们往往无法跟上快速增长的生物医学文本中丰富的信息量。现有的大多数方法都是将从文本中提取的DDI建模为一个分类问题，主要依赖于手工特征。其中一些功能还取决于特定于域的工具。近来，使用潜在特征的神经网络模型已经显示出与依赖于手工特征的其他现有模型相似或更好的性能。在本文中，我们基于长期短期记忆（LSTM）网络提出了三种模型：{\ it B-LSTM}，{\ it AB-LSTM}和{ABIt LSTM}。所有这三种模型都将字和位置嵌入作为潜在特征，因此不依赖显式特征工程。双向长时间记忆（Bi-LSTM）网络的进一步使用允许从整个句子中提取隐式特征。这两个模型{\ it AB-LSTM}和{\ it Joint AB-LSTM}也在Bi-LSTM层的输出中使用专注池来为特征分配权重。我们在SemEval-2013 DDI提取数据集上的实验结果显示，{\ it Joint AB-LSTM}模型优于所有现有方法，包括那些依赖手工功能的方法。另外两个提出的LSTM模型也与最先进的方法竞争。

##### URL
[https://arxiv.org/abs/1701.08303](https://arxiv.org/abs/1701.08303)

##### PDF
[https://arxiv.org/pdf/1701.08303](https://arxiv.org/pdf/1701.08303)

