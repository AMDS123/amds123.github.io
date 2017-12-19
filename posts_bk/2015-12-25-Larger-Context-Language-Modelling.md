---
layout: post
title: "Larger-Context Language Modelling"
date: 2015-12-25 17:51:01
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Tian Wang, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel method to incorporate corpus-level discourse information into language modelling. We call this larger-context language model. We introduce a late fusion approach to a recurrent language model based on long short-term memory units (LSTM), which helps the LSTM unit keep intra-sentence dependencies and inter-sentence dependencies separate from each other. Through the evaluation on three corpora (IMDB, BBC, and PennTree Bank), we demon- strate that the proposed model improves perplexity significantly. In the experi- ments, we evaluate the proposed approach while varying the number of context sentences and observe that the proposed late fusion is superior to the usual way of incorporating additional inputs to the LSTM. By analyzing the trained larger- context language model, we discover that content words, including nouns, adjec- tives and verbs, benefit most from an increasing number of context sentences. This analysis suggests that larger-context language model improves the unconditional language model by capturing the theme of a document better and more easily.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新的方法，将语料库语篇信息纳入语言建模。我们称之为大语境语言模型。我们引入了一种基于长期短期记忆单元（LSTM）的循环语言模型的后期融合方法，它可以帮助LSTM单元保持句子间依赖关系和句子间依赖关系。通过对三个语料库（IMDB，BBC和PennTree Bank）的评估，我们证明了所提出的模型显着改善了困惑。在实验中，我们评估了所提出的方法，同时改变了上下文句子的数量，并且观察到提出的后期融合优于通常的方式来将额外的输入结合到LSTM中。通过分析训练的大语境语言模型，我们发现包含名词，主语和动词在内的内容词语从越来越多的语境句子中获益最多。这种分析表明，大语境语言模型通过更好，更容易地捕捉文件的主题来改善无条件语言模型。

##### URL
[https://arxiv.org/abs/1511.03729](https://arxiv.org/abs/1511.03729)

##### PDF
[https://arxiv.org/pdf/1511.03729](https://arxiv.org/pdf/1511.03729)

