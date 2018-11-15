---
layout: post
title: "Looking Beyond Appearances: Synthetic Training Data for Deep CNNs in Re-identification"
date: 2018-11-13 21:14:53
categories: arXiv_CV
tags: arXiv_CV Re-identification CNN
author: Igor Barros Barbosa, Marco Cristani, Barbara Caputo, Aleksander Rognhaugen, Theoharis Theoharis
mathjax: true
---

* content
{:toc}

##### Abstract
Re-identification is generally carried out by encoding the appearance of a subject in terms of outfit, suggesting scenarios where people do not change their attire. In this paper we overcome this restriction, by proposing a framework based on a deep convolutional neural network, SOMAnet, that additionally models other discriminative aspects, namely, structural attributes of the human figure (e.g. height, obesity, gender). Our method is unique in many respects. First, SOMAnet is based on the Inception architecture, departing from the usual siamese framework. This spares expensive data preparation (pairing images across cameras) and allows the understanding of what the network learned. Second, and most notably, the training data consists of a synthetic 100K instance dataset, SOMAset, created by photorealistic human body generation software. Synthetic data represents a good compromise between realistic imagery, usually not required in re-identification since surveillance cameras capture low-resolution silhouettes, and complete control of the samples, which is useful in order to customize the data w.r.t. the surveillance scenario at-hand, e.g. ethnicity. SOMAnet, trained on SOMAset and fine-tuned on recent re-identification benchmarks, outperforms all competitors, matching subjects even with different apparel. The combination of synthetic data with Inception architectures opens up new research avenues in re-identification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1701.03153](http://arxiv.org/abs/1701.03153)

##### PDF
[http://arxiv.org/pdf/1701.03153](http://arxiv.org/pdf/1701.03153)

