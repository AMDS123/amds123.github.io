---
layout: post
title: "S-Net: From Answer Extraction to Answer Generation for Machine Reading Comprehension"
date: 2017-11-20 06:10:03
categories: arXiv_CL
tags: arXiv_CL
author: Chuanqi Tan, Furu Wei, Nan Yang, Bowen Du, Weifeng Lv, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel approach to machine reading comprehension for the MS-MARCO dataset. Unlike the SQuAD dataset that aims to answer a question with exact text spans in a passage, the MS-MARCO dataset defines the task as answering a question from multiple passages and the words in the answer are not necessary in the passages. We therefore develop an extraction-then-synthesis framework to synthesize answers from extraction results. Specifically, the answer extraction model is first employed to predict the most important sub-spans from the passage as evidence, and the answer synthesis model takes the evidence as additional features along with the question and passage to further elaborate the final answers. We build the answer extraction model with state-of-the-art neural networks for single passage reading comprehension, and propose an additional task of passage ranking to help answer extraction in multiple passages. The answer synthesis model is based on the sequence-to-sequence neural networks with extracted evidences as features. Experiments show that our extraction-then-synthesis method outperforms state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来机器阅读理解MS-MARCO数据集。与SQUAD数据集不同，SQUAD数据集的目的是通过一段精确的文本跨度来回答问题，MS-MARCO数据集将任务定义为回答多个段落中的问题，而答案中的单词在段落中不是必需的。因此，我们开发了一个提取 - 合成框架来综合提取结果的答案。具体而言，答案抽取模型首先用来预测来自文章的最重要的子跨度作为证据，答案综合模型将证据作为附加特征以及问题和段落进一步阐述最终答案。我们建立了具有最先进神经网络的答案抽取模型，用于单段阅读理解，并提出了一个额外的通道排序任务来帮助解答多段提取。答案综合模型基于序列 - 序列神经网络，提取证据作为特征。实验表明，我们的提取 - 合成方法胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1706.04815](https://arxiv.org/abs/1706.04815)

##### PDF
[https://arxiv.org/pdf/1706.04815](https://arxiv.org/pdf/1706.04815)

