---
layout: post
title: "Super-pixel cloud detection using Hierarchical Fusion CNN"
date: 2018-10-19 04:37:46
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Han Liu, Dan Zeng, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Cloud detection plays a very important role in the process of remote sensing images. This paper designs a super-pixel level cloud detection method based on convolutional neural network (CNN) and deep forest. Firstly, remote sensing images are segmented into super-pixels through the combination of SLIC and SEEDS. Structured forests is carried out to compute edge probability of each pixel, based on which super-pixels are segmented more precisely. Segmented super-pixels compose a super-pixel level remote sensing database. Though cloud detection is essentially a binary classification problem, our database is labeled into four categories: thick cloud, cirrus cloud, building and other culture, to improve the generalization ability of our proposed models. Secondly, super-pixel level database is used to train our cloud detection models based on CNN and deep forest. Considering super-pixel level remote sensing images contain less semantic information compared with general object classification database, we propose a Hierarchical Fusion CNN (HFCNN). It takes full advantage of low-level features like color and texture information and is more applicable to cloud detection task. In test phase, every super-pixel in remote sensing images is classified by our proposed models and then combined to recover final binary mask by our proposed distance metric, which is used to determine ambiguous super-pixels. Experimental results show that, compared with conventional methods, HFCNN can achieve better precision and recall.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08352](http://arxiv.org/abs/1810.08352)

##### PDF
[http://arxiv.org/pdf/1810.08352](http://arxiv.org/pdf/1810.08352)

