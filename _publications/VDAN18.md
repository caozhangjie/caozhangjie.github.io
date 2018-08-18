---
title: "Learning Transferable Visual Features with Very Deep Adaptation Networks"
collection: publications
permalink: /publications/VDAN18
venue: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
date: 2017-10-21
citation: 'Mingsheng Long, <b>Zhangjie Cao</b>, Jianmin Wang, Han Zhu, Michael I. Jordan. <i>IEEE Transactions on Pattern Analysis and Machine Intelligence</i> <b>TPAMI</b>.'
---

[[PDF]](http://caozhangjie.github.io/files/VDAN18.pdf)

## Abstract
Domain adaptation generalizes a learning machine across source domain and target domain under different distributions. Recent studies reveal that deep neural networks can learn transferable features that generalize well to similar novel tasks for domain adaptation. However, as deep features eventually transition from general to specific along the network, feature transferability drops significantly in higher task-specific layers with increasing domain discrepancy. To formally reduce the dataset bias and enhance the feature transferability in task-specific layers, this paper presents a novel framework for deep adaptation networks, which generalizes deep convolutional neural networks to domain adaptation. The framework embeds the deep features of all task-specific layers to reproducing kernel Hilbert spaces (RKHSs) and optimally match different domain distributions. The deep features are made more transferable by exploring very deep architectures and low-density separation of target-unlabeled data, while the domain discrepancy is further reduced using multiple kernel learning and maximal testing power for kernel embedding matching. The framework can learn transferable visual features with statistical guarantees, and can scale linearly using unbiased estimate of kernel embedding. Extensive empirical evidence shows that the proposed networks yield state of the art results on standard visual domain adaptation benchmarks.