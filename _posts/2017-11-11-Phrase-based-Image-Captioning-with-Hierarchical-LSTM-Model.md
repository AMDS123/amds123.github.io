---
layout: post
title: "Phrase-based Image Captioning with Hierarchical LSTM Model"
date: 2017-11-11 10:48:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference RNN
author: Ying Hua Tan, Chee Seng Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic generation of caption to describe the content of an image has been gaining a lot of research interests recently, where most of the existing works treat the image caption as pure sequential data. Natural language, however possess a temporal hierarchy structure, with complex dependencies between each subsequence. In this paper, we propose a phrase-based hierarchical Long Short-Term Memory (phi-LSTM) model to generate image description. In contrast to the conventional solutions that generate caption in a pure sequential manner, our proposed model decodes image caption from phrase to sentence. It consists of a phrase decoder at the bottom hierarchy to decode noun phrases of variable length, and an abbreviated sentence decoder at the upper hierarchy to decode an abbreviated form of the image description. A complete image caption is formed by combining the generated phrases with sentence during the inference stage. Empirically, our proposed model shows a better or competitive result on the Flickr8k, Flickr30k and MS-COCO datasets in comparison to the state-of-the art models. We also show that our proposed model is able to generate more novel captions (not seen in the training data) which are richer in word contents in all these three datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.05557](https://arxiv.org/abs/1711.05557)

##### PDF
[https://arxiv.org/pdf/1711.05557](https://arxiv.org/pdf/1711.05557)

