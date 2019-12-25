---
title: "Depth-Adaptive Transformer"
collection: publications
permalink: /publication/depth-adaptive-transformer
excerpt: "Maha Elbayad, **Jiatao Gu**, Edouard Grave, Michael Auli"
date: 2020-04-26
venue: 'International Conference on Learning Representations (ICLR)'
---


**Abstract** <br>
State of the art sequence-to-sequence models for large scale tasks perform a fixed number of computations for each input sequence regardless of whether it is easy or hard to process. In this paper, we train Transformer models which can make output predictions at different stages of the network and we investigate different ways to predict how much computation is required for a particular sequence. Unlike dynamic computation in Universal Transformers, which applies the same set of layers iteratively, we apply different layers at every step to adjust both the amount of computation as well as the model capacity. On IWSLT German-English translation our approach matches the accuracy of a well tuned baseline Transformer while using less than a quarter of the decoder layers.
[[paper]](https://arxiv.org/pdf/1910.10073.pdf) [code]

Please cite as:
```bibtex
@article{elbayad2019depth,
  title={Depth-Adaptive Transformer},
  author={Elbayad, Maha and Gu, Jiatao and Grave, Edouard and Auli, Michael},
  journal={8th International Conference on Learning Representations, {ICLR} 2020,
           Addis Ababa, Ethiopia, April 26-30, 2020, Conference Track Proceedings},
  year={2020}
}
```