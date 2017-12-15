---
layout: post
title: "Joint Line Segmentation and Transcription for End-to-End Handwritten Paragraph Recognition"
date: 2016-04-28 09:08:30
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation Attention RNN Prediction Recognition
author: Théodore Bluche
mathjax: true
---

* content
{:toc}

##### Abstract
Offline handwriting recognition systems require cropped text line images for both training and recognition. On the one hand, the annotation of position and transcript at line level is costly to obtain. On the other hand, automatic line segmentation algorithms are prone to errors, compromising the subsequent recognition. In this paper, we propose a modification of the popular and efficient multi-dimensional long short-term memory recurrent neural networks (MDLSTM-RNNs) to enable end-to-end processing of handwritten paragraphs. More particularly, we replace the collapse layer transforming the two-dimensional representation into a sequence of predictions by a recurrent version which can recognize one line at a time. In the proposed model, a neural network performs a kind of implicit line segmentation by computing attention weights on the image representation. The experiments on paragraphs of Rimes and IAM database yield results that are competitive with those of networks trained at line level, and constitute a significant step towards end-to-end transcription of full documents.

##### Abstract (translated by Google)
离线手写识别系统需要剪裁文本行图像进行训练和识别。一方面，在线层面的注释和抄本成本高昂。另一方面，自动行分割算法容易出错，影响后续的识别。在本文中，我们提出修改流行和高效的多维长期短期记忆递归神经网络（MDLSTM-RNN），以实现手写段落的端到端处理。更具体地说，我们用能够一次识别一条线的循环版本来替换将二维表示变换成一系列预测的折叠层。在所提出的模型中，神经网络通过计算图像表示上的注意权重来执行一种隐式行分割。对Rimes和IAM数据库段落的实验产生的结果与在线层面训练的网络相比具有竞争性，并且是整个文档的端到端转录的重要步骤。

##### URL
[https://arxiv.org/abs/1604.08352](https://arxiv.org/abs/1604.08352)

##### PDF
[https://arxiv.org/pdf/1604.08352](https://arxiv.org/pdf/1604.08352)

