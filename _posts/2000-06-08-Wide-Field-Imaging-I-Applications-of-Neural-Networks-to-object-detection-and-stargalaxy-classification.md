---
layout: post
title: "Wide Field Imaging. I. Applications of Neural Networks to object detection and star/galaxy classification"
date: 2000-06-08 16:34:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: S. Andreon (1), G. Gargiulo (2,3), G. Longo (1), R. Tagliaferri (4,5), N. Capuano (2) ((1) Oss. Astron. Capodimonte, (2) Univ. Salerno, (3) IIASS, (4) DMI, Univ. Salerno, (5) INFM, Univ. Salerno)
mathjax: true
---

* content
{:toc}

##### Abstract
[Abriged] Astronomical Wide Field Imaging performed with new large format CCD detectors poses data reduction problems of unprecedented scale which are difficult to deal with traditional interactive tools. We present here NExt (Neural Extractor): a new Neural Network (NN) based package capable to detect objects and to perform both deblending and star/galaxy classification in an automatic way. Traditionally, in astronomical images, objects are first discriminated from the noisy background by searching for sets of connected pixels having brightnesses above a given threshold and then they are classified as stars or as galaxies through diagnostic diagrams having variables choosen accordingly to the astronomer's taste and experience. In the extraction step, assuming that images are well sampled, NExt requires only the simplest a priori definition of "what an object is" (id est, it keeps all structures composed by more than one pixels) and performs the detection via an unsupervised NN approaching detection as a clustering problem which has been thoroughly studied in the artificial intelligence literature. In order to obtain an objective and reliable classification, instead of using an arbitrarily defined set of features, we use a NN to select the most significant features among the large number of measured ones, and then we use their selected features to perform the classification task. In order to optimise the performances of the system we implemented and tested several different models of NN. The comparison of the NExt performances with those of the best detection and classification package known to the authors (SExtractor) shows that NExt is at least as effective as the best traditional packages.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/astro-ph/0006115](https://arxiv.org/abs/astro-ph/0006115)

##### PDF
[https://arxiv.org/pdf/astro-ph/0006115](https://arxiv.org/pdf/astro-ph/0006115)

