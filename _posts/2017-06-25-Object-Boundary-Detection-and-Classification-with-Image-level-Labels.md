---
layout: post
title: "Object Boundary Detection and Classification with Image-level Labels"
date: 2017-06-25 12:50:55
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Detection
author: Jing Yu Koh, Wojciech Samek, Klaus-Robert Müller, Alexander Binder
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic boundary and edge detection aims at simultaneously detecting object edge pixels in images and assigning class labels to them. Systematic training of predictors for this task requires the labeling of edges in images which is a particularly tedious task. We propose a novel strategy for solving this task, when pixel-level annotations are not available, performing it in an almost zero-shot manner by relying on conventional whole image neural net classifiers that were trained using large bounding boxes. Our method performs the following two steps at test time. Firstly it predicts the class labels by applying the trained whole image network to the test images. Secondly, it computes pixel-wise scores from the obtained predictions by applying backprop gradients as well as recent visualization algorithms such as deconvolution and layer-wise relevance propagation. We show that high pixel-wise scores are indicative for the location of semantic boundaries, which suggests that the semantic boundary problem can be approached without using edge labels during the training phase.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.09187](https://arxiv.org/abs/1606.09187)

##### PDF
[https://arxiv.org/pdf/1606.09187](https://arxiv.org/pdf/1606.09187)

