---
title: "Towards Reliable and Holistic Visual In-Context Learning Prompt Selection"
information: '**Wenxiao Wu**, Jinghao Xue, Chengming Xu<sup>*</sup>, Xinwei Sun, Chen Liu, Changxin Gao, Nong Sang, Yanwei Fu, "Towards Reliable and Holistic Visual In-Context Learning Prompt Selection", NeurIPS, 2025.'
collection: publications
permalink: /publication/RH-Partial2Global
excerpt: ''
date: 2025-09-18
venue: 'NeurIPS'
paperurl: 'https://Wu-Wenxiao.github.io/files/Towards_Reliable_and_Holistic_Visual_In_Context_Learning_Prompt_Selection.pdf'
citation: ''
---
<p style="text-align: justify;font-size: 80%;">
<strong>Abstract:</strong> Visual In-Context Learning (VICL) has emerged as a prominent approach for adapting visual foundation models to novel tasks, by effectively exploiting contextual information embedded in in-context examples, which can be formulated as a global ranking problem of potential candidates. Current VICL methods, such as Partial2Global and VPR, are grounded in the similarity-priority assumption that images more visually similar to a query image serve as better in-context examples. This foundational assumption, while intuitive, lacks sufficient justification for its efficacy in selecting optimal in-context examples. Furthermore, Partial2Global constructs its global ranking from a series of randomly sampled pairwise preference predictions. Such a reliance on random sampling can lead to incomplete coverage and redundant samplings of comparisons, thus further adversely impacting the final global ranking. To address these issues, this paper introduces an enhanced variant of Partial2Global designed for reliable and holistic selection of in-context examples in VICL. Our proposed method, dubbed RH-Partial2Global, leverages a jackknife conformal prediction-guided strategy to construct reliable alternative sets and a covering design-based sampling approach to ensure comprehensive and uniform coverage of pairwise preferences. Extensive experiments demonstrate that RH-Partial2Global achieves excellent performance and outperforms Partial2Global across diverse visual tasks.
</p>

<div style="display: flex; align-items: center; gap: 20px; font-size: 90%;">
    <a href="https://Wu-Wenxiao.github.io/files/Towards_Reliable_and_Holistic_Visual_In_Context_Learning_Prompt_Selection.pdf">[Paper]</a>
    <a href="https://github.com/Wu-Wenxiao/RH-Partial2Global">[Code]</a>
</div>

<strong style="display: block; margin-top: 1.5em; margin-bottom: 0.5em;">Bibtex</strong>
<pre style="background-color: #f6f8fa; border: 1px solid #ddd; padding: 16px; border-radius: 8px; font-size: 70%; overflow-x: auto; margin-top: 0;">
None
</pre>
