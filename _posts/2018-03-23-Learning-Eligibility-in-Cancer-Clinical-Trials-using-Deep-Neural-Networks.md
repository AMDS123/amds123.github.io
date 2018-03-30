---
layout: post
title: "Learning Eligibility in Cancer Clinical Trials using Deep Neural Networks"
date: 2018-03-23 14:45:57
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Represenation_Learning
author: Aurelia Bustos, Antonio Pertusa
mathjax: true
---

* content
{:toc}

##### Abstract
Interventional cancer clinical trials are generally too restrictive and patients are often excluded from them on the basis of comorbidity, past or concomitant treatments and the fact that they are over a certain age. The efficacy and safety of new treatments for patients with these characteristics are not, therefore, defined. In this work, we build a model with which to automatically predict whether short clinical statements were considered inclusion or exclusion criteria. We used clinical trials protocols on cancer that have been available in public registries for the last 18 years to train word embeddings, and constructed a dataset of 6M short free-texts labeled as eligible or not eligible. We then trained and validated a text classifier, using deep neural networks with pre-trained word-embedding as its inputs, to predict whether or not short free-text statements describing clinical information were considered eligible. The best model achieved an F-measure of 0.91 and an almost perfect agreement when employing a validation set of 800K labeled statements. The trained model was also tested on an independent set of clinical statements mimicking those used in routine clinical practice, yielding a consistent performance. We additionally analyzed the semantic reasoning of the word embedding representations obtained, and were able to identify equivalent treatments for a type of tumor in an analogy with the drugs used to treat other tumors. The present work shows that representation learning using neural networks can be successfully leveraged to extract the medical knowledge available on clinical trial protocols and potentially assist practitioners when prescribing treatments.

##### Abstract (translated by Google)
介入性癌症临床试验通常过于严格，患者常常根据合并症，过去或伴随治疗以及他们超过一定年龄而被排除在外。因此，对具有这些特征的患者的新疗法的有效性和安全性没有定义。在这项工作中，我们建立了一个模型，可以自动预测短期临床陈述是否被视为纳入或排除标准。我们使用了过去18年在公共注册管理机构提供的关于癌症的临床试验方案来训练单词嵌入，并构建了一个6M短文本的数据集，标记为合格或不合格。然后，我们使用预先训练的词嵌入作为其输入的深度神经网络来训练和验证文本分类器，以预测描述临床信息的短自由文本陈述是否被认为是合格的。当采用800K标记语句的验证集时，最佳模型实现了0.91的F-measure和几乎完美的协议。训练有素的模型也在一套独立的临床陈述中进行了测试，模拟了常规临床实践中使用的陈述，产生了一致的表现。我们另外分析了所获得的单词嵌入表示的语义推理，并且能够类似于用于治疗其他肿瘤的药物来识别用于类型的肿瘤的等同治疗。目前的工作表明，使用神经网络进行表示学习可以成功地用于提取临床试验方案中可用的医学知识，并可能在开处方时帮助从业者。

##### URL
[https://arxiv.org/abs/1803.08312](https://arxiv.org/abs/1803.08312)

##### PDF
[https://arxiv.org/pdf/1803.08312](https://arxiv.org/pdf/1803.08312)

