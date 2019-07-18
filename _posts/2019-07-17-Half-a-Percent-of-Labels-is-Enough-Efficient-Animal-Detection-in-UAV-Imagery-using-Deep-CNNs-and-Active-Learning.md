---
layout: post
title: "Half a Percent of Labels is Enough: Efficient Animal Detection in UAV Imagery using Deep CNNs and Active Learning"
date: 2019-07-17 04:06:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Benjamin Kellenberger, Diego Marcos, Sylvain Lobry, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
We present an Active Learning (AL) strategy for re-using a deep Convolutional Neural Network (CNN)-based object detector on a new dataset. This is of particular interest for wildlife conservation: given a set of images acquired with an Unmanned Aerial Vehicle (UAV) and manually labeled gound truth, our goal is to train an animal detector that can be re-used for repeated acquisitions, e.g. in follow-up years. Domain shifts between datasets typically prevent such a direct model application. We thus propose to bridge this gap using AL and introduce a new criterion called Transfer Sampling (TS). TS uses Optimal Transport to find corresponding regions between the source and the target datasets in the space of CNN activations. The CNN scores in the source dataset are used to rank the samples according to their likelihood of being animals, and this ranking is transferred to the target dataset. Unlike conventional AL criteria that exploit model uncertainty, TS focuses on very confident samples, thus allowing a quick retrieval of true positives in the target dataset, where positives are typically extremely rare and difficult to find by visual inspection. We extend TS with a new window cropping strategy that further accelerates sample retrieval. Our experiments show that with both strategies combined, less than half a percent of oracle-provided labels are enough to find almost 80% of the animals in challenging sets of UAV images, beating all baselines by a margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07319](http://arxiv.org/abs/1907.07319)

##### PDF
[http://arxiv.org/pdf/1907.07319](http://arxiv.org/pdf/1907.07319)

