---
layout: post
title: "Weakly Supervised Salient Object Detection Using Image Labels"
date: 2018-03-17 13:40:00
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Weakly_Supervised CNN Classification Deep_Learning Detection
author: Guanbin Li, Yuan Xie, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based salient object detection has recently achieved great success with its performance greatly outperforms any other unsupervised methods. However, annotating per-pixel saliency masks is a tedious and inefficient procedure. In this paper, we note that superior salient object detection can be obtained by iteratively mining and correcting the labeling ambiguity on saliency maps from traditional unsupervised methods. We propose to use the combination of a coarse salient object activation map from the classification network and saliency maps generated from unsupervised methods as pixel-level annotation, and develop a simple yet very effective algorithm to train fully convolutional networks for salient object detection supervised by these noisy annotations. Our algorithm is based on alternately exploiting a graphical model and training a fully convolutional network for model updating. The graphical model corrects the internal labeling ambiguity through spatial consistency and structure preserving while the fully convolutional network helps to correct the cross-image semantic ambiguity and simultaneously update the coarse activation map for next iteration. Experimental results demonstrate that our proposed method greatly outperforms all state-of-the-art unsupervised saliency detection methods and can be comparable to the current best strongly-supervised methods training with thousands of pixel-level saliency map annotations on all public benchmarks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.06503](https://arxiv.org/abs/1803.06503)

##### PDF
[https://arxiv.org/pdf/1803.06503](https://arxiv.org/pdf/1803.06503)

