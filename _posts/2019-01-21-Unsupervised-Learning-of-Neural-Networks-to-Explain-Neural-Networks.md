---
layout: post
title: "Unsupervised Learning of Neural Networks to Explain Neural Networks"
date: 2019-01-21 16:03:31
categories: arXiv_AI
tags: arXiv_AI Knowledge CNN
author: Quanshi Zhang, Yu Yang, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an unsupervised method to learn a neural network, namely an explainer, to interpret a pre-trained convolutional neural network (CNN), i.e., the explainer uses interpretable visual concepts to explain features in middle conv-layers of a CNN. Given feature maps of a conv-layer of the CNN, the explainer performs like an auto-encoder, which decomposes the feature maps into object-part features. The object-part features are learned to reconstruct CNN features without much loss of information. We can consider the disentangled representations of object parts a paraphrase of CNN features, which help people understand the knowledge encoded by the CNN. More crucially, we learn the explainer via knowledge distillation without using any annotations of object parts or textures for supervision. In experiments, our method was widely used to interpret features of different benchmark CNNs, and explainers significantly boosted the feature interpretability without hurting the discrimination power of the CNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07538](http://arxiv.org/abs/1901.07538)

##### PDF
[http://arxiv.org/pdf/1901.07538](http://arxiv.org/pdf/1901.07538)

