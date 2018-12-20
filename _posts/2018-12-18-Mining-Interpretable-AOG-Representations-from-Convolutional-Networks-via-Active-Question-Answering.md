---
layout: post
title: "Mining Interpretable AOG Representations from Convolutional Networks via Active Question Answering"
date: 2018-12-18 05:49:36
categories: arXiv_CV
tags: arXiv_CV QA GAN CNN
author: Quanshi Zhang, Ruiming Cao, Ying Nian Wu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a method to mine object-part patterns from conv-layers of a pre-trained convolutional neural network (CNN). The mined object-part patterns are organized by an And-Or graph (AOG). This interpretable AOG representation consists of a four-layer semantic hierarchy, i.e., semantic parts, part templates, latent patterns, and neural units. The AOG associates each object part with certain neural units in feature maps of conv-layers. The AOG is constructed in a weakly-supervised manner, i.e., very few annotations (e.g., 3-20) of object parts are used to guide the learning of AOGs. We develop a question-answering (QA) method that uses active human-computer communications to mine patterns from a pre-trained CNN, in order to incrementally explain more features in conv-layers. During the learning process, our QA method uses the current AOG for part localization. The QA method actively identifies objects, whose feature maps cannot be explained by the AOG. Then, our method asks people to annotate parts on the unexplained objects, and uses answers to discover CNN patterns corresponding to the newly labeled parts. In this way, our method gradually grows new branches and refines existing branches on the AOG to semanticize CNN representations. In experiments, our method exhibited a high learning efficiency. Our method used about 1/6-1/3 of the part annotations for training, but achieved similar or better part-localization performance than fast-RCNN methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07996](http://arxiv.org/abs/1812.07996)

##### PDF
[http://arxiv.org/pdf/1812.07996](http://arxiv.org/pdf/1812.07996)

