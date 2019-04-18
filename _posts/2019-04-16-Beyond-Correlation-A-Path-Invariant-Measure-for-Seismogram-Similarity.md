---
layout: post
title: "Beyond Correlation: A Path-Invariant Measure for Seismogram Similarity"
date: 2019-04-16 19:22:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding CNN Detection Relation
author: Joshua Dickey, Brett Borghetti, William Junek, Richard Martin
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity search is a popular technique for seismic signal processing, with template matching, matched filters and subspace detectors being utilized for a wide variety of tasks, including both signal detection and source discrimination. Traditionally, these techniques rely on the cross-correlation function as the basis for measuring similarity. Unfortunately, seismogram correlation is dominated by path effects, essentially requiring a distinct waveform template along each path to be detected. To address this limitation, we define a path-invariant measure for seismogram similarity. A deep convolutional neural network with a triplet loss function maps raw seismograms to a low dimensional embedding space, where nearness on the space corresponds to nearness of source function, regardless of path or recording instrumentation. This path-agnostic embedding space represents a new representation for seismograms, characterized by robust, source-specific features. The dataset used to train and test the algorithm comes primarily from the USArray experiment, a temporary network of 400 seismometers that was deployed at more than 2000 locations across the US from 2007 to 2012. The first four years (2006, 2007, 2008, 2009) were selected as the training set, and the following two years (2010, 2011) were selected for validation and testing. The training, validation and test sets contained 24,811, 5,711 and 4,214 seismograms, respectively. The utility of our novel embedding space representation is evaluated across three common seismic tasks: event association, signal detection, and source discrimination, achieving an accuracy of 80%, 92% and 90%, respectively, all while minimizing the number of template waveforms required.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07936](http://arxiv.org/abs/1904.07936)

##### PDF
[http://arxiv.org/pdf/1904.07936](http://arxiv.org/pdf/1904.07936)

