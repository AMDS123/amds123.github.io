---
layout: post
title: "Hybrid LSTM and Encoder-Decoder Architecture for Detection of Image Forgeries"
date: 2019-03-06 17:09:46
categories: arXiv_CV
tags: arXiv_CV RNN Prediction Detection Relation
author: Jawadul H. Bappy, Cody Simons, Lakshmanan Nataraj, B.S. Manjunath, Amit K. Roy-Chowdhury
mathjax: true
---

* content
{:toc}

##### Abstract
With advanced image journaling tools, one can easily alter the semantic meaning of an image by exploiting certain manipulation techniques such as copy-clone, object splicing, and removal, which mislead the viewers. In contrast, the identification of these manipulations becomes a very challenging task as manipulated regions are not visually apparent. This paper proposes a high-confidence manipulation localization architecture which utilizes resampling features, Long-Short Term Memory (LSTM) cells, and encoder-decoder network to segment out manipulated regions from non-manipulated ones. Resampling features are used to capture artifacts like JPEG quality loss, upsampling, downsampling, rotation, and shearing. The proposed network exploits larger receptive fields (spatial maps) and frequency domain correlation to analyze the discriminative characteristics between manipulated and non-manipulated regions by incorporating encoder and LSTM network. Finally, decoder network learns the mapping from low-resolution feature maps to pixel-wise predictions for image tamper localization. With predicted mask provided by final layer (softmax) of the proposed architecture, end-to-end training is performed to learn the network parameters through back-propagation using ground-truth masks. Furthermore, a large image splicing dataset is introduced to guide the training process. The proposed method is capable of localizing image manipulations at pixel level with high precision, which is demonstrated through rigorous experimentation on three diverse datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02495](http://arxiv.org/abs/1903.02495)

##### PDF
[http://arxiv.org/pdf/1903.02495](http://arxiv.org/pdf/1903.02495)

