---
layout: post
title: "Neural Lattice-to-Sequence Models for Uncertain Inputs"
date: 2017-07-21 13:31:07
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Matthias Sperber, Graham Neubig, Jan Niehues, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
The input to a neural sequence-to-sequence model is often determined by an up-stream system, e.g. a word segmenter, part of speech tagger, or speech recognizer. These up-stream models are potentially error-prone. Representing inputs through word lattices allows making this uncertainty explicit by capturing alternative sequences and their posterior probabilities in a compact form. In this work, we extend the TreeLSTM (Tai et al., 2015) into a LatticeLSTM that is able to consume word lattices, and can be used as encoder in an attentional encoder-decoder model. We integrate lattice posterior scores into this architecture by extending the TreeLSTM's child-sum and forget gates and introducing a bias term into the attention mechanism. We experiment with speech translation lattices and report consistent improvements over baselines that translate either the 1-best hypothesis or the lattice without posterior scores.

##### Abstract (translated by Google)
神经序列 - 序列模型的输入通常由上游系统确定，例如，词语分词器，词性标注器或语音识别器。这些上游模型是潜在的错误倾向。通过单词格表示输入可以通过以紧凑​​的形式捕获替代序列及其后验概率来明确这种不确定性。在这项工作中，我们将TreeLSTM（Tai et al。，2015）扩展到能够消费单词格的LatticeLSTM，并且可以在注意编码器 - 解码器模型中用作编码器。我们通过扩展TreeLSTM的child-sum和forget gate并在注意机制中引入一个偏差项来将格子后验分数整合到这个架构中。我们对语音翻译格进行实验，并报告基线的一致性改进，这些基线可以翻译1最好的假设或没有后验分数的格。

##### URL
[https://arxiv.org/abs/1704.00559](https://arxiv.org/abs/1704.00559)

##### PDF
[https://arxiv.org/pdf/1704.00559](https://arxiv.org/pdf/1704.00559)

