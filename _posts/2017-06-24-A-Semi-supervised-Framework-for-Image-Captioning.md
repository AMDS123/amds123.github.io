---
layout: post
title: "A Semi-supervised Framework for Image Captioning"
date: 2017-06-24 08:24:44
categories: arXiv_CV
tags: arXiv_CV Image_Caption Salient Review Attention Caption Embedding
author: Wenhu Chen, Aurelien Lucchi, Thomas Hofmann
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art approaches for image captioning require supervised training data consisting of captions with paired image data. These methods are typically unable to use unsupervised data such as textual data with no corresponding images, which is a much more abundant commodity. We here propose a novel way of using such textual data by artificially generating missing visual information. We evaluate this learning approach on a newly designed model that detects visual concepts present in an image and feed them to a reviewer-decoder architecture with an attention mechanism. Unlike previous approaches that encode visual concepts using word embeddings, we instead suggest using regional image features which capture more intrinsic information. The main benefit of this architecture is that it synthesizes meaningful thought vectors that capture salient image properties and then applies a soft attentive decoder to decode the thought vectors and generate image captions. We evaluate our model on both Microsoft COCO and Flickr30K datasets and demonstrate that this model combined with our semi-supervised learning method can largely improve performance and help the model to generate more accurate and diverse captions.

##### Abstract (translated by Google)
用于图像字幕的最先进方法需要受监督的训练数据，该数据由具有成对图像数据的字幕组成。这些方法通常不能使用无监督数据，例如没有相应图像的文本数据，这是一种更丰富的商品。我们在这里提出了一种通过人工生成缺失的视觉信息来使用这种文本数据的新方法。我们在新设计的模型上评估这种学习方法，该模型检测图像中存在的视觉概念，并将其提供给具有注意机制的评论者 - 解码器架构。与以前使用单词嵌入编码视觉概念的方法不同，我们建议使用捕获更多内在信息的区域图像特征。这种架构的主要好处是它可以合成有意义的思维向量，捕获显着的图像属性，然后应用软的细心解码器来解码思想向量并生成图像标题。我们在Microsoft COCO和Flickr30K数据集上评估我们的模型，并证明该模型与我们的半监督学习方法相结合可以在很大程度上提高性能并帮助模型生成更准确和多样化的标题。

##### URL
[https://arxiv.org/abs/1611.05321](https://arxiv.org/abs/1611.05321)

##### PDF
[https://arxiv.org/pdf/1611.05321](https://arxiv.org/pdf/1611.05321)

