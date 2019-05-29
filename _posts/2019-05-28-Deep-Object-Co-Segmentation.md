---
layout: post
title: "Deep Object Co-Segmentation"
date: 2019-05-28 17:05:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Relation
author: Weihao Li, Omid Hosseini Jafari, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a deep object co-segmentation (DOCS) approach for segmenting common objects of the same class within a pair of images. This means that the method learns to ignore common, or uncommon, background stuff and focuses on objects. If multiple object classes are presented in the image pair, they are jointly extracted as foreground. To address this task, we propose a CNN-based Siamese encoder-decoder architecture. The encoder extracts high-level semantic features of the foreground objects, a mutual correlation layer detects the common objects, and finally, the decoder generates the output foreground masks for each image. To train our model, we compile a large object co-segmentation dataset consisting of image pairs from the PASCAL VOC dataset with common objects masks. We evaluate our approach on commonly used datasets for co-segmentation tasks and observe that our approach consistently outperforms competing methods, for both seen and unseen object classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.06423](http://arxiv.org/abs/1804.06423)

##### PDF
[http://arxiv.org/pdf/1804.06423](http://arxiv.org/pdf/1804.06423)

