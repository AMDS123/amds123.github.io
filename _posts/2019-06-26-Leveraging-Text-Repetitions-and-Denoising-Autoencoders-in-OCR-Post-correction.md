---
layout: post
title: "Leveraging Text Repetitions and Denoising Autoencoders in OCR Post-correction"
date: 2019-06-26 08:28:51
categories: arXiv_CL
tags: arXiv_CL OCR
author: Kai Hakala, Aleksi Vesanto, Niko Miekka, Tapio Salakoski, Filip Ginter
mathjax: true
---

* content
{:toc}

##### Abstract
A common approach for improving OCR quality is a post-processing step based on models correcting misdetected characters and tokens. These models are typically trained on aligned pairs of OCR read text and their manually corrected counterparts. In this paper we show that the requirement of manually corrected training data can be alleviated by estimating the OCR errors from repeating text spans found in large OCR read text corpora and generating synthetic training examples following this error distribution. We use the generated data for training a character-level neural seq2seq model and evaluate the performance of the suggested model on a manually corrected corpus of Finnish newspapers mostly from the 19th century. The results show that a clear improvement over the underlying OCR system as well as previously suggested models utilizing uniformly generated noise can be achieved.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10907](http://arxiv.org/abs/1906.10907)

##### PDF
[http://arxiv.org/pdf/1906.10907](http://arxiv.org/pdf/1906.10907)

