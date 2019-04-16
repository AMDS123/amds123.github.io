---
layout: post
title: "Women also Snowboard: Overcoming Bias in Captioning Models"
date: 2018-07-02 08:15:11
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Prediction
author: Lisa Anne Hendricks, Kaylee Burns, Kate Saenko, Trevor Darrell, Anna Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Most machine learning methods are known to capture and exploit biases of the training data. While some biases are beneficial for learning, others are harmful. Specifically, image captioning models tend to exaggerate biases present in training data. This can lead to incorrect captions in domains where unbiased captions are desired, or required, due to over reliance on the learned prior and image context. We investigate generation of gender specific caption words (e.g. man, woman) based on the person's appearance or the image context. We introduce a new Equalizer model that ensures equal gender probability when gender evidence is occluded in a scene and confident predictions when gender evidence is present. The resulting model is forced to look at a person rather than use contextual cues to make a gender specific prediction. The losses that comprise our model, the Appearance Confusion Loss and the Confident Loss, are general, and can be added to any description model in order to mitigate impacts of unwanted bias in a description dataset. Our proposed model has lower error than prior work when describing images with people and mentioning their gender and more closely matches the ground truth ratio of sentences including women to sentences including men.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.00517](https://arxiv.org/abs/1807.00517)

##### PDF
[https://arxiv.org/pdf/1807.00517](https://arxiv.org/pdf/1807.00517)

