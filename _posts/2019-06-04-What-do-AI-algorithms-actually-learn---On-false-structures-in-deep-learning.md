---
layout: post
title: "What do AI algorithms actually learn? - On false structures in deep learning"
date: 2019-06-04 14:35:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Deep_Learning
author: Laura Thesing, Vegard Antun, Anders C. Hansen
mathjax: true
---

* content
{:toc}

##### Abstract
There are two big unsolved mathematical questions in artificial intelligence (AI): (1) Why is deep learning so successful in classification problems and (2) why are neural nets based on deep learning at the same time universally unstable, where the instabilities make the networks vulnerable to adversarial attacks. We present a solution to these questions that can be summed up in two words; false structures. Indeed, deep learning does not learn the original structures that humans use when recognising images (cats have whiskers, paws, fur, pointy ears, etc), but rather different false structures that correlate with the original structure and hence yield the success. However, the false structure, unlike the original structure, is unstable. The false structure is simpler than the original structure, hence easier to learn with less data and the numerical algorithm used in the training will more easily converge to the neural network that captures the false structure. We formally define the concept of false structures and formulate the solution as a conjecture. Given that trained neural networks always are computed with approximations, this conjecture can only be established through a combination of theoretical and computational results similar to how one establishes a postulate in theoretical physics (e.g. the speed of light is constant). Establishing the conjecture fully will require a vast research program characterising the false structures. We provide the foundations for such a program establishing the existence of the false structures in practice. Finally, we discuss the far reaching consequences the existence of the false structures has on state-of-the-art AI and Smale's 18th problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01478](http://arxiv.org/abs/1906.01478)

##### PDF
[http://arxiv.org/pdf/1906.01478](http://arxiv.org/pdf/1906.01478)

