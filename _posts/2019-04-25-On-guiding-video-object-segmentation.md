---
layout: post
title: "On guiding video object segmentation"
date: 2019-04-25 11:03:16
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN
author: Diego Ortego, Kevin McGuinness, Juan C. SanMiguel, Eric Arazo, Jos&#xe9; M. Mart&#xed;nez, Noel E. O&#x27;Connor
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel approach for segmenting moving objects in unconstrained environments using guided convolutional neural networks. This guiding process relies on foreground masks from independent algorithms (i.e. state-of-the-art algorithms) to implement an attention mechanism that incorporates the spatial location of foreground and background to compute their separated representations. Our approach initially extracts two kinds of features for each frame using colour and optical flow information. Such features are combined following a multiplicative scheme to benefit from their complementarity. These unified colour and motion features are later processed to obtain the separated foreground and background representations. Then, both independent representations are concatenated and decoded to perform foreground segmentation. Experiments conducted on the challenging DAVIS 2016 dataset demonstrate that our guided representations not only outperform non-guided, but also recent and top-performing video object segmentation algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11256](http://arxiv.org/abs/1904.11256)

##### PDF
[http://arxiv.org/pdf/1904.11256](http://arxiv.org/pdf/1904.11256)

