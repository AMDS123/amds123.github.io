---
layout: post
title: "Attentive Contexts for Object Detection"
date: 2016-03-24 02:18:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN RNN Detection
author: Jianan Li, Yunchao Wei, Xiaodan Liang, Jian Dong, Tingfa Xu, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep neural network based object detection methods typically classify candidate proposals using their interior features. However, global and local surrounding contexts that are believed to be valuable for object detection are not fully exploited by existing methods yet. In this work, we take a step towards understanding what is a robust practice to extract and utilize contextual information to facilitate object detection in practice. Specifically, we consider the following two questions: "how to identify useful global contextual information for detecting a certain object?" and "how to exploit local context surrounding a proposal for better inferring its contents?". We provide preliminary answers to these questions through developing a novel Attention to Context Convolution Neural Network (AC-CNN) based object detection model. AC-CNN effectively incorporates global and local contextual information into the region-based CNN (e.g. Fast RCNN) detection model and provides better object detection performance. It consists of one attention-based global contextualized (AGC) sub-network and one multi-scale local contextualized (MLC) sub-network. To capture global context, the AGC sub-network recurrently generates an attention map for an input image to highlight useful global contextual locations, through multiple stacked Long Short-Term Memory (LSTM) layers. For capturing surrounding local context, the MLC sub-network exploits both the inside and outside contextual information of each specific proposal at multiple scales. The global and local context are then fused together for making the final decision for detection. Extensive experiments on PASCAL VOC 2007 and VOC 2012 well demonstrate the superiority of the proposed AC-CNN over well-established baselines. In particular, AC-CNN outperforms the popular Fast-RCNN by 2.0% and 2.2% on VOC 2007 and VOC 2012 in terms of mAP, respectively.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1603.07415](https://arxiv.org/abs/1603.07415)

##### PDF
[https://arxiv.org/pdf/1603.07415](https://arxiv.org/pdf/1603.07415)

