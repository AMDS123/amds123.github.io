---
layout: post
title: "Exploring Visual Relationship for Image Captioning"
date: 2018-09-19 07:50:17
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption CNN RNN Relation
author: Ting Yao, Yingwei Pan, Yehao Li, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
It is always well believed that modeling relationships between objects would be helpful for representing and eventually describing an image. Nevertheless, there has not been evidence in support of the idea on image description generation. In this paper, we introduce a new design to explore the connections between objects for image captioning under the umbrella of attention-based encoder-decoder framework. Specifically, we present Graph Convolutional Networks plus Long Short-Term Memory (dubbed as GCN-LSTM) architecture that novelly integrates both semantic and spatial object relationships into image encoder. Technically, we build graphs over the detected objects in an image based on their spatial and semantic connections. The representations of each region proposed on objects are then refined by leveraging graph structure through GCN. With the learnt region-level features, our GCN-LSTM capitalizes on LSTM-based captioning framework with attention mechanism for sentence generation. Extensive experiments are conducted on COCO image captioning dataset, and superior results are reported when comparing to state-of-the-art approaches. More remarkably, GCN-LSTM increases CIDEr-D performance from 120.1% to 128.7% on COCO testing set.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.07041](https://arxiv.org/abs/1809.07041)

##### PDF
[https://arxiv.org/pdf/1809.07041](https://arxiv.org/pdf/1809.07041)

