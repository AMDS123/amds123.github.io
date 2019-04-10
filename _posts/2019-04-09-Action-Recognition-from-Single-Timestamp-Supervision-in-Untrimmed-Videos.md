---
layout: post
title: "Action Recognition from Single Timestamp Supervision in Untrimmed Videos"
date: 2019-04-09 14:11:48
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Davide Moltisanti, Sanja Fidler, Dima Damen
mathjax: true
---

* content
{:toc}

##### Abstract
Recognising actions in videos relies on labelled supervision during training, typically the start and end times of each action instance. This supervision is not only subjective, but also expensive to acquire. Weak video-level supervision has been successfully exploited for recognition in untrimmed videos, however it is challenged when the number of different actions in training videos increases. We propose a method that is supervised by single timestamps located around each action instance, in untrimmed videos. We replace expensive action bounds with sampling distributions initialised from these timestamps. We then use the classifier's response to iteratively update the sampling distributions. We demonstrate that these distributions converge to the location and extent of discriminative action segments. We evaluate our method on three datasets for fine-grained recognition, with increasing number of different actions per video, and show that single timestamps offer a reasonable compromise between recognition performance and labelling effort, performing comparably to full temporal supervision. Our update method improves top-1 test accuracy by up to 5.4%. across the evaluated datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04689](http://arxiv.org/abs/1904.04689)

##### PDF
[http://arxiv.org/pdf/1904.04689](http://arxiv.org/pdf/1904.04689)

