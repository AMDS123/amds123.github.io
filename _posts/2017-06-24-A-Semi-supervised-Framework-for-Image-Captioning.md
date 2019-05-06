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


##### URL
[https://arxiv.org/abs/1611.05321](https://arxiv.org/abs/1611.05321)

##### PDF
[https://arxiv.org/pdf/1611.05321](https://arxiv.org/pdf/1611.05321)

