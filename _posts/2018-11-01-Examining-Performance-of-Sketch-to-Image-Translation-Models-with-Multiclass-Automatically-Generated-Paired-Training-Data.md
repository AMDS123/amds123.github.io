---
layout: post
title: "Examining Performance of Sketch-to-Image Translation Models with Multiclass Automatically Generated Paired Training Data"
date: 2018-11-01 05:59:53
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Dichao Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Image translation is a computer vision task that involves translating one representation of the scene into another. Various approaches have been proposed and achieved highly desirable results. Nevertheless, its accomplishment requires abundant paired training data which are expensive to acquire. Therefore, models for translation are usually trained on a set of paired training data which are carefully and laboriously designed. Our work is focused on learning through automatically generated paired data. We propose a method to generate fake sketches from images using an adversarial network and then pair the images with corresponding fake sketches to form large-scale multi-class paired training data for training a sketch-to-image translation model. Our model is an encoder-decoder architecture where the encoder generates fake sketches from images and the decoder performs sketch-to-image translation. Qualitative results show that the encoder can be used for generating large-scale multi-class paired data under low supervision. Our current dataset now contains 61255 image and (fake) sketch pairs from 256 different categories. These figures can be greatly increased in the future thanks to our weak reliance on manually labeled data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00249](http://arxiv.org/abs/1811.00249)

##### PDF
[http://arxiv.org/pdf/1811.00249](http://arxiv.org/pdf/1811.00249)

