---
layout: post
title: "Multilingual and Unsupervised Subword Modeling for Zero-Resource Languages"
date: 2018-11-09 11:04:40
categories: arXiv_CL
tags: arXiv_CL Segmentation
author: Enno Hermann, Herman Kamper, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised subword modeling aims to learn low-level representations of speech audio in "zero-resource" settings: that is, without using transcriptions or other resources from the target language (such as text corpora or pronunciation dictionaries). A good representation should capture phonetic content and abstract away from other types of variability, such as speaker differences and channel noise. Previous work in this area has primarily focused on learning from target language data only, and has been evaluated only intrinsically. Here we directly compare multiple methods, including some that use only target language speech data and some that use transcribed speech from other (non-target) languages, and we evaluate using two intrinsic measures as well as on a downstream unsupervised word segmentation and clustering task. We find that combining two existing target-language-only methods yields better features than either method alone. Nevertheless, even better results are obtained by extracting target language bottleneck features using a model trained on other languages. Cross-lingual training using just one other language is enough to provide this benefit, but multilingual training helps even more. In addition to these results, which hold across both intrinsic measures and the extrinsic task, we discuss the qualitative differences between the different types of learned features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04791](http://arxiv.org/abs/1811.04791)

##### PDF
[http://arxiv.org/pdf/1811.04791](http://arxiv.org/pdf/1811.04791)

