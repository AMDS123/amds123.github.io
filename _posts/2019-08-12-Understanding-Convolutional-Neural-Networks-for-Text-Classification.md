---
layout: post
title: "Understanding Convolutional Neural Networks for Text Classification"
date: 2019-08-12 10:37:41
categories: arXiv_CL
tags: arXiv_CL Object_Detection Text_Classification CNN Classification Prediction Detection
author: Alon Jacovi, Oren Sar Shalom, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
We present an analysis into the inner workings of Convolutional Neural Networks (CNNs) for processing text. CNNs used for computer vision can be interpreted by projecting filters into image space, but for discrete sequence inputs CNNs remain a mystery. We aim to understand the method by which the networks process and classify text. We examine common hypotheses to this problem: that filters, accompanied by global max-pooling, serve as ngram detectors. We show that filters may capture several different semantic classes of ngrams by using different activation patterns, and that global max-pooling induces behavior which separates important ngrams from the rest. Finally, we show practical use cases derived from our findings in the form of model interpretability (explaining a trained model by deriving a concrete identity for each filter, bridging the gap between visualization tools in vision tasks and NLP) and prediction interpretability (explaining predictions). Code implementation is available online at github.com/sayaendo/interpreting-cnn-for-text.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.08037](http://arxiv.org/abs/1809.08037)

##### PDF
[http://arxiv.org/pdf/1809.08037](http://arxiv.org/pdf/1809.08037)

