---
title: "AlignFlow: Cycle Consistent Learning from Multiple Domains via Normalizing Flows"
collection: publications
permalink: /publications/AlignFlow20
venue: "AAAI Conference on Artificial Intelligence (AAAI), 2020"
date: 2020-2-7
citation: 'Aditya Grover, Christopher Chute, Rui Shu, <b>Zhangjie Cao</b>, Stefano Ermon. <i>AAAI Conference on Artificial Intelligence</i> <b>AAAI 2020</b>.'
---

[[Arxiv]](https://arxiv.org/pdf/1905.12892.pdf)

## Abstract
Given datasets from multiple domains, a key challenge is to
efficiently exploit these data sources for modeling a target
domain. Variants of this problem have been studied in many
contexts, such as cross-domain translation and domain adaptation. We propose AlignFlow, a generative modeling framework
that models each domain via a normalizing flow. The use of
normalizing flows allows for a) flexibility in specifying learning objectives via adversarial training, maximum likelihood
estimation, or a hybrid of the two methods; and b) learning
and exact inference of a shared representation in the latent
space of the generative model. We derive a uniform set of
conditions under which AlignFlow is marginally-consistent
for the different learning objectives. Furthermore, we show
that AlignFlow guarantees exact cycle consistency in mapping
datapoints from a source domain to target and back to the
source domain. Empirically, AlignFlow outperforms relevant
baselines on image-to-image translation and unsupervised domain adaptation and can be used to simultaneously interpolate
across the various domains using the learned representation.
