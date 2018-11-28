---
layout: post
title: "Learning to detect dysarthria from raw speech"
date: 2018-11-27 16:51:39
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Classification Detection Recognition
author: Juliette Millet, Neil Zeghidour
mathjax: true
---

* content
{:toc}

##### Abstract
Speech classifiers of paralinguistic traits traditionally learn from diverse hand-crafted low-level features, by selecting the relevant information for the task at hand. We explore an alternative to this selection, by learning jointly the classifier, and the feature extraction. Recent work on speech recognition has shown improved performance over speech features by learning from the waveform. We extend this approach to paralinguistic classification and propose a neural network that can learn a filterbank, a normalization factor and a compression power from the raw speech, jointly with the rest of the architecture. We apply this model to dysarthria detection from sentence-level audio recordings. Starting from a strong attention-based baseline on which mel-filterbanks outperform standard low-level descriptors, we show that learning the filters or the normalization and compression improves over fixed features by 10% absolute accuracy. We also observe a gain over OpenSmile features by learning jointly the feature extraction, the normalization, and the compression factor with the architecture. This constitutes a first attempt at learning jointly all these operations from raw audio for a speech classification task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11101](http://arxiv.org/abs/1811.11101)

##### PDF
[http://arxiv.org/pdf/1811.11101](http://arxiv.org/pdf/1811.11101)

