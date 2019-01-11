---
layout: post
title: "Polyphonic Pitch Tracking with Deep Layered Learning"
date: 2019-01-10 18:08:56
categories: arXiv_SD
tags: arXiv_SD Sparse Tracking Detection
author: Anders Elowsson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a polyphonic pitch tracking system able to extract both framewise and note-based estimates from audio. The system uses several artificial neural networks in a deep layered learning setup. First, cascading networks are applied to a spectrogram for framewise fundamental frequency (f0) estimation. A sparse receptive field is learned by the first network and then used as a filter kernel for parameter sharing throughout the system. The f0 activations are connected across time to extract pitch contours. These contours define a framework within which subsequent networks perform onset and offset detection, operating across both time and smaller pitch fluctuations at the same time. As input, the networks use, e.g., variations of latent representations from the f0 estimation network. Finally, incorrect tentative notes are removed one by one in an iterative procedure that allows a network to classify notes within an accurate context. The system was evaluated on four public test sets: MAPS, Bach10, TRIOS, and the MIREX Woodwind quintet, and performed state-of-the-art results for all four datasets. It performs well across all subtasks: f0, pitched onset, and pitched offset tracking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.02918](http://arxiv.org/abs/1804.02918)

##### PDF
[http://arxiv.org/pdf/1804.02918](http://arxiv.org/pdf/1804.02918)

