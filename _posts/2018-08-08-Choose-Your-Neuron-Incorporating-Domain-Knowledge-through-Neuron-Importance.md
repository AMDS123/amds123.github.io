---
layout: post
title: "Choose Your Neuron: Incorporating Domain Knowledge through Neuron-Importance"
date: 2018-08-08 17:00:43
categories: arXiv_CV
tags: arXiv_CV Knowledge Caption CNN Classification Prediction
author: Ramprasaath R. Selvaraju, Prithvijit Chattopadhyay, Mohamed Elhoseiny, Tilak Sharma, Dhruv Batra, Devi Parikh, Stefan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Individual neurons in convolutional neural networks supervised for image-level classification tasks have been shown to implicitly learn semantically meaningful concepts ranging from simple textures and shapes to whole or partial objects - forming a "dictionary" of concepts acquired through the learning process. In this work we introduce a simple, efficient zero-shot learning approach based on this observation. Our approach, which we call Neuron Importance-AwareWeight Transfer (NIWT), learns to map domain knowledge about novel "unseen" classes onto this dictionary of learned concepts and then optimizes for network parameters that can effectively combine these concepts - essentially learning classifiers by discovering and composing learned semantic concepts in deep networks. Our approach shows improvements over previous approaches on the CUBirds and AWA2 generalized zero-shot learning benchmarks. We demonstrate our approach on a diverse set of semantic inputs as external domain knowledge including attributes and natural language captions. Moreover by learning inverse mappings, NIWT can provide visual and textual explanations for the predictions made by the newly learned classifiers and provide neuron names. Our code is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.02861](https://arxiv.org/abs/1808.02861)

##### PDF
[https://arxiv.org/pdf/1808.02861](https://arxiv.org/pdf/1808.02861)

