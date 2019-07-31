---
layout: post
title: "Towards Pure End-to-End Learning for Recognizing Multiple Text Sequences from an Image"
date: 2019-07-30 09:07:28
categories: arXiv_CV
tags: arXiv_CV Attention Recognition
author: Xu Zhenlong, Zhou shuigeng, Cheng zhanzhan, Bai fan, Niu yi, Pu shiliang
mathjax: true
---

* content
{:toc}

##### Abstract
Here we address a challenging problem: recognizing multiple text sequences from an image by pure end-to-end learning. It is twofold: 1) Multiple text sequences recognition. Each image may contain multiple text sequences of different content, location and orientation, and we try to recognize all the text sequences contained in the image. 2) Pure end-to-end (PEE) learning.We solve the problem in a pure end-to-end learning way where each training image is labeled by only text transcripts of all contained sequences, without any geometric annotations. Most existing works recognize multiple text sequences from an image in a non-end-to-end (NEE) or quasi-end-to-end (QEE) way, in which each image is trained with both text transcripts and text locations.Only recently, a PEE method was proposed to recognize text sequences from an image where the text sequence was split to several lines in the image. However, it cannot be directly applied to recognizing multiple text sequences from an image. So in this paper, we propose a pure end-to-end learning method to recognize multiple text sequences from an image. Our method directly learns multiple sequences of probability distribution conditioned on each input image, and outputs multiple text transcripts with a well-designed decoding strategy.To evaluate the proposed method, we constructed several datasets mainly based on an existing public dataset andtwo real application scenarios. Experimental results show that the proposed method can effectively recognize multiple text sequences from images, and outperforms CTC-based and attention-based baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12791](http://arxiv.org/abs/1907.12791)

##### PDF
[http://arxiv.org/pdf/1907.12791](http://arxiv.org/pdf/1907.12791)

