---
layout: post
title: "Region Proposal Networks with Contextual Selective Attention for Real-Time Organ Detection"
date: 2018-12-26 14:33:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention GAN Detection
author: Awais Mansoor, Antonio R. Porras, Marius George Linguraru
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for object detection use region proposal networks (RPN) to hypothesize object location. These networks simultaneously predicts object bounding boxes and \emph{objectness} scores at each location in the image. Unlike natural images for which RPN algorithms were originally designed, most medical images are acquired following standard protocols, thus organs in the image are typically at a similar location and possess similar geometrical characteristics (e.g. scale, aspect-ratio, etc.). Therefore, medical image acquisition protocols hold critical localization and geometric information that can be incorporated for faster and more accurate detection. This paper presents a novel attention mechanism for the detection of organs by incorporating imaging protocol information. Our novel selective attention approach (i) effectively shrinks the search space inside the feature map, (ii) appends useful localization information to the hypothesized proposal for the detection architecture to learn where to look for each organ, and (iii) modifies the pyramid of regression references in the RPN by incorporating organ- and modality-specific information, which results in additional time reduction. We evaluated the proposed framework on a dataset of 768 chest X-ray images obtained from a diverse set of sources. Our results demonstrate superior performance for the detection of the lung field compared to the state-of-the-art, both in terms of detection accuracy, demonstrating an improvement of $&gt;7\%$ in Dice score, and reduced processing time by $27.53\%$ due to fewer hypotheses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10330](http://arxiv.org/abs/1812.10330)

##### PDF
[http://arxiv.org/pdf/1812.10330](http://arxiv.org/pdf/1812.10330)

