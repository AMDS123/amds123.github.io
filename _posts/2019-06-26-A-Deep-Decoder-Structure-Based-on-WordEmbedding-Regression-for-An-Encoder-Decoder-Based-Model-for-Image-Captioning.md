---
layout: post
title: "A Deep Decoder Structure Based on WordEmbedding Regression for An Encoder-Decoder Based Model for Image Captioning"
date: 2019-06-26 13:51:59
categories: arXiv_AI
tags: arXiv_AI Image_Caption Attention Caption Embedding Deep_Learning
author: Ahmad Asadi, Reza Safabakhsh
mathjax: true
---

* content
{:toc}

##### Abstract
Generating textual descriptions for images has been an attractive problem for the computer vision and natural language processing researchers in recent years. Dozens of models based on deep learning have been proposed to solve this problem. The existing approaches are based on neural encoder-decoder structures equipped with the attention mechanism. These methods strive to train decoders to minimize the log likelihood of the next word in a sentence given the previous ones, which results in the sparsity of the output space. In this work, we propose a new approach to train decoders to regress the word embedding of the next word with respect to the previous ones instead of minimizing the log likelihood. The proposed method is able to learn and extract long-term information and can generate longer fine-grained captions without introducing any external memory cell. Furthermore, decoders trained by the proposed technique can take the importance of the generated words into consideration while generating captions. In addition, a novel semantic attention mechanism is proposed that guides attention points through the image, taking the meaning of the previously generated word into account. We evaluate the proposed approach with the MS-COCO dataset. The proposed model outperformed the state of the art models especially in generating longer captions. It achieved a CIDEr score equal to 125.0 and a BLEU-4 score equal to 50.5, while the best scores of the state of the art models are 117.1 and 48.0, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12188](http://arxiv.org/abs/1906.12188)

##### PDF
[http://arxiv.org/pdf/1906.12188](http://arxiv.org/pdf/1906.12188)

