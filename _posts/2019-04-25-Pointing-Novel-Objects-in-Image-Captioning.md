---
layout: post
title: "Pointing Novel Objects in Image Captioning"
date: 2019-04-25 10:22:35
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge Attention Caption RNN Recognition
author: Yehao Li, Ting Yao, Yingwei Pan, Hongyang Chao, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning has received significant attention with remarkable improvements in recent advances. Nevertheless, images in the wild encapsulate rich knowledge and cannot be sufficiently described with models built on image-caption pairs containing only in-domain objects. In this paper, we propose to address the problem by augmenting standard deep captioning architectures with object learners. Specifically, we present Long Short-Term Memory with Pointing (LSTM-P) --- a new architecture that facilitates vocabulary expansion and produces novel objects via pointing mechanism. Technically, object learners are initially pre-trained on available object recognition data. Pointing in LSTM-P then balances the probability between generating a word through LSTM and copying a word from the recognized objects at each time step in decoder stage. Furthermore, our captioning encourages global coverage of objects in the sentence. Extensive experiments are conducted on both held-out COCO image captioning and ImageNet datasets for describing novel objects, and superior results are reported when comparing to state-of-the-art approaches. More remarkably, we obtain an average of 60.9% in F1 score on held-out COCO~dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11251](http://arxiv.org/abs/1904.11251)

##### PDF
[http://arxiv.org/pdf/1904.11251](http://arxiv.org/pdf/1904.11251)

