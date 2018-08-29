---
layout: post
title: "Evaluating the Utility of Hand-crafted Features in Sequence Labelling"
date: 2018-08-28 00:53:06
categories: arXiv_CL
tags: arXiv_CL Deep_Learning Recognition
author: Minghao Wu, Fei Liu, Trevor Cohn
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional wisdom is that hand-crafted features are redundant for deep learning models, as they already learn adequate representations of text automatically from corpora. In this work, we test this claim by proposing a new method for exploiting handcrafted features as part of a novel hybrid learning approach, incorporating a feature auto-encoder loss component. We evaluate on the task of named entity recognition (NER), where we show that including manual features for part-of-speech, word shapes and gazetteers can improve the performance of a neural CRF model. We obtain a $F_1$ of 91.89 for the CoNLL-2003 English shared task, which significantly outperforms a collection of highly competitive baseline models. We also present an ablation study showing the importance of auto-encoding, over using features as either inputs or outputs alone, and moreover, show including the autoencoder components reduces training requirements to 60\%, while retaining the same predictive accuracy.

##### Abstract (translated by Google)
传统观点认为，手工制作的特征对于深度学习模型来说是多余的，因为它们已经从语料库中自动学习了足够的文本表示。在这项工作中，我们通过提出一种利用手工制作功能的新方法作为新型混合学习方法的一部分来测试这一主张，其中包含一个功能自动编码器丢失组件。我们评估命名实体识别（NER）的任务，其中我们表明包括词性，字形和地名词典的手动特征可以改善神经CRF模型的性能。我们获得了CoNLL-2003英语共享任务的$ F_1 $ 91.89，该任务明显优于一系列竞争激烈的基线模型。我们还提供了一个消融研究，显示了自动编码的重要性，而不仅仅是使用输入或输出功能，而且，显示包括自动编码器组件将训练要求降低到60％，同时保持相同的预测准确性。

##### URL
[http://arxiv.org/abs/1808.09075](http://arxiv.org/abs/1808.09075)

##### PDF
[http://arxiv.org/pdf/1808.09075](http://arxiv.org/pdf/1808.09075)

