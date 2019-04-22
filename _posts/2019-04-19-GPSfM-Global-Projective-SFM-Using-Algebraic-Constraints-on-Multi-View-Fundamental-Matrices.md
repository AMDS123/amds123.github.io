---
layout: post
title: "GPSfM: Global Projective SFM Using Algebraic Constraints on Multi-View Fundamental Matrices"
date: 2019-04-19 12:33:16
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Yoni Kasten, Amnon Geifman, Meirav Galun, Ronen Basri
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of recovering projective camera matrices from collections of fundamental matrices in multiview settings. We make two main contributions. First, given ${n \choose 2}$ fundamental matrices computed for $n$ images, we provide a complete algebraic characterization in the form of conditions that are both necessary and sufficient to enabling the recovery of camera matrices. These conditions are based on arranging the fundamental matrices as blocks in a single matrix, called the $n$-view fundamental matrix, and characterizing this matrix in terms of the signs of its eigenvalues and rank structures. Secondly, we propose a concrete algorithm for projective structure-from-motion that utilizes this characterization. Given a complete or partial collection of measured fundamental matrices, our method seeks camera matrices that minimize a global algebraic error for the measured fundamental matrices. In contrast to existing methods, our optimization, without any initialization, produces a consistent set of fundamental matrices that corresponds to a unique set of cameras (up to a choice of projective frame). Our experiments indicate that our method achieves state of the art performance in both accuracy and running time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00426](http://arxiv.org/abs/1812.00426)

##### PDF
[http://arxiv.org/pdf/1812.00426](http://arxiv.org/pdf/1812.00426)

