---
layout: post
title: "Deep Neural Network Augmentation: Generating Faces for Affect Analysis"
date: 2019-07-16 21:33:58
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Face Quantitative Recognition
author: Dimitrios Kollias, Shiyang Cheng, Evangelos Ververas, Irene Kotsia, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel approach for synthesizing facial affect; either in terms of the six basic expressions (i.e., anger, disgust, fear, joy, sadness and surprise), or in terms of valence (i.e., how positive or negative is an emotion) and arousal (i.e., power of the emotion activation). The proposed approach accepts the following inputs: i) a neutral 2D image of a person; ii) a basic facial expression or a pair of valence-arousal (VA) emotional state descriptors to be generated, or a path of affect in the 2D VA Space to be generated as an image sequence. In order to synthesize affect in terms of VA, for this person, $600,000$ frames from the 4DFAB database were annotated. The affect synthesis is implemented by fitting a 3D Morphable Model on the neutral image, then deforming the reconstructed face and adding the inputted affect, and blending the new face with the given affect into the original image. Qualitative experiments illustrate the generation of realistic images, when the neutral image is sampled from thirteen well known lab-controlled or in-the-wild databases, including Aff-Wild, AffectNet, RAF-DB; comparisons with Generative Adversarial Networks (GANs) show the higher quality achieved by the proposed approach. Then, quantitative experiments are conducted, in which the synthesized images are used for data augmentation in training Deep Neural Networks to perform affect recognition over all databases; greatly improved performances are achieved when compared with state-of-the-art methods, as well as with GAN-based data augmentation, in all cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05027](http://arxiv.org/abs/1811.05027)

##### PDF
[http://arxiv.org/pdf/1811.05027](http://arxiv.org/pdf/1811.05027)

