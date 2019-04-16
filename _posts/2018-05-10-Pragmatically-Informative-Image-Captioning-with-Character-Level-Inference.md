---
layout: post
title: "Pragmatically Informative Image Captioning with Character-Level Inference"
date: 2018-05-10 17:10:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference
author: Reuben Cohn-Gordon, Noah Goodman, Christopher Potts
mathjax: true
---

* content
{:toc}

##### Abstract
We combine a neural image captioner with a Rational Speech Acts (RSA) model to make a system that is pragmatically informative: its objective is to produce captions that are not merely true but also distinguish their inputs from similar images. Previous attempts to combine RSA with neural image captioning require an inference which normalizes over the entire set of possible utterances. This poses a serious problem of efficiency, previously solved by sampling a small subset of possible utterances. We instead solve this problem by implementing a version of RSA which operates at the level of characters ("a","b","c"...) during the unrolling of the caption. We find that the utterance-level effect of referential captions can be obtained with only character-level decisions. Finally, we introduce an automatic method for testing the performance of pragmatic speaker models, and show that our model outperforms a non-pragmatic baseline as well as a word-level RSA captioner.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.05417](https://arxiv.org/abs/1804.05417)

##### PDF
[https://arxiv.org/pdf/1804.05417](https://arxiv.org/pdf/1804.05417)

