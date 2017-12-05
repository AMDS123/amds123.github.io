---
layout: post
title:  "Dual-Path Convolutional Image-Text Embedding"
date:   2017-12-05 11:15:19
categories: CV
tags: CV
---

* content
{:toc}

## Authros
Zhedong Zheng, Liang Zheng, Michael Garrett, Yi Yang, Yi-Dong Shen

## Date
(Submitted on 15 Nov 2017 (v1), last revised 22 Nov 2017 (this version, v2))

## Abstract
This paper considers the task of matching images and sentences. The challenge consists in discriminatively embedding the two modalities onto a shared visual-textual space. Existing work in this field largely uses Recurrent Neural Networks (RNN) for text feature learning and employs off-the-shelf Convolutional Neural Networks (CNN) for image feature extraction. Our system, in comparison, differs in two key aspects. Firstly, we build a convolutional network amenable for fine-tuning the visual and textual representations, where the entire network only contains four components, i.e., convolution layer, pooling layer, rectified linear unit function (ReLU), and batch normalisation. End-to-end learning allows the system to directly learn from the data and fully utilise the supervisions. Secondly, we propose instance loss according to viewing each multimodal data pair as a class. This works with a large margin objective to learn the inter-modal correspondence between images and their textual descriptions. Experiments on two generic retrieval datasets (Flickr30k and MSCOCO) demonstrate that our method yields competitive accuracy compared to state-of-the-art methods. Moreover, in language person retrieval, we improve the state of the art by a large margin. Code is available at this https URL com/layumi/Image-Text-Embedding



