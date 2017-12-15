---
layout: post
title: "A Deep Generative Framework for Paraphrase Generation"
date: 2017-09-15 06:58:13
categories: arXiv_CL
tags: arXiv_CL RNN Quantitative
author: Ankush Gupta, Arvind Agarwal, Prawaan Singh, Piyush Rai
mathjax: true
---

* content
{:toc}

##### Abstract
Paraphrase generation is an important problem in NLP, especially in question answering, information retrieval, information extraction, conversation systems, to name a few. In this paper, we address the problem of generating paraphrases automatically. Our proposed method is based on a combination of deep generative models (VAE) with sequence-to-sequence models (LSTM) to generate paraphrases, given an input sentence. Traditional VAEs when combined with recurrent neural networks can generate free text but they are not suitable for paraphrase generation for a given sentence. We address this problem by conditioning the both, encoder and decoder sides of VAE, on the original sentence, so that it can generate the given sentence's paraphrases. Unlike most existing models, our model is simple, modular and can generate multiple paraphrases, for a given sentence. Quantitative evaluation of the proposed method on a benchmark paraphrase dataset demonstrates its efficacy, and its performance improvement over the state-of-the-art methods by a significant margin, whereas qualitative human evaluation indicate that the generated paraphrases are well-formed, grammatically correct, and are relevant to the input sentence. Furthermore, we evaluate our method on a newly released question paraphrase dataset, and establish a new baseline for future research.

##### Abstract (translated by Google)
释义生成是NLP中的一个重要问题，尤其是在问答，信息检索，信息提取，会话系统等方面。在本文中，我们解决了自动生成释义的问题。我们提出的方法是基于深生成模型（VAE）和序列 - 序列模型（LSTM）的组合来生成释义，给定一个输入句子。传统的VAE结合循环神经网络可以生成自由文本，但不适合给定句子的复述生成。我们通过调整VAE的编码器和解码器两侧的原始句子来解决这个问题，以便它能够生成给定句子的释义。与大多数现有的模型不同，我们的模型是简单的，模块化的，可以为给定的句子生成多个释义。在基准复述数据集上对所提出的方法进行定量评估证明了其效力，并且其性能改进优于现有技术的方法，而定性的人类评估表明所生成的复述句是格式良好的，语法上正确的，并与输入的句子有关。此外，我们在新发布的问题解释数据集上评估我们的方法，并为未来的研究建立一个新的基准。

##### URL
[https://arxiv.org/abs/1709.05074](https://arxiv.org/abs/1709.05074)

##### PDF
[https://arxiv.org/pdf/1709.05074](https://arxiv.org/pdf/1709.05074)

