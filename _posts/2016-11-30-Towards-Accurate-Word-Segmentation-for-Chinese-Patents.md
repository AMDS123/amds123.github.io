---
layout: post
title: "Towards Accurate Word Segmentation for Chinese Patents"
date: 2016-11-30 07:53:34
categories: arXiv_CL
tags: arXiv_CL Segmentation
author: Si Li, Nianwen Xue
mathjax: true
---

* content
{:toc}

##### Abstract
A patent is a property right for an invention granted by the government to the inventor. An invention is a solution to a specific technological problem. So patents often have a high concentration of scientific and technical terms that are rare in everyday language. The Chinese word segmentation model trained on currently available everyday language data sets performs poorly because it cannot effectively recognize these scientific and technical terms. In this paper we describe a pragmatic approach to Chinese word segmentation on patents where we train a character-based semi-supervised sequence labeling model by extracting features from a manually segmented corpus of 142 patents, enhanced with information extracted from the Chinese TreeBank. Experiments show that the accuracy of our model reached 95.08% (F1 score) on a held-out test set and 96.59% on development set, compared with an F1 score of 91.48% on development set if the model is trained on the Chinese TreeBank. We also experimented with some existing domain adaptation techniques, the results show that the amount of target domain data and the selected features impact the performance of the domain adaptation techniques.

##### Abstract (translated by Google)
专利是政府授予发明人的发明的产权。一项发明是解决具体的技术问题。所以专利往往有很高的科技术语，这在日常语言中是很少见的。在当前可用的日常语言数据集上训练的中文分词模型表现不佳，因为它不能有效地识别这些科学和技术术语。在本文中，我们描述了一种实用的中文分词专利方法，我们通过从142个专利的手动分割语料中提取特征来训练基于字符的半监督序列标签模型，并利用从中国树库提取的信息进行增强。实验表明，模型的准确性达到了95.08％（F1得分）和96.59％，相比之下，如果模型在中国树上训练，F1得分为91.48％。我们还尝试了一些现有的领域适应技术，结果表明，目标领域数据量和选择的特征影响领域适应技术的性能。

##### URL
[https://arxiv.org/abs/1611.10038](https://arxiv.org/abs/1611.10038)

##### PDF
[https://arxiv.org/pdf/1611.10038](https://arxiv.org/pdf/1611.10038)

