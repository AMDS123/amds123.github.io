---
layout: post
title: "MAT: A Multimodal Attentive Translator for Image Captioning"
date: 2017-08-10 14:29:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption CNN RNN
author: Chang Liu, Fuchun Sun, Changhu Wang, Feng Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we formulate the problem of image captioning as a multimodal translation task. Analogous to machine translation, we present a sequence-to-sequence recurrent neural networks (RNN) model for image caption generation. Different from most existing work where the whole image is represented by convolutional neural network (CNN) feature, we propose to represent the input image as a sequence of detected objects which feeds as the source sequence of the RNN model. In this way, the sequential representation of an image can be naturally translated to a sequence of words, as the target sequence of the RNN model. To represent the image in a sequential way, we extract the objects features in the image and arrange them in a order using convolutional neural networks. To further leverage the visual information from the encoded objects, a sequential attention layer is introduced to selectively attend to the objects that are related to generate corresponding words in the sentences. Extensive experiments are conducted to validate the proposed approach on popular benchmark dataset, i.e., MS COCO, and the proposed model surpasses the state-of-the-art methods in all metrics following the dataset splits of previous work. The proposed approach is also evaluated by the evaluation server of MS COCO captioning challenge, and achieves very competitive results, e.g., a CIDEr of 1.029 (c5) and 1.064 (c40).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.05658](https://arxiv.org/abs/1702.05658)

##### PDF
[https://arxiv.org/pdf/1702.05658](https://arxiv.org/pdf/1702.05658)

