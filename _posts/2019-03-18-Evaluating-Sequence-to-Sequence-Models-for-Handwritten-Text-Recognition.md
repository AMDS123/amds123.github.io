---
layout: post
title: "Evaluating Sequence-to-Sequence Models for Handwritten Text Recognition"
date: 2019-03-18 11:51:33
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Speech_Recognition Caption CNN Language_Model Recognition
author: Johannes Michael, Roger Labahn, Tobias Gr&#xfc;ning, Jochen Z&#xf6;llner
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder models have become an effective approach for sequence learning tasks like machine translation, image captioning and speech recognition, but have yet to show competitive results for handwritten text recognition. To this end, we propose an attention-based sequence-to-sequence model. It combines a convolutional neural network as a generic feature extractor with a recurrent neural network to encode both the visual information, as well as the temporal context between characters in the input image, and uses a separate recurrent neural network to decode the actual character sequence. We make experimental comparisons between various attention mechanisms and positional encodings, in order to find an appropriate alignment between the input and output sequence. The model can be trained end-to-end and the optional integration of a hybrid loss allows the encoder to retain an interpretable and usable output, e.g. for keyword spotting purposes without prior indexing, if desired. We achieve competitive results on the IAM and ICFHR2016 READ data sets compared to the state-of-the-art without the use of a language model, and we significantly improve over any recent sequence-to-sequence approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07377](http://arxiv.org/abs/1903.07377)

##### PDF
[http://arxiv.org/pdf/1903.07377](http://arxiv.org/pdf/1903.07377)

