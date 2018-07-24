---
layout: post
title: "Abstractive and Extractive Text Summarization using Document Context Vector and Recurrent Neural Networks"
date: 2018-07-20 18:56:32
categories: arXiv_CL
tags: arXiv_CL Summarization RNN
author: Chandra Khatri, Gyanit Singh, Nish Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence to sequence (Seq2Seq) learning has recently been used for abstractive and extractive summarization. In current study, Seq2Seq models have been used for eBay product description summarization. We propose a novel Document-Context based Seq2Seq models using RNNs for abstractive and extractive summarizations. Intuitively, this is similar to humans reading the title, abstract or any other contextual information before reading the document. This gives humans a high-level idea of what the document is about. We use this idea and propose that Seq2Seq models should be started with contextual information at the first time-step of the input to obtain better summaries. In this manner, the output summaries are more document centric, than being generic, overcoming one of the major hurdles of using generative models. We generate document-context from user-behavior and seller provided information. We train and evaluate our models on human-extracted-golden-summaries. The document-contextual Seq2Seq models outperform standard Seq2Seq models. Moreover, generating human extracted summaries is prohibitively expensive to scale, we therefore propose a semi-supervised technique for extracting approximate summaries and using it for training Seq2Seq models at scale. Semi-supervised models are evaluated against human extracted summaries and are found to be of similar efficacy. We provide side by side comparison for abstractive and extractive summarizers (contextual and non-contextual) on same evaluation dataset. Overall, we provide methodologies to use and evaluate the proposed techniques for large document summarization. Furthermore, we found these techniques to be highly effective, which is not the case with existing techniques.

##### Abstract (translated by Google)
序列到序列（Seq2Seq）学习最近已被用于抽象和提取摘要。在目前的研究中，Seq2Seq模型已被用于eBay产品描述汇总。我们提出了一种新的基于文档 - 上下文的Seq2Seq模型，它使用RNN进行抽象和提取总结。直观地说，这类似于人们在阅读文档之前阅读标题，摘要或任何其他上下文信息。这为人们提供了关于文档内容的高级概念。我们使用这个想法并建议Seq2Seq模型应该在输入的第一个时间步骤使用上下文信息启动，以获得更好的摘要。以这种方式，输出摘要更加以文档为中心，而不是通用的，克服了使用生成模型的主要障碍之一。我们根据用户行为和卖家提供的信息生成文档上下文。我们在人类提取的黄金摘要上训练和评估我们的模型。文档上下文Seq2Seq模型优于标准Seq2Seq模型。此外，生成人类提取的摘要的规模过于昂贵，因此我们提出了一种半监督技术，用于提取近似摘要并将其用于大规模训练Seq2Seq模型。根据人类提取的摘要评估半监督模型，发现它们具有相似的功效。我们在同一评估数据集上提供抽象和提取摘要（上下文和非上下文）的并排比较。总的来说，我们提供了使用和评估大型文档摘要的建议技术的方法。此外，我们发现这些技术非常有效，而现有技术则不然。

##### URL
[http://arxiv.org/abs/1807.08000](http://arxiv.org/abs/1807.08000)

##### PDF
[http://arxiv.org/pdf/1807.08000](http://arxiv.org/pdf/1807.08000)

