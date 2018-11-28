---
layout: post
title: "Unsupervised Image Captioning"
date: 2018-11-27 03:16:20
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Knowledge Caption Detection
author: Yang Feng, Lin Ma, Wei Liu, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved great successes on the image captioning task. However, most of the existing models depend heavily on paired image-sentence datasets, which are very expensive to acquire. In this paper, we make the first attempt to train an image captioning model in an unsupervised manner. Instead of relying on manually labeled image-sentence pairs, our proposed model merely requires an image set, a sentence corpus, and an existing visual concept detector. The sentence corpus is used to teach the captioning model how to generate plausible sentences. Meanwhile, the knowledge in the visual concept detector is distilled into the captioning model to guide the model to recognize the visual concepts in an image. In order to further encourage the generated captions to be semantically consistent with the image, the image and caption are projected into a common latent space so that they can be used to reconstruct each other. Given that the existing sentence corpora are mainly designed for linguistic research and thus with little reference to image contents, we crawl a large-scale image description corpus of 2 million natural sentences to facilitate the unsupervised image captioning scenario. Experimental results show that our proposed model is able to produce quite promising results without using any labeled training pairs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10787](http://arxiv.org/abs/1811.10787)

##### PDF
[http://arxiv.org/pdf/1811.10787](http://arxiv.org/pdf/1811.10787)

