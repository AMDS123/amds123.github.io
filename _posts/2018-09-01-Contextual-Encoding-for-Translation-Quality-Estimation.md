---
layout: post
title: "Contextual Encoding for Translation Quality Estimation"
date: 2018-09-01 08:01:29
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Prediction
author: Junjie Hu, Wei-Cheng Chang, Yuexin Wu, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
The task of word-level quality estimation (QE) consists of taking a source sentence and machine-generated translation, and predicting which words in the output are correct and which are wrong. 
 In this paper, propose a method to effectively encode the local and global contextual information for each target word using a three-part neural network approach. 
 The first part uses an embedding layer to represent words and their part-of-speech tags in both languages. The second part leverages a one-dimensional convolution layer to integrate local context information for each target word. The third part applies a stack of feed-forward and recurrent neural networks to further encode the global context in the sentence before making the predictions. This model was submitted as the CMU entry to the WMT2018 shared task on QE, and achieves strong results, ranking first in three of the six tracks.

##### Abstract (translated by Google)
单词级质量评估（QE）的任务包括获取源句和机器生成的翻译，并预测输出中的哪些单词是正确的，哪些是错误的。
 在本文中，提出了一种使用三部分神经网络方法有效编码每个目标词的局部和全局上下文信息的方法。
 第一部分使用嵌入层来表示两种语言中的单词及其词性标签。第二部分利用一维卷积层来整合每个目标词的本地上下文信息。第三部分应用一堆前馈和递归神经网络，在进行预测之前进一步对句子中的全局上下文进行编码。该模型作为CMU入口提交给QE上的WMT2018共享任务，并取得了很好的成绩，在六个轨道中的三个中排名第一。

##### URL
[http://arxiv.org/abs/1809.00129](http://arxiv.org/abs/1809.00129)

##### PDF
[http://arxiv.org/pdf/1809.00129](http://arxiv.org/pdf/1809.00129)

