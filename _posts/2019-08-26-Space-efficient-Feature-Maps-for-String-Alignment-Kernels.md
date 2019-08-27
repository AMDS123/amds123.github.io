---
layout: post
title: "Space-efficient Feature Maps for String Alignment Kernels"
date: 2019-08-26 08:36:23
categories: arXiv_AI
tags: arXiv_AI Embedding Classification Prediction
author: Yasuo Tabei, Yoshihiro Yamanishi, Rasmus Pagh
mathjax: true
---

* content
{:toc}

##### Abstract
String kernels are attractive data analysis tools for analyzing string data. Among them, alignment kernels are known for their high prediction accuracies in string classifications when tested in combination with SVM in various applications. However, alignment kernels have a crucial drawback in that they scale poorly due to their quadratic computation complexity in the number of input strings, which limits large-scale applications in practice. We address this need by presenting the first approximation for string alignment kernels, which we call space-efficient feature maps for edit distance with moves (SFMEDM), by leveraging a metric embedding named edit sensitive parsing (ESP) and feature maps (FMs) of random Fourier features (RFFs) for large-scale string analyses. The original FMs for RFFs consume a huge amount of memory proportional to the dimension d of input vectors and the dimension D of output vectors, which prohibits its large-scale applications. We present novel space-efficient feature maps (SFMs) of RFFs for a space reduction from O(dD) of the original FMs to O(d) of SFMs with a theoretical guarantee with respect to concentration bounds. We experimentally test SFMEDM on its ability to learn SVM for large-scale string classifications with various massive string data, and we demonstrate the superior performance of SFMEDM with respect to prediction accuracy, scalability and computation efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.06382](http://arxiv.org/abs/1802.06382)

##### PDF
[http://arxiv.org/pdf/1802.06382](http://arxiv.org/pdf/1802.06382)

