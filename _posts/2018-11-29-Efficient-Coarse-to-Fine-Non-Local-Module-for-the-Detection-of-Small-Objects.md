---
layout: post
title: "Efficient Coarse-to-Fine Non-Local Module for the Detection of Small Objects"
date: 2018-11-29 14:09:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Relation
author: Hila Levi, Shimon Ullman
mathjax: true
---

* content
{:toc}

##### Abstract
An image is not just a collection of objects, but rather a graph where each object is related to other objects through spatial and semantic relations. Using relational reasoning modules, allowing message passing between objects, can therefore improve object detection. Current schemes apply such dedicated modules either on a specific layer of the bottom-up stream, or between already-detected objects. We show that the relational process can be better modeled in a coarse to fine manner and present a novel framework, applying a non-local module sequentially to increasing resolution feature-maps along the top-down stream. In this way, the inner relational process can naturally pass information from larger objects to smaller related ones. Applying the modules to fine feature-maps also allows message passing between the small objects themselves, exploiting repetitions of instances from of the same class. In practice, due to the expensive memory utilization of the non-local module, it is unfeasible to apply the module as currently used to high-resolution feature-maps. We efficiently redesigned the non local module, improved it in terms of memory and number of operations, allowing it to be placed anywhere along the network. We also incorporated relative spatial information into the module, in a manner that can be incorporated into our efficient implementation. We show the effectiveness of our scheme by improving the results of detecting small objects on COCO by 1.5 AP over Faster RCNN and by 1 AP over using non-local module on the bottom-up stream.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12152](http://arxiv.org/abs/1811.12152)

##### PDF
[http://arxiv.org/pdf/1811.12152](http://arxiv.org/pdf/1811.12152)

