---
layout: post
title: "SenGen: Sentence Generating Neural Variational Topic Model"
date: 2017-08-01 13:31:24
categories: arXiv_CL
tags: arXiv_CL RNN
author: Ramesh Nallapati, Igor Melnyk, Abhishek Kumar, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new topic model that generates documents by sampling a topic for one whole sentence at a time, and generating the words in the sentence using an RNN decoder that is conditioned on the topic of the sentence. We argue that this novel formalism will help us not only visualize and model the topical discourse structure in a document better, but also potentially lead to more interpretable topics since we can now illustrate topics by sampling representative sentences instead of bag of words or phrases. We present a variational auto-encoder approach for learning in which we use a factorized variational encoder that independently models the posterior over topical mixture vectors of documents using a feed-forward network, and the posterior over topic assignments to sentences using an RNN. Our preliminary experiments on two different datasets indicate early promise, but also expose many challenges that remain to be addressed.

##### Abstract (translated by Google)
我们提出了一个新的话题模型，通过一次对一个整个句子抽样一个话题产生文件，并且使用以该句子的话题为条件的RNN解码器在句子中产生单词。我们认为，这种新颖的形式主义不仅可以帮助我们更好地对文档中的话题结构进行可视化和模型化，而且还可能导致更多可解释的话题，因为我们现在可以通过对代表性句子进行抽样而不是单词或短语来说明话题。我们提出了一种变化的自动编码器的学习方法，我们使用一个分解变分编码器，独立地建模文本的后部使用一个前馈网络的主题混合物向量，并使用一个RNN后面的话题分配到句子。我们对两个不同数据集的初步实验表明了早期的承诺，但也暴露了许多仍有待解决的挑战。

##### URL
[https://arxiv.org/abs/1708.00308](https://arxiv.org/abs/1708.00308)

##### PDF
[https://arxiv.org/pdf/1708.00308](https://arxiv.org/pdf/1708.00308)

