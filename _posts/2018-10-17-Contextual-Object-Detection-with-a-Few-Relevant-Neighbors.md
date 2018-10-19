---
layout: post
title: "Contextual Object Detection with a Few Relevant Neighbors"
date: 2018-10-17 21:51:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection Relation
author: Ehud Barnea, Ohad Ben-Shahar
mathjax: true
---

* content
{:toc}

##### Abstract
A natural way to improve the detection of objects is to consider the contextual constraints imposed by the detection of additional objects in a given scene. In this work, we exploit the spatial relations between objects in order to improve detection capacity, as well as analyze various properties of the contextual object detection problem. To precisely calculate context-based probabilities of objects, we developed a model that examines the interactions between objects in an exact probabilistic setting, in contrast to previous methods that typically utilize approximations based on pairwise interactions. Such a scheme is facilitated by the realistic assumption that the existence of an object in any given location is influenced by only few informative locations in space. Based on this assumption, we suggest a method for identifying these relevant locations and integrating them into a mostly exact calculation of probability based on their raw detector responses. This scheme is shown to improve detection results and provides unique insights about the process of contextual inference for object detection. We show that it is generally difficult to learn that a particular object reduces the probability of another, and that in cases when the context and detector strongly disagree this learning becomes virtually impossible for the purposes of improving the results of an object detector. Finally, we demonstrate improved detection results through use of our approach as applied to the PASCAL VOC and COCO datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.05705](http://arxiv.org/abs/1711.05705)

##### PDF
[http://arxiv.org/pdf/1711.05705](http://arxiv.org/pdf/1711.05705)

