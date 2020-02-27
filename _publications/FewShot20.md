---
title: "Few-Shot Video Classification via Temporal Alignment"
collection: publications
permalink: /publications/FewShot20
venue: "Conference on Computer Vision and Pattern Recognition (CVPR), 2020"
date: 2020-06-16
citation: 'Kaidi Cao, Jingwei Ji*, <b>Zhangjie Cao</b>*, Chien-Yi Chang, Juan Carlos Niebles. <i>Conference on Computer Vision and Pattern Recognition</i> <b>CVPR 2020</b>.'
---

[[Arxiv]](https://arxiv.org/pdf/1906.11415.pdf)

## Abstract
There is a growing interest in learning a model which
could recognize novel classes with only a few labeled examples. In this paper, we propose Temporal Alignment
Module (TAM), a novel few-shot learning framework that
can learn to classify a previous unseen video. While most
previous works neglect long-term temporal ordering information, our proposed model explicitly leverages the temporal ordering information in video data through temporal
alignment. This leads to strong data-efficiency for few-shot
learning. In concrete, TAM calculates the distance value
of query video with respect to novel class proxies by averaging the per frame distances along its alignment path.
We introduce continuous relaxation to TAM so the model
can be learned in an end-to-end fashion to directly optimize
the few-shot learning objective. We evaluate TAM on two
challenging real-world datasets, Kinetics and SomethingSomething-V2, and show that our model leads to significant
improvement of few-shot video classification over a wide
range of competitive baselines.
