---
title: "Transferable Representation Learning with Deep Adaptation Networks"
collection: publications
permalink: /publications/VDAN18
venue: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
date: 2017-10-21
citation: 'Mingsheng Long, Yue Cao, <b>Zhangjie Cao</b>, Jianmin Wang, Han Zhu, Michael I. Jordan. <i>IEEE Transactions on Pattern Analysis and Machine Intelligence</i> <b>TPAMI</b>.'
---

[[Journal Version]](https://ieeexplore.ieee.org/document/8454781)

## Abstract
Domain adaptation generalizes a learning machine across source domain and target domain under different distributions. Recent studies reveal that deep neural networks can learn transferable features generalizing well to similar novel tasks for domain adaptation. However, as deep features eventually transition from general to specific along the network, feature transferability drops significantly in higher task-specific layers with increasing domain discrepancy. To formally reduce the dataset shift and enhance the feature transferability in task-specific layers, this paper presents a novel framework for deep adaptation networks, which generalizes deep convolutional neural networks to domain adaptation. The framework embeds the deep features of all task-specific layers to reproducing kernel Hilbert spaces (RKHSs) and optimally match different domain distributions. The deep features are made more transferable by exploring low-density separation of target-unlabeled data and very deep architectures, while the domain discrepancy is further reduced using multiple kernel learning for maximal testing power of kernel embedding matching. This leads to a minimax game framework that learns transferable features with statistical guarantees, and scales linearly with unbiased estimate of kernel embedding. Extensive empirical evidence shows that the proposed networks yield state-of-the-art results on standard visual domain adaptation benchmarks.
