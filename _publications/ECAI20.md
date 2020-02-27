---
title: "Improving Unsupervised Domain Adaptation with Variational Information Bottleneck"
collection: publications
permalink: /publications/ECAI20
venue: "European Conference on Artificial Intelligence (ECAI), 2020"
date: 2020-06-11
citation: 'Yuxuan Song, Lantao Yu, <b>Zhangjie Cao</b>, Zhiming Zhou, Jian Shen, Shuo Shao, Weinan Zhang, Yong Yu. <i>European Conference on Artificial Intelligence</i> <b>ECAI 2020</b>.'
---

[[Arxiv]](https://arxiv.org/pdf/1911.09310.pdf)

## Abstract
Domain adaptation aims to leverage the supervision signal of source domain to obtain an accurate model for target domain,
where the labels are not available. To leverage and adapt the label
information from source domain, most existing methods employ a
feature extracting function and match the marginal distributions of
source and target domains in a shared feature space. In this paper,
from the perspective of information theory, we show that representation matching is actually an insufficient constraint on the feature
space for obtaining a model with good generalization performance in
target domain. We then propose variational bottleneck domain adaptation (VBDA), a new domain adaptation method which improves
feature transferability by explicitly enforcing the feature extractor to
ignore the task-irrelevant factors and focus on the information that is
essential to the task of interest for both source and target domains.
Extensive experimental results demonstrate that VBDA significantly
outperforms state-of-the-art methods across three domain adaptation
benchmark datasets.
