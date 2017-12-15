---
layout: post
title: "Unsupervised Pretraining for Sequence to Sequence Learning"
date: 2016-11-08 20:42:26
categories: arXiv_CL
tags: arXiv_CL Summarization Optimization Language_Model
author: Prajit Ramachandran, Peter J. Liu, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence to sequence models are successful tools for supervised sequence learning tasks, such as machine translation. Despite their success, these models still require much labeled data and it is unclear how to improve them using unlabeled data, which is much less expensive to obtain. In this paper, we present simple changes that lead to a significant improvement in the accuracy of seq2seq models when the labeled set is small. Our method intializes the encoder and decoder of the seq2seq model with the trained weights of two language models, and then all weights are jointly fine-tuned with labeled data. An additional language modeling loss can be used to regularize the model during fine-tuning. We apply this method to low-resource tasks in machine translation and abstractive summarization and find that it significantly improves the subsequent supervised models. Our main finding is that the pretraining accelerates training and improves generalization of seq2seq models, achieving state-of-the-art results on the WMT English$\rightarrow$German task. Our model obtains an improvement of 1.3 BLEU from the previous best models on both WMT'14 and WMT'15 English$\rightarrow$German. Our ablation study shows that pretraining helps seq2seq models in different ways depending on the nature of the task: translation benefits from the improved generalization whereas summarization benefits from the improved optimization.

##### Abstract (translated by Google)
序列模型序列是监督序列学习任务（如机器翻译）的成功工具。尽管他们取得了成功，但是这些模型仍然需要大量的标记数据，而且还不清楚如何使用无标记的数据来改进它们，这些数据的获取成本要低得多。在本文中，我们给出简单的变化，当标记集合很小时，导致seq2seq模型的精度显着提高。我们的方法用两个语言模型的训练权重对seq2seq模型的编码器和解码器进行初始化，然后将所有权重与标记数据一起进行联合微调。在微调期间，可以使用另外的语言建模损失来使模型正规化。我们将这种方法应用于机器翻译和抽象概括中的低资源任务，发现它显着改善了后续的监督模型。我们的主要发现是，预训练加速了训练，并提高了seq2seq模型的泛化能力，在WMT英语$ \ rightarrow $德语任务中取得了最新的成果。我们的模型在WMT'14和WMT'15英语$ \ rightarrow $德语版本上得到了1.3 BLEU的改进。我们的消融研究表明，根据任务的性质，预训练以不同的方式帮助seq2seq模型：翻译受益于改进的泛化，而摘要则从改进的优化中受益。

##### URL
[https://arxiv.org/abs/1611.02683](https://arxiv.org/abs/1611.02683)

##### PDF
[https://arxiv.org/pdf/1611.02683](https://arxiv.org/pdf/1611.02683)

