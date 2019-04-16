---
layout: post
title: "Zero-Shot Cross-lingual Classification Using Multilingual Neural Machine Translation"
date: 2018-09-12 21:34:03
categories: arXiv_CL
tags: arXiv_CL Review Attention Transfer_Learning NMT Classification
author: Akiko Eriguchi, Melvin Johnson, Orhan Firat, Hideto Kazawa, Wolfgang Macherey
mathjax: true
---

* content
{:toc}

##### Abstract
Transferring representations from large supervised tasks to downstream tasks has shown promising results in AI fields such as Computer Vision and Natural Language Processing (NLP). In parallel, the recent progress in Machine Translation (MT) has enabled one to train multilingual Neural MT (NMT) systems that can translate between multiple languages and are also capable of performing zero-shot translation. However, little attention has been paid to leveraging representations learned by a multilingual NMT system to enable zero-shot multilinguality in other NLP tasks. In this paper, we demonstrate a simple framework, a multilingual Encoder-Classifier, for cross-lingual transfer learning by reusing the encoder from a multilingual NMT system and stitching it with a task-specific classifier component. Our proposed model achieves significant improvements in the English setup on three benchmark tasks - Amazon Reviews, SST and SNLI. Further, our system can perform classification in a new language for which no classification data was seen during training, showing that zero-shot classification is possible and remarkably competitive. In order to understand the underlying factors contributing to this finding, we conducted a series of analyses on the effect of the shared vocabulary, the training data type for NMT, classifier complexity, encoder representation power, and model generalization on zero-shot performance. Our results provide strong evidence that the representations learned from multilingual NMT systems are widely applicable across languages and tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.04686](https://arxiv.org/abs/1809.04686)

##### PDF
[https://arxiv.org/pdf/1809.04686](https://arxiv.org/pdf/1809.04686)

