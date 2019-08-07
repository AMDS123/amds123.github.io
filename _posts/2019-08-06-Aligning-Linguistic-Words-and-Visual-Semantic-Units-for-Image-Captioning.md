---
layout: post
title: "Aligning Linguistic Words and Visual Semantic Units for Image Captioning"
date: 2019-08-06 13:19:24
categories: arXiv_CL
tags: arXiv_CL Image_Caption Attention Caption Embedding CNN
author: Longteng Guo, Jing Liu, Jinhui Tang, Jiangwei Li, Wei Luo, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning attempts to generate a sentence composed of several linguistic words, which are used to describe objects, attributes, and interactions in an image, denoted as visual semantic units in this paper. Based on this view, we propose to explicitly model the object interactions in semantics and geometry based on Graph Convolutional Networks (GCNs), and fully exploit the alignment between linguistic words and visual semantic units for image captioning. Particularly, we construct a semantic graph and a geometry graph, where each node corresponds to a visual semantic unit, i.e., an object, an attribute, or a semantic (geometrical) interaction between two objects. Accordingly, the semantic (geometrical) context-aware embeddings for each unit are obtained through the corresponding GCN learning processers. At each time step, a context gated attention module takes as inputs the embeddings of the visual semantic units and hierarchically align the current word with these units by first deciding which type of visual semantic unit (object, attribute, or interaction) the current word is about, and then finding the most correlated visual semantic units under this type. Extensive experiments are conducted on the challenging MS-COCO image captioning dataset, and superior results are reported when comparing to state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.02127](https://arxiv.org/abs/1908.02127)

##### PDF
[https://arxiv.org/pdf/1908.02127](https://arxiv.org/pdf/1908.02127)

