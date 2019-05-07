---
layout: post
title: "Learning Sampling Distributions for Efficient Object Detection"
date: 2015-11-02 12:52:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Face Detection Face_Detection
author: Yanwei Pang, Jiale Cao, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is an important task in computer vision and learning systems. Multistage particle windows (MPW), proposed by Gualdi et al., is an algorithm of fast and accurate object detection. By sampling particle windows from a proposal distribution (PD), MPW avoids exhaustively scanning the image. Despite its success, it is unknown how to determine the number of stages and the number of particle windows in each stage. Moreover, it has to generate too many particle windows in the initialization step and it redraws unnecessary too many particle windows around object-like regions. In this paper, we attempt to solve the problems of MPW. An important fact we used is that there is large probability for a randomly generated particle window not to contain the object because the object is a sparse event relevant to the huge number of candidate windows. Therefore, we design the proposal distribution so as to efficiently reject the huge number of non-object windows. Specifically, we propose the concepts of rejection, acceptance, and ambiguity windows and regions. This contrasts to MPW which utilizes only on region of support. The PD of MPW is acceptance-oriented whereas the PD of our method (called iPW) is rejection-oriented. Experimental results on human and face detection demonstrate the efficiency and effectiveness of the iPW algorithm. The source code is publicly accessible.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1508.05581](https://arxiv.org/abs/1508.05581)

##### PDF
[https://arxiv.org/pdf/1508.05581](https://arxiv.org/pdf/1508.05581)

