---
layout: post
title: "New Techniques for Graph Edit Distance Computation"
date: 2019-08-01 08:33:48
categories: arXiv_CV
tags: arXiv_CV QA Classification Recognition
author: David B. Blumenthal
mathjax: true
---

* content
{:toc}

##### Abstract
Due to their capacity to encode rich structural information, labeled graphs are often used for modeling various kinds of objects such as images, molecules, and chemical compounds. If pattern recognition problems such as clustering and classification are to be solved on these domains, a (dis-)similarity measure for labeled graphs has to be defined. A widely used measure is the graph edit distance (GED), which, intuitively, is defined as the minimum amount of distortion that has to be applied to a source graph in order to transform it into a target graph. The main advantage of GED is its flexibility and sensitivity to small differences between the input graphs. Its main drawback is that it is hard to compute. 
 In this thesis, new results and techniques for several aspects of computing GED are presented. Firstly, theoretical aspects are discussed: competing definitions of GED are harmonized, the problem of computing GED is characterized in terms of complexity, and several reductions from GED to the quadratic assignment problem (QAP) are presented. Secondly, solvers for the linear sum assignment problem with error-correction (LSAPE) are discussed. LSAPE is a generalization of the well-known linear sum assignment problem (LSAP), and has to be solved as a subproblem by many GED algorithms. In particular, a new solver is presented that efficiently reduces LSAPE to LSAP. Thirdly, exact algorithms for computing GED are presented in a systematic way, and improvements of existing algorithms as well as a new mixed integer programming (MIP) based approach are introduced. Fourthly, a detailed overview of heuristic algorithms that approximate GED via upper and lower bounds is provided, and eight new heuristics are described. Finally, a new easily extensible C++ library for exactly or approximately computing GED is presented.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00265](http://arxiv.org/abs/1908.00265)

##### PDF
[http://arxiv.org/pdf/1908.00265](http://arxiv.org/pdf/1908.00265)

