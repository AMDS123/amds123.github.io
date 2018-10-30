---
layout: post
title: "Real-time Action Recognition with Dissimilarity-based Training of Specialized Module Networks"
date: 2018-10-27 23:29:13
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Marian K.Y. Boktor, Ahmad Al-Kabbany, Radwa Khalil, Said El-Khamy
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of real-time action recognition in trimmed videos, for which deep neural networks have defined the state-of-the-art performance in the recent literature. For attaining higher recognition accuracies with efficient computations, researchers have addressed the various aspects of limitations in the recognition pipeline. This includes network architecture, the number of input streams (where additional streams augment the color information), the cost function to be optimized, in addition to others. The literature has always aimed, though, at assigning the adopted network (or networks, in case of multiple streams) the task of recognizing the whole number of action classes in the dataset at hand. We propose to train multiple specialized module networks instead. Each module is trained to recognize a subset of the action classes. Towards this goal, we present a dissimilarity-based optimized procedure for distributing the action classes over the modules, which can be trained simultaneously offline. On two standard datasets--UCF-101 and HMDB-51--the proposed method demonstrates a comparable performance, that is superior in some aspects, to the state-of-the-art, and that satisfies the real-time constraint. We achieved 72.5\% accuracy on the challenging HMDB-51 dataset. By assigning fewer and unalike classes to each module network, this research paves the way to benefit from light-weight architectures without compromising recognition accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11731](http://arxiv.org/abs/1810.11731)

##### PDF
[http://arxiv.org/pdf/1810.11731](http://arxiv.org/pdf/1810.11731)

