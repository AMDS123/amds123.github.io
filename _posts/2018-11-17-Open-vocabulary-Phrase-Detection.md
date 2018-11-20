---
layout: post
title: "Open-vocabulary Phrase Detection"
date: 2018-11-17 19:45:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Relation
author: Bryan A. Plummer, Kevin J. Shih, Yichen Li, Ke Xu, Svetlana Lazebnik, Stan Sclaroff, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing work that grounds natural language phrases in images starts with the assumption that the phrase in question is relevant to the image. In this paper we address a more realistic version of the natural language grounding task where we must both identify whether the phrase is relevant to an image and localize the phrase. This can also be viewed as a generalization of object detection to an open-ended vocabulary, essentially introducing elements of few- and zero-shot detection. We propose a Phrase R-CNN network for this task that extends Faster R-CNN to relate image regions and phrases. By carefully initializing the classification layers of our network using canonical correlation analysis (CCA), we encourage a solution that is more discerning when reasoning between similar phrases, resulting in over double the performance compared to a naive adaptation on two popular phrase grounding datasets, Flickr30K Entities and ReferIt Game, with test-time phrase vocabulary sizes of 5K and 39K, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07212](http://arxiv.org/abs/1811.07212)

##### PDF
[http://arxiv.org/pdf/1811.07212](http://arxiv.org/pdf/1811.07212)

