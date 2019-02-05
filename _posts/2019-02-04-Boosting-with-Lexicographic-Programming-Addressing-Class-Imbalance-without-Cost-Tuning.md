---
layout: post
title: "Boosting with Lexicographic Programming: Addressing Class Imbalance without Cost Tuning"
date: 2019-02-04 01:08:07
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Shounak Datta, Sayak Nag, Swagatam Das
mathjax: true
---

* content
{:toc}

##### Abstract
A large amount of research effort has been dedicated to adapting boosting for imbalanced classification. However, boosting methods are yet to be satisfactorily immune to class imbalance, especially for multi-class problems. This is because most of the existing solutions for handling class imbalance rely on expensive cost set tuning for determining the proper level of compensation. We show that the assignment of weights to the component classifiers of a boosted ensemble can be thought of as a game of Tug of War between the classes in the margin space. We then demonstrate how this insight can be used to attain a good compromise between the rare and abundant classes without having to resort to cost set tuning, which has long been the norm for imbalanced classification. The solution is based on a lexicographic linear programming framework which requires two stages. Initially, class-specific component weight combinations are found so as to minimize a hinge loss individually for each of the classes. Subsequently, the final component weights are assigned so that the maximum deviation from the class-specific minimum loss values (obtained in the previous stage) is minimized. Hence, the proposal is not only restricted to two-class situations, but is also readily applicable to multi-class problems. Additionally,we also derive the dual formulation corresponding to the proposed framework. Experiments conducted on artificial and real-world imbalanced datasets as well as on challenging applications such as hyperspectral image classification and ImageNet classification establish the efficacy of the proposal.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.09684](http://arxiv.org/abs/1708.09684)

##### PDF
[http://arxiv.org/pdf/1708.09684](http://arxiv.org/pdf/1708.09684)

