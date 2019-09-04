---
layout: post
title: "Phrase Grounding by Soft-Label Chain Conditional Random Field"
date: 2019-09-01 01:57:45
categories: arXiv_CL
tags: arXiv_CL Caption Inference Prediction
author: Jiacheng Liu, Julia Hockenmaier
mathjax: true
---

* content
{:toc}

##### Abstract
The phrase grounding task aims to ground each entity mention in a given caption of an image to a corresponding region in that image. Although there are clear dependencies between how different mentions of the same caption should be grounded, previous structured prediction methods that aim to capture such dependencies need to resort to approximate inference or non-differentiable losses. In this paper, we formulate phrase grounding as a sequence labeling task where we treat candidate regions as potential labels, and use neural chain Conditional Random Fields (CRFs) to model dependencies among regions for adjacent mentions. In contrast to standard sequence labeling tasks, the phrase grounding task is defined such that there may be multiple correct candidate regions. To address this multiplicity of gold labels, we define so-called Soft-Label Chain CRFs, and present an algorithm that enables convenient end-to-end training. Our method establishes a new state-of-the-art on phrase grounding on the Flickr30k Entities dataset. Analysis shows that our model benefits both from the entity dependencies captured by the CRF and from the soft-label training regime. Our code is available at \url{github.com/liujch1998/SoftLabelCCRF}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00301](http://arxiv.org/abs/1909.00301)

##### PDF
[http://arxiv.org/pdf/1909.00301](http://arxiv.org/pdf/1909.00301)

