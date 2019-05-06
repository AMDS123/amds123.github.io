---
layout: post
title: "Medusa: An Efficient Cloud Fault-Tolerant MapReduce"
date: 2015-11-23 12:02:43
categories: arXiv_CV
tags: arXiv_CV
author: Pedro A.R.S. Costa, Xiao Bai, Fernando M.V. Ramos, Miguel Correia
mathjax: true
---

* content
{:toc}

##### Abstract
Applications such as web search and social networking have been moving from centralized to decentralized cloud architectures to improve their scalability. MapReduce, a programming framework for processing large amounts of data using thousands of machines in a single cloud, also needs to be scaled out to multiple clouds to adapt to this evolution. The challenge of building a multi-cloud distributed architecture is substantial. Notwithstanding, the ability to deal with the new types of faults introduced by such setting, such as the outage of a whole datacenter or an arbitrary fault caused by a malicious cloud insider, increases the endeavor considerably. In this paper we propose Medusa, a platform that allows MapReduce computations to scale out to multiple clouds and tolerate several types of faults. Our solution fulfills four objectives. First, it is transparent to the user, who writes her typical MapReduce application without modification. Second, it does not require any modification to the widely used Hadoop framework. Third, the proposed system goes well beyond the fault-tolerance offered by MapReduce to tolerate arbitrary faults, cloud outages, and even malicious faults caused by corrupt cloud insiders. Fourth, it achieves this increased level of fault tolerance at reasonable cost. We performed an extensive experimental evaluation in the ExoGENI testbed, demonstrating that our solution significantly reduces execution time when compared to traditional methods that achieve the same level of resilience.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1511.07185](https://arxiv.org/abs/1511.07185)

##### PDF
[https://arxiv.org/pdf/1511.07185](https://arxiv.org/pdf/1511.07185)

