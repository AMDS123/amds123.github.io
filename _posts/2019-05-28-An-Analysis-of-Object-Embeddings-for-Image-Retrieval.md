---
layout: post
title: "An Analysis of Object Embeddings for Image Retrieval"
date: 2019-05-28 16:02:51
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Salient Object_Detection Segmentation Attention Embedding CNN Image_Classification Classification Detection
author: Bor-Chun Chen, Larry S. Davis, Ser-Nam Lim
mathjax: true
---

* content
{:toc}

##### Abstract
We present an analysis of embeddings extracted from different pre-trained models for content-based image retrieval. Specifically, we study embeddings from image classification and object detection models. We discover that even with additional human annotations such as bounding boxes and segmentation masks, the discriminative power of the embeddings based on modern object detection models is significantly worse than their classification counterparts for the retrieval task. At the same time, our analysis also unearths that object detection model can help retrieval task by acting as a hard attention module for extracting object embeddings that focus on salient region from the convolutional feature map. In order to efficiently extract object embeddings, we introduce a simple guided student-teacher training paradigm for learning discriminative embeddings within the object detection framework. We support our findings with strong experimental results.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11903](https://arxiv.org/abs/1905.11903)

##### PDF
[https://arxiv.org/pdf/1905.11903](https://arxiv.org/pdf/1905.11903)

