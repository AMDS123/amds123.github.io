---
layout: post
title: 'A Semi-supervised Framework for Image Captioning'
date: 2017-06-24 08:24:44
categories: arXiv_CV
tags: arXiv_CV Image_Caption Review Caption
author: Wenhu Chen, Aurelien Lucchi, Thomas Hofmann
---

* content
{:toc}

##### Abstract
State-of-the-art approaches for image captioning require supervised training data consisting of captions with paired image data. These methods are typically unable to use unsupervised data such as textual data with no corresponding images, which is a much more abundant commodity. We here propose a novel way of using such textual data by artificially generating missing visual information. We evaluate this learning approach on a newly designed model that detects visual concepts present in an image and feed them to a reviewer-decoder architecture with an attention mechanism. Unlike previous approaches that encode visual concepts using word embeddings, we instead suggest using regional image features which capture more intrinsic information. The main benefit of this architecture is that it synthesizes meaningful thought vectors that capture salient image properties and then applies a soft attentive decoder to decode the thought vectors and generate image captions. We evaluate our model on both Microsoft COCO and Flickr30K datasets and demonstrate that this model combined with our semi-supervised learning method can largely improve performance and help the model to generate more accurate and diverse captions.

##### Abstract (translated by Google)
用于图像字幕的最新方法需要由带有成对图像数据的字幕组成的监督训练数据。这些方法通常不能使用无监督的数据，如没有相应图像的文本数据，这是一种更为丰富的商品。我们在这里提出了一种通过人为地生成缺失的视觉信息来使用这种文本数据的新颖方式。我们在新设计的模型上评估这种学习方法，该模型检测图像中存在的视觉概念并将其提供给具有注意机制的审阅者 - 解码器体系结构。与以前使用词嵌入来编码视觉概念的方法不同，我们建议使用捕获更多内在信息的区域图像特征。这种体系结构的主要优点在于它综合了有意义的思想向量，捕捉突出的图像属性，然后应用软注意解码器来解码思想向量并生成图像标题。我们在Microsoft COCO和Flickr30K数据集上评估我们的模型，并证明这个模型结合我们的半监督学习方法可以大大提高性能，并帮助模型生成更准确和多样的标题。

##### URL
[https://arxiv.org/abs/1611.05321](https://arxiv.org/abs/1611.05321)

