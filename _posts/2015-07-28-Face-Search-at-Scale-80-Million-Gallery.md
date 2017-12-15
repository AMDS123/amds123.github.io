---
layout: post
title: "Face Search at Scale: 80 Million Gallery"
date: 2015-07-28 22:09:17
categories: arXiv_CV
tags: arXiv_CV Face CNN Recognition Face_Recognition
author: Dayong Wang, Charles Otto, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the prevalence of social media websites, one challenge facing computer vision researchers is to devise methods to process and search for persons of interest among the billions of shared photos on these websites. Facebook revealed in a 2013 white paper that its users have uploaded more than 250 billion photos, and are uploading 350 million new photos each day. Due to this humongous amount of data, large-scale face search for mining web images is both important and challenging. Despite significant progress in face recognition, searching a large collection of unconstrained face images has not been adequately addressed. To address this challenge, we propose a face search system which combines a fast search procedure, coupled with a state-of-the-art commercial off the shelf (COTS) matcher, in a cascaded framework. Given a probe face, we first filter the large gallery of photos to find the top-k most similar faces using deep features generated from a convolutional neural network. The k candidates are re-ranked by combining similarities from deep features and the COTS matcher. We evaluate the proposed face search system on a gallery containing 80 million web-downloaded face images. Experimental results demonstrate that the deep features are competitive with state-of-the-art methods on unconstrained face recognition benchmarks (LFW and IJB-A). Further, the proposed face search system offers an excellent trade-off between accuracy and scalability on datasets consisting of millions of images. Additionally, in an experiment involving searching for face images of the Tsarnaev brothers, convicted of the Boston Marathon bombing, the proposed face search system could find the younger brother's (Dzhokhar Tsarnaev) photo at rank 1 in 1 second on a 5M gallery and at rank 8 in 7 seconds on an 80M gallery.

##### Abstract (translated by Google)
由于社交媒体网站的流行，计算机视觉研究者面临的一个挑战是设计处理和搜索这些网站上数十亿共享照片中感兴趣的人的方法。 Facebook在2013年白皮书中透露，其用户已经上传了超过2500亿张照片，并且每天上传3.5亿张新照片。由于这样大量的数据，大规模人脸搜索网页图像既重要又具有挑战性。尽管在人脸识别方面取得了重大进展，但搜索大量无约束的人脸图像还没有得到充分的解决。为了解决这个挑战，我们提出了一个面部搜索系统，它结合了一个快速搜索程序，加上一个现成的商业现货（COTS）匹配器，在一个级联的框架中。给定一个探测面，我们首先通过使用由卷积神经网络生成的深度特征来过滤大型照片库，以找到最前k个最相似的面部。 k个候选者通过结合来自深度特征和COTS匹配器的相似性而被重新排序。我们在包含8000万个网络下载的人脸图像的画廊上评估所提议的人脸搜索系统。实验结果证明，深度特征与无约束的人脸识别基准（LFW和IJB-A）上的最新方法相比是有竞争力的。此外，所提出的人脸搜索系统在由数百万图像组成的数据集上提供精确性和可伸缩性之间的良好折衷。此外，在一次涉及查尔斯·沙尔夫（Tsarnaev）兄弟脸部图像的实验中，被波士顿马拉松（Boston Marathon）爆炸案定罪，提议的脸部搜索系统可以在5M长廊上以1秒1的等级找到弟弟（Dzhokhar Tsarnaev）在一个80M画廊的7秒内完成8个。

##### URL
[https://arxiv.org/abs/1507.07242](https://arxiv.org/abs/1507.07242)

##### PDF
[https://arxiv.org/pdf/1507.07242](https://arxiv.org/pdf/1507.07242)

