---
layout: post
title: "ShapeGlot: Learning Language for Shape Differentiation"
date: 2019-05-08 06:01:33
categories: arXiv_CV
tags: arXiv_CV Attention Transfer_Learning Relation
author: Panos Achlioptas, Judy Fan, Robert X.D. Hawkins, Noah D. Goodman, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we explore how fine-grained differences between the shapes of common objects are expressed in language, grounded on images and 3D models of the objects. We first build a large scale, carefully controlled dataset of human utterances that each refers to a 2D rendering of a 3D CAD model so as to distinguish it from a set of shape-wise similar alternatives. Using this dataset, we develop neural language understanding (listening) and production (speaking) models that vary in their grounding (pure 3D forms via point-clouds vs. rendered 2D images), the degree of pragmatic reasoning captured (e.g. speakers that reason about a listener or not), and the neural architecture (e.g. with or without attention). We find models that perform well with both synthetic and human partners, and with held out utterances and objects. We also find that these models are amenable to zero-shot transfer learning to novel object classes (e.g. transfer from training on chairs to testing on lamps), as well as to real-world images drawn from furniture catalogs. Lesion studies indicate that the neural listeners depend heavily on part-related words and associate these words correctly with visual parts of objects (without any explicit network training on object parts), and that transfer to novel classes is most successful when known part-words are available. This work illustrates a practical approach to language grounding, and provides a case study in the relationship between object shape and linguistic structure when it comes to object differentiation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02925](http://arxiv.org/abs/1905.02925)

##### PDF
[http://arxiv.org/pdf/1905.02925](http://arxiv.org/pdf/1905.02925)

