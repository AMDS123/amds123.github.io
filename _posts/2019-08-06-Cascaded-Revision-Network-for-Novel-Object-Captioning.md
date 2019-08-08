---
layout: post
title: "Cascaded Revision Network for Novel Object Captioning"
date: 2019-08-06 01:36:31
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Knowledge Attention Caption Detection
author: Qianyu Feng, Yu Wu, Hehe Fan, Chenggang Yan, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning, a challenging task where the machine automatically describes an image by sentences, has drawn significant attention in recent years. Despite the remarkable improvements of recent approaches, however, these methods are built upon a large set of training image-sentence pairs. The expensive labor efforts hence limit the captioning model to describe the wider world. In this paper, we present a novel network structure, Cascaded Revision Network, which aims at relieving the problem by equipping the model with out-of-domain knowledge. CRN first tries its best to describe an image using the existing vocabulary from in-domain knowledge. Due to the lack of out-of-domain knowledge, the caption may be inaccurate or include ambiguous words for the image with unknown (novel) objects. We propose to re-edit the primary captioning sentence by a series of cascaded operations. We introduce a perplexity predictor to find out which words are most likely to be inaccurate given the input image. Thereafter, we utilize external knowledge from a pre-trained object detection model and select more accurate words from detection results by the visual matching module. In the last step, we design a semantic matching module to ensure that the novel object is fit in the right position. By this novel cascaded captioning-revising mechanism, CRN can accurately describe images with unseen objects. We validate the proposed method with state-of-the-art performance on the held-out MSCOCO dataset as well as scale to ImageNet, demonstrating the effectiveness of this method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02726](http://arxiv.org/abs/1908.02726)

##### PDF
[http://arxiv.org/pdf/1908.02726](http://arxiv.org/pdf/1908.02726)

