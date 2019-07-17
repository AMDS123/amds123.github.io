---
layout: post
title: "The Bach Doodle: Approachable music composition with machine learning at scale"
date: 2019-07-14 23:39:12
categories: arXiv_SD
tags: arXiv_SD Face
author: Cheng-Zhi Anna Huang, Curtis Hawthorne, Adam Roberts, Monica Dinculescu, James Wexler, Leon Hong, Jacob Howcroft
mathjax: true
---

* content
{:toc}

##### Abstract
To make music composition more approachable, we designed the first AI-powered Google Doodle, the Bach Doodle, where users can create their own melody and have it harmonized by a machine learning model Coconet (Huang et al., 2017) in the style of Bach. For users to input melodies, we designed a simplified sheet-music based interface. To support an interactive experience at scale, we re-implemented Coconet in TensorFlow.js (Smilkov et al., 2019) to run in the browser and reduced its runtime from 40s to 2s by adopting dilated depth-wise separable convolutions and fusing operations. We also reduced the model download size to approximately 400KB through post-training weight quantization. We calibrated a speed test based on partial model evaluation time to determine if the harmonization request should be performed locally or sent to remote TPU servers. In three days, people spent 350 years worth of time playing with the Bach Doodle, and Coconet received more than 55 million queries. Users could choose to rate their compositions and contribute them to a public dataset, which we are releasing with this paper. We hope that the community finds this dataset useful for applications ranging from ethnomusicological studies, to music education, to improving machine learning models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06637](http://arxiv.org/abs/1907.06637)

##### PDF
[http://arxiv.org/pdf/1907.06637](http://arxiv.org/pdf/1907.06637)

