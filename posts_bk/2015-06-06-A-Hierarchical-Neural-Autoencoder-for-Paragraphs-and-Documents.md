---
layout: post
title: "A Hierarchical Neural Autoencoder for Paragraphs and Documents"
date: 2015-06-06 01:47:34
categories: arXiv_CL
tags: arXiv_CL Summarization Embedding RNN
author: Jiwei Li, Minh-Thang Luong, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language generation of coherent long texts like paragraphs or longer documents is a challenging problem for recurrent networks models. In this paper, we explore an important step toward this generation task: training an LSTM (Long-short term memory) auto-encoder to preserve and reconstruct multi-sentence paragraphs. We introduce an LSTM model that hierarchically builds an embedding for a paragraph from embeddings for sentences and words, then decodes this embedding to reconstruct the original paragraph. We evaluate the reconstructed paragraph using standard metrics like ROUGE and Entity Grid, showing that neural models are able to encode texts in a way that preserve syntactic, semantic, and discourse coherence. While only a first step toward generating coherent text units from neural models, our work has the potential to significantly impact natural language generation and summarization\footnote{Code for the three models described in this paper can be found at www.stanford.edu/~jiweil/ .

##### Abstract (translated by Google)
自然语言生成连贯的长文本，如段落或较长的文档，对于经常性网络模型来说是一个具有挑战性的问题。在本文中，我们探索了迈向这一代任务的重要一步：训练LSTM（长短期记忆）自动编码器来保存和重构多句段落。我们引入一个LSTM模型，从句子和单词的嵌入中分层次地构建一个段落的嵌入，然后对这个嵌入进行解码以重建原始段落。我们使用ROUGE和Entity Grid等标准指标评估重建的段落，表明神经模型能够以保留句法，语义和语篇连贯性的方式编码文本。虽然只是从神经模型生成相关文本单元的第一步，但是我们的工作有可能显着影响自然语言生成和汇总。本文所述的三种模型的代码可以在www.stanford.edu/~ jiweil /。

##### URL
[https://arxiv.org/abs/1506.01057](https://arxiv.org/abs/1506.01057)

##### PDF
[https://arxiv.org/pdf/1506.01057](https://arxiv.org/pdf/1506.01057)

