---
layout: post
title: "Attentive Contexts for Object Detection"
date: 2016-03-24 02:18:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN RNN Detection
author: Jianan Li, Yunchao Wei, Xiaodan Liang, Jian Dong, Tingfa Xu, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep neural network based object detection methods typically classify candidate proposals using their interior features. However, global and local surrounding contexts that are believed to be valuable for object detection are not fully exploited by existing methods yet. In this work, we take a step towards understanding what is a robust practice to extract and utilize contextual information to facilitate object detection in practice. Specifically, we consider the following two questions: "how to identify useful global contextual information for detecting a certain object?" and "how to exploit local context surrounding a proposal for better inferring its contents?". We provide preliminary answers to these questions through developing a novel Attention to Context Convolution Neural Network (AC-CNN) based object detection model. AC-CNN effectively incorporates global and local contextual information into the region-based CNN (e.g. Fast RCNN) detection model and provides better object detection performance. It consists of one attention-based global contextualized (AGC) sub-network and one multi-scale local contextualized (MLC) sub-network. To capture global context, the AGC sub-network recurrently generates an attention map for an input image to highlight useful global contextual locations, through multiple stacked Long Short-Term Memory (LSTM) layers. For capturing surrounding local context, the MLC sub-network exploits both the inside and outside contextual information of each specific proposal at multiple scales. The global and local context are then fused together for making the final decision for detection. Extensive experiments on PASCAL VOC 2007 and VOC 2012 well demonstrate the superiority of the proposed AC-CNN over well-established baselines. In particular, AC-CNN outperforms the popular Fast-RCNN by 2.0% and 2.2% on VOC 2007 and VOC 2012 in terms of mAP, respectively.

##### Abstract (translated by Google)
基于现代深度神经网络的对象检测方法通常使用其内部特征对候选提议进行分类。然而，被认为对物体检测有价值的全局和局部的周围环境还没有被现有的方法充分利用。在这项工作中，我们迈出了一步，理解在实践中提取和利用上下文信息以促进对象检测的强大实践。具体而言，我们考虑以下两个问题：“如何识别有用的全局上下文信息来检测某个对象？和“如何利用围绕提案的地方背景来更好地推断其内容？”。我们通过开发一种基于上下文卷积神经网络（AC-CNN）的新型物体检测模型来为这些问题提供初步的答案。 AC-CNN有效地将全局和本地上下文信息结合到基于区域的CNN（例如，快速RCNN）检测模型中，并提供更好的对象检测性能。它由一个基于注意力的全球情境化（AGC）子网络和一个多尺度本地情境化（MLC）子网络组成。为了捕捉全局上下文，AGC子网络经常通过多个堆叠的长期短期存储器（LSTM）层为输入图像生成关注图，以突出有用的全局上下文位置。为了捕捉周围的本地情景，MLC子网在多个尺度上利用每个具体提议的内部和外部上下文信息。然后将全球和当地情况融合在一起，作出最终的检测决定。对PASCAL VOC 2007和VOC 2012进行的大量实验充分证明了所建议的AC-CNN优于已建立的基线的优势。特别是，AC-CNN在mAP方面分别超过了流行的Fast-RCNN 2.0％和2.2％的VOC 2007和VOC 2012。

##### URL
[https://arxiv.org/abs/1603.07415](https://arxiv.org/abs/1603.07415)

