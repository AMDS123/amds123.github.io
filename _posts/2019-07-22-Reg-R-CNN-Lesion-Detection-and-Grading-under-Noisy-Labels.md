---
layout: post
title: "Reg R-CNN: Lesion Detection and Grading under Noisy Labels"
date: 2019-07-22 10:16:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Relation
author: Gregor N. Ramien, Paul F. Jaeger, Simon A. A. Kohl, Klaus H. Maier-Hein
mathjax: true
---

* content
{:toc}

##### Abstract
For the task of concurrently detecting and categorizing objects, the medical imaging community commonly adopts methods developed on natural images. Current state-of-the-art object detectors are comprised of two stages: the first stage generates region proposals, the second stage subsequently categorizes them. Unlike in natural images, however, for anatomical structures of interest such as tumors, the appearance in the image (e.g., scale or intensity) links to a malignancy grade that lies on a continuous ordinal scale. While classification models discard this ordinal relation between grades by discretizing the continuous scale to an unordered "bag of categories", regression models are trained with distance metrics, which preserve the relation. This advantage becomes all the more important in the setting of label confusions on ambiguous data sets, which is the usual case with medical images. To this end, we propose Reg R-CNN, which replaces the second-stage classification model of a current object detector with a regression model. We show the superiority of our approach on a public data set with 1026 patients and a series of toy experiments. Code will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12915](http://arxiv.org/abs/1907.12915)

##### PDF
[http://arxiv.org/pdf/1907.12915](http://arxiv.org/pdf/1907.12915)

