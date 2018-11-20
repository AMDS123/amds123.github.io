---
layout: post
title: "Data-Efficient Graph Embedding Learning for PCB Component Detection"
date: 2018-11-16 19:07:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Embedding Deep_Learning Prediction Detection
author: Chia-Wen Kuo, Jacob Ashmore, David Huggins, Zsolt Kira
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a challenging computer vision task, namely the detection of generic components on a PCB, and a novel set of deep-learning methods that are able to jointly leverage the appearance of individual components and the propagation of information across the structure of the board to accurately detect and identify various types of components on a PCB. Due to the expense of manual data labeling, a highly unbalanced distribution of component types, and significant domain shift across boards, most earlier attempts based on traditional image processing techniques fail to generalize well to PCB images with various quality, lighting conditions, etc. Newer object detection pipelines such as Faster R-CNN, on the other hand, require a large amount of labeled data, do not deal with domain shift, and do not leverage structure. To address these issues, we propose a three stage pipeline in which a class-agnostic region proposal network is followed by a low-shot similarity prediction classifier. In order to exploit the data dependency within a PCB, we design a novel Graph Network block to refine the component features conditioned on each PCB. To the best of our knowledge, this is one of the earliest attempts to train a deep learning based model for such tasks, and we demonstrate improvements over recent graph networks for this task. We also provide in-depth analysis and discussion for this challenging task, pointing to future research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06994](http://arxiv.org/abs/1811.06994)

##### PDF
[http://arxiv.org/pdf/1811.06994](http://arxiv.org/pdf/1811.06994)

