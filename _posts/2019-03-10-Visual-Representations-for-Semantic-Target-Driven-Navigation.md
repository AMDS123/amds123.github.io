---
layout: post
title: "Visual Representations for Semantic Target Driven Navigation"
date: 2019-03-10 00:49:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Arsalan Mousavian, Alexander Toshev, Marek Fiser, Jana Kosecka, Ayzaan Wahid, James Davidson
mathjax: true
---

* content
{:toc}

##### Abstract
What is a good visual representation for autonomous agents? We address this question in the context of semantic visual navigation, which is the problem of a robot finding its way through a complex environment to a target object, e.g. go to the refrigerator. Instead of acquiring a metric semantic map of an environment and using planning for navigation, our approach learns navigation policies on top of representations that capture spatial layout and semantic contextual cues. We propose to using high level semantic and contextual features including segmentation and detection masks obtained by off-the-shelf state-of-the-art vision as observations and use deep network to learn the navigation policy. This choice allows using additional data, from orthogonal sources, to better train different parts of the model the representation extraction is trained on large standard vision datasets while the navigation component leverages large synthetic environments for training. This combination of real and synthetic is possible because equitable feature representations are available in both (e.g., segmentation and detection masks), which alleviates the need for domain adaptation. Both the representation and the navigation policy can be readily applied to real non-synthetic environments as demonstrated on the Active Vision Dataset [1]. Our approach gets successfully to the target in 54% of the cases in unexplored environments, compared to 46% for non-learning based approach, and 28% for the learning-based baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.06066](http://arxiv.org/abs/1805.06066)

##### PDF
[http://arxiv.org/pdf/1805.06066](http://arxiv.org/pdf/1805.06066)

