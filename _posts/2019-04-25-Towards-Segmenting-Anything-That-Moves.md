---
layout: post
title: "Towards Segmenting Anything That Moves"
date: 2019-04-25 20:18:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection Recognition
author: Achal Dave, Pavel Tokmakov, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
For many applications such as action detection or robotic interaction, segmenting all moving objects is a crucial first step. While this problem has been well-studied under the formulation of spatiotemporal video segmentation, virtually none of the prior works use learning-based approaches, despite significant advances in single-frame instance segmentation. We propose the first deep-learning based approach for spatio-temporal grouping. Our model extends the state-of-the-art Mask R-CNN architecture to the video domain. It takes a video frame together with its optical flow as input, and passes them through appearance and motion streams respectively. It then combines the motion cues, which provide a bottom-up signal for object detection, with appearance cues that allow capturing the full extent of the object via a joint RPN module. We show state-of-the-art results on the Freiburg Berkeley Motion Segmentation dataset by a wide margin. One potential worry with learning-based methods is that they might overfit to the particular type of objects that they have been trained on. While current recognition systems tend to be limited to a "closed world" of N objects on which they are trained, our model can segment almost anything that moves.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03715](http://arxiv.org/abs/1902.03715)

##### PDF
[http://arxiv.org/pdf/1902.03715](http://arxiv.org/pdf/1902.03715)

