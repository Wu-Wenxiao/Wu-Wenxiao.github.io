---
title: "Improving the Generalization of MAML in Few-Shot Classification via Bi-Level Constraint"
collection: publications
permalink: publication/Improving_the_Generalization_of_MAML_in_Few-Shot_Classification_via_Bi-Level_Constraint
excerpt: ''
date: 2022-12-27
venue: 'Journal 1'
paperurl: 'https://Wu-Wenxiao.github.io/files/Improving_the_Generalization_of_MAML_in_Few-Shot_Classification_via_Bi-Level_Constraint.pdf'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
<p style="text-align: justify;font-size: 80%;">
<strong>Abstract:</strong> Few-shot classification (FSC), which aims to identify novel classes in the presence of a few labeled samples, has drawn vast attention in recent years. One of the representative few-shot classification methods is model-agnostic meta-learning (MAML), which focuses on learning an initialization that can quickly adapt to novel categories with a few annotated samples. However, due to insufficient samples, MAML can easily fall into the dilemma of overfitting. Most existing MAML-based methods either improve the inner-loop update rule to achieve better generalization or constrain the outer-loop optimization to learn a more desirable initialization, without considering improving the two optimization processes jointly, resulting in unsatisfactory performance. In this paper, we propose a bi-level constrained MAML (BLC-MAML) method for few-shot classification. Specifically, in the innerloop optimization, we introduce a supervised contrastive loss to constrain the adaptation procedure, which can effectively increase the intra-class aggregation and inter-class separability, thus improving the generalization of the adapted model. In the case of the outer loop, we propose a cross-task metric (CTM) loss to constrain the adapted model to perform well on the different few-shot task. The CTM loss can enforce the adapted model to learn more discriminative and generalized feature representations, further boosting the generalization of the learned initialization. By simultaneously constraining the bi-level optimization procedure, the proposed BLC-MAML can learn an initialization with better generalization. Extensive experiments on several FSC benchmarks show that our method can effectively improve the performance of MAML under both the within-domain and crossdomain settings, and also perform favorably against the state-of-the-art FSC algorithms.
</p>

[Download paper here](https://Wu-Wenxiao.github.io/files/Improving_the_Generalization_of_MAML_in_Few-Shot_Classification_via_Bi-Level_Constraint.pdf)

<pre><strong>Bibtex</strong>
<div style="background-color: #f6f8fa; border: 1px solid #ddd; padding: 16px; border-radius: 8px;font-size: 70%">
@article{shao2022improving,
  title={Improving the generalization of MAML in few-shot classification via bi-level constraint},
  author={Shao, Yuanjie and Wu, Wenxiao and You, Xinge and Gao, Changxin and Sang, Nong},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  volume={33},
  number={7},
  pages={3284--3295},
  year={2022},
  publisher={IEEE}
}
</div>
</pre>