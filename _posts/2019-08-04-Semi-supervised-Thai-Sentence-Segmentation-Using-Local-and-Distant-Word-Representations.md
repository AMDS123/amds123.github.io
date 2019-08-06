---
layout: post
title: "Semi-supervised Thai Sentence Segmentation Using Local and Distant Word Representations"
date: 2019-08-04 08:24:05
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention Embedding Deep_Learning
author: Chanatip Saetia, Ekapol Chuangsuwanich, Tawunrat Chalothorn, Peerapon Vateekul
mathjax: true
---

* content
{:toc}

##### Abstract
A sentence is typically treated as the minimal syntactic unit used for extracting valuable information from a longer piece of text. However, in written Thai, there are no explicit sentence markers. We proposed a deep learning model for the task of sentence segmentation that includes three main contributions. First, we integrate n-gram embedding as a local representation to capture word groups near sentence boundaries. Second, to focus on the keywords of dependent clauses, we combine the model with a distant representation obtained from self-attention modules. Finally, due to the scarcity of labeled data, for which annotation is difficult and time-consuming, we also investigate and adapt Cross-View Training (CVT) as a semi-supervised learning technique, allowing us to utilize unlabeled data to improve the model representations. In the Thai sentence segmentation experiments, our model reduced the relative error by 7.4% and 10.5% compared with the baseline models on the Orchid and UGWC datasets, respectively. We also applied our model to the task of pronunciation recovery on the IWSLT English dataset. Our model outperformed the prior sequence tagging models, achieving a relative error reduction of 2.5%. Ablation studies revealed that utilizing n-gram presentations was the main contributing factor for Thai, while the semi-supervised training helped the most for English.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01294](http://arxiv.org/abs/1908.01294)

##### PDF
[http://arxiv.org/pdf/1908.01294](http://arxiv.org/pdf/1908.01294)

