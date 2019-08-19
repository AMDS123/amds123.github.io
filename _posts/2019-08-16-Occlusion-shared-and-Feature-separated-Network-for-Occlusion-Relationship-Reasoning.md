---
layout: post
title: "Occlusion-shared and Feature-separated Network for Occlusion Relationship Reasoning"
date: 2019-08-16 09:09:50
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Rui Lu, Feng Xue, Menghan Zhou, Anlong Ming, Yu Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Occlusion relationship reasoning demands closed contour to express the object, and orientation of each contour pixel to describe the order relationship between objects. Current CNN-based methods neglect two critical issues of the task: (1) simultaneous existence of the relevance and distinction for the two elements, i.e, occlusion edge and occlusion orientation; and (2) inadequate exploration to the orientation features. For the reasons above, we propose the Occlusion-shared and Feature-separated Network (OFNet). On one hand, considering the relevance between edge and orientation, two sub-networks are designed to share the occlusion cue. On the other hand, the whole network is split into two paths to learn the high-level semantic features separately. Moreover, a contextual feature for orientation prediction is extracted, which represents the bilateral cue of the foreground and background areas. The bilateral cue is then fused with the occlusion cue to precisely locate the object regions. Finally, a stripe convolution is designed to further aggregate features from surrounding scenes of the occlusion edge. The proposed OFNet remarkably advances the state-of-the-art approaches on PIOD and BSDS ownership dataset. The source code is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05898](https://arxiv.org/abs/1908.05898)

##### PDF
[https://arxiv.org/pdf/1908.05898](https://arxiv.org/pdf/1908.05898)

