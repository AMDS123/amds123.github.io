---
layout: post
title: "Lucid Data Dreaming for Video Object Segmentation"
date: 2019-02-03 16:34:23
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN
author: Anna Khoreva, Rodrigo Benenson, Eddy Ilg, Thomas Brox, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional networks reach top quality in pixel-level video object segmentation but require a large amount of training data (1k~100k) to deliver such results. We propose a new training strategy which achieves state-of-the-art results across three evaluation datasets while using 20x~1000x less annotated data than competing methods. Our approach is suitable for both single and multiple object segmentation. Instead of using large training sets hoping to generalize across domains, we generate in-domain training data using the provided annotation on the first frame of each video to synthesize ("lucid dream") plausible future video frames. In-domain per-video training data allows us to train high quality appearance- and motion-based models, as well as tune the post-processing stage. This approach allows to reach competitive results even when training from only a single annotated frame, without ImageNet pre-training. Our results indicate that using a larger training set is not automatically better, and that for the video object segmentation task a smaller training set that is closer to the target domain is more effective. This changes the mindset regarding how many training samples and general "objectness" knowledge are required for the video object segmentation task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1703.09554](http://arxiv.org/abs/1703.09554)

##### PDF
[http://arxiv.org/pdf/1703.09554](http://arxiv.org/pdf/1703.09554)

