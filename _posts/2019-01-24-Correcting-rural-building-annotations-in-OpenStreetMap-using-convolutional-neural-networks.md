---
layout: post
title: "Correcting rural building annotations in OpenStreetMap using convolutional neural networks"
date: 2019-01-24 01:44:12
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: John E. Vargas-Mu&#xf1;oz, Sylvain Lobry, Alexandre X. Falc&#xe3;o, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
Rural building mapping is paramount to support demographic studies and plan actions in response to crisis that affect those areas. Rural building annotations exist in OpenStreetMap (OSM), but their quality and quantity are not sufficient for training models that can create accurate rural building maps. The problems with these annotations essentially fall into three categories: (i) most commonly, many annotations are geometrically misaligned with the updated imagery; (ii) some annotations do not correspond to buildings in the images (they are misannotations or the buildings have been destroyed); and (iii) some annotations are missing for buildings in the images (the buildings were never annotated or were built between subsequent image acquisitions). First, we propose a method based on Markov Random Field (MRF) to align the buildings with their annotations. The method maximizes the correlation between annotations and a building probability map while enforcing that nearby buildings have similar alignment vectors. Second, the annotations with no evidence in the building probability map are removed. Third, we present a method to detect non-annotated buildings with predefined shapes and add their annotation. The proposed methodology shows considerable improvement in accuracy of the OSM annotations for two regions of Tanzania and Zimbabwe, being more accurate than state-of-the-art baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08190](http://arxiv.org/abs/1901.08190)

##### PDF
[http://arxiv.org/pdf/1901.08190](http://arxiv.org/pdf/1901.08190)

