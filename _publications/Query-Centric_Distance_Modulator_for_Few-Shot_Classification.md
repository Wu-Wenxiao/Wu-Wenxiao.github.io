---
title: "Query-Centric Distance Modulator for Few-Shot Classification"
collection: publications
permalink: /publication/QCDM
excerpt: ''
date: 2010-10-01
venue: 'Pattern Recognition'
paperurl: 'https://Wu-Wenxiao.github.io/files/Query-Centric_Distance_Modulator_for_Few-Shot_Classification.pdf'
citation: ''
---
<p style="text-align: justify;font-size: 80%;">
<strong>Abstract:</strong> Few-shot classification (FSC) is a highly challenging task, as only a small number of labeled samples are available when identifying new categories. Distance metric learning-based methods have emerged as a prominent approach to FSC, which typically use a distance function to measure the difference between query and support samples for identifying the class membership of the query sample. However, these methods simply treat each channel difference between query and support features equally when computing the class scores. Since different channels in the learned feature seek for different patterns, these distance metrics fail to consider that different channels are of different importance to FSC, and thus cannot accurately measure the similarity between samples. To address this issue, we propose a Query-Centric Distance Modulator (QCDM) to generate query-related weights for each channel difference adaptively. Specifically, since the distribution of difference between a query sample and all support samples in a particular channel can reflect the importance of this channel to the classification of the query sample, we take this difference vector as input and generate a query-specific channel weight through a meta-network. QCDM can guide FSC models to focus on discriminative channel differences and achieve better generalization. QCDM is a plug-and-play module that can be seamlessly integrated with existing distance metric learning-based FSC methods. Extensive experimental results indicate that our method can effectively improve the performance of distance metric learning-based FSC methods.
</p>

<div style="display: flex; align-items: center; gap: 20px; font-size: 90%;">
    <a href="https://Wu-Wenxiao.github.io/files/Query-Centric_Distance_Modulator_for_Few-Shot_Classification.pdf">[Paper]</a>
    <a href="https://github.com/Wu-Wenxiao/QCDM">[Code]</a>
</div>

<pre><strong>Bibtex</strong>
<div style="background-color: #f6f8fa; border: 1px solid #ddd; padding: 16px; border-radius: 8px;font-size: 70%">
@article{wu2024query,
  title={Query-centric distance modulator for few-shot classification},
  author={Wu, Wenxiao and Shao, Yuanjie and Gao, Changxin and Xue, Jing-Hao and Sang, Nong},
  journal={Pattern Recognition},
  volume={151},
  pages={110380},
  year={2024},
  publisher={Elsevier}
}
</div>
</pre>