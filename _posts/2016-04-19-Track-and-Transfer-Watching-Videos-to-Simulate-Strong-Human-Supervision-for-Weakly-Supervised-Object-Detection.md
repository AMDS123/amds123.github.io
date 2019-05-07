---
layout: post
title: "Track and Transfer: Watching Videos to Simulate Strong Human Supervision for Weakly-Supervised Object Detection"
date: 2016-04-19 22:23:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Krishna Kumar Singh, Fanyi Xiao, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
The status quo approach to training object detectors requires expensive bounding box annotations. Our framework takes a markedly different direction: we transfer tracked object boxes from weakly-labeled videos to weakly-labeled images to automatically generate pseudo ground-truth boxes, which replace manually annotated bounding boxes. We first mine discriminative regions in the weakly-labeled image collection that frequently/rarely appear in the positive/negative images. We then match those regions to videos and retrieve the corresponding tracked object boxes. Finally, we design a hough transform algorithm to vote for the best box to serve as the pseudo GT for each image, and use them to train an object detector. Together, these lead to state-of-the-art weakly-supervised detection results on the PASCAL 2007 and 2010 datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1604.05766](https://arxiv.org/abs/1604.05766)

##### PDF
[https://arxiv.org/pdf/1604.05766](https://arxiv.org/pdf/1604.05766)

