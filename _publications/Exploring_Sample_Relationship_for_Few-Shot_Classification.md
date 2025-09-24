---
title: "Exploring Sample Relationship for Few-Shot Classification"
information: 'Xingye Chen<sup>&dagger;</sup>, **Wenxiao Wu**<sup>&dagger;</sup>, Li Ma, Xinge You, Changxin Gao, Nong Sang, Yuanjie Shao<sup>*</sup>, "Exploring Sample Relationship for Few-Shot Classification", Pattern Recognition, 2025: 111089.'
collection: publications
permalink: publication/SRE
excerpt: ''
date: 2025-03-01
venue: 'Pattern Recognition'
paperurl: 'https://Wu-Wenxiao.github.io/files/Exploring_Sample_Relationship_for_Few-Shot_Classification.pdf'
citation: ''
---
<p style="text-align: justify;font-size: 80%;">
<strong>Abstract:</strong> Few-shot classification (FSC) is a challenging problem, which aims to identify novel classes with limited samples. Most existing methods employ vanilla transfer learning or episodic meta-training to learn a feature extractor, and then measure the similarity between the query image and the few support examples of novel classes. However, these approaches merely learn feature representations from individual images, overlooking the exploration of the interrelationships among images. This neglect can hinder the attainment of more discriminative feature representations, thus limiting the potential improvement of few-shot classification
performance. To address this issue, we propose a Sample Relationship Exploration (SRE) module comprising the Sample-level Attention (SA), Explicit Guidance (EG) and Channel-wise Adaptive Fusion (CAF) components, to learn discriminative category-related features. Specifically, we first employ the SA component to explore
the similarity relationships among samples and obtain aggregated features of similar samples. Furthermore, to enhance the robustness of these features, we introduce the EG component to explicitly guide the learning of sample relationships by providing an ideal affinity map among samples. Finally, the CAF component is adopted
to perform weighted fusion of the original features and the aggregated features, yielding category-related embeddings. The proposed method is a plug-and-play module which can be embedded into both transfer learning and meta-learning based few-shot classification frameworks. Extensive experiments on benchmark datasets show that the proposed module can effectively improve the performance over baseline models, and also perform competitively against the state-of-the-art algorithms.
</p>

<div style="display: flex; align-items: center; gap: 20px; font-size: 90%;">
    <a href="https://Wu-Wenxiao.github.io/files/Exploring_Sample_Relationship_for_Few-Shot_Classification.pdf">[Paper]</a>
    <a href="https://github.com/Chenguoz/SRE">[Code]</a>
</div>

<div style="background-color: #f6f8fa; border: 1px solid #ddd; padding: 16px; border-radius: 8px;">
  <strong>Bibtex</strong>
  <pre style="white-space: pre-wrap; word-break: break-all; font-size: 70%; margin-top: 10px; margin-bottom: 0;">
@article{chen2025exploring,
  title={Exploring sample relationship for few-shot classification},
  author={Chen, Xingye and Wu, Wenxiao and Ma, Li and You, Xinge and Gao, Changxin and Sang, Nong and Shao, Yuanjie},
  journal={Pattern Recognition},
  volume={159},
  pages={111089},
  year={2025},
  publisher={Elsevier}
}
  </pre>
</div>