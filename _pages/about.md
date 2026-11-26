---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**Focus:** `Audio-Visual Learning` · `Speech Generation` · `Full-Duplex Interaction`

I am an undergraduate student in the **[Turing Class](http://www.cs.zju.edu.cn/turingclass_en/)** at **[Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/)**, **[Zhejiang University](https://www.zju.edu.cn/english/)**, majoring in Artificial Intelligence and expecting to graduate in June 2027. I am currently a **Research Intern at Alibaba Group's Qwen Division**, working on speech generation and full-duplex speech language models.

My research interests include **audio-visual representations and generation**, **full-duplex interaction**, **multimodal learning**, and **interactive world models**. My recent work spans speech codecs, spatial audio generation, long-form speech evaluation, and controllable prosody.

I am always open to potential collaborations and opportunities. Feel free to reach out.

# 🔥 News
<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2026</div>
    <div class="timeline-content">CSAVocoder was accepted to the <strong>EMNLP 2026 Main Conference</strong>. I presented the work in Budapest.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.09</div>
    <div class="timeline-content">Joined <strong>Alibaba Group's Qwen Division</strong> as a research intern.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.07</div>
    <div class="timeline-content">Joined <strong>The Chinese University of Hong Kong, Shenzhen</strong> as a research assistant with Zhizheng Wu.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.04</div>
    <div class="timeline-content">🎉 One dataset paper accepted by <strong><a href="https://2026.aclweb.org/">ACL 2026 Findings</a></strong>.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.01</div>
    <div class="timeline-content">Started my research internship at <a href="https://vuilabs.cn/">VUI Labs</a>, working on speech synthesis and neural speech codecs.</div>
  </div>
</div>

# 📝 Publications

Selected publications and manuscripts. <sup>*</sup> Equal contribution. [Full list on Google Scholar](https://scholar.google.com/citations?user=JSeLOUwAAAAJ&hl=zh-CN).

<div class='paper-box'><div class='paper-box-text' markdown="1">

[Interpreting and Evaluating Dynamic-Rate Speech Codec Boundaries](https://arxiv.org/abs/2609.36951)

**Han Wang**<sup>*</sup>, Jiaqi Li<sup>*</sup>, Yingda Shen, Yuxiang Wang, Zhizheng Wu.

**Submitted to ICASSP 2027** · arXiv:2609.36951

Analyzed what dynamic codec boundaries encode and tested syllable- and phoneme-based segmentation under matched frame rates.
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026 Main</div><img src='images/vocoder.png' alt="CSAVocoder architecture" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CSAVocoder: A Causal Spatial Audio Vocoder Towards Real-Time Spatial Audio Generation](https://aclanthology.org/2026.emnlp-main.496/)

Zhiyuan Zhu<sup>*</sup>, **Han Wang**<sup>*</sup>, Wenxiang Guo, Yu Zhang, Changhao Pan, Rui Yang, Zhou Zhao.

**EMNLP 2026 Main Conference**, pp. 11394–11416

Co-developed a causal vocoder for real-time spatial audio generation with pose conditioning and stateful streaming inference.
</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

**DelexWav: An Audible Representation of Fine-Grained Prosody**

Haiyang Sun, **Han Wang**, Chenyang Le, Yi Wang, Yanmin Qian.

**Submitted to ICLR 2027**

A waveform representation that preserves fine-grained prosody while suppressing lexical content, enabling direct listening and local editing.
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2026</div><img src='images/aoe.png' alt="LFS-Bench overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Comprehensive Benchmarking of Long-Form Speech Generation in Diverse Scenarios](https://aclanthology.org/2026.findings-acl.112/)

Changhao Pan<sup>*</sup>, Rui Yang<sup>*</sup>, **Han Wang**<sup>*</sup>, et al.

**Findings of ACL 2026**, pp. 2365–2400

Co-developed **LFS-Bench**, a benchmark for semantic consistency, generation stability, and perceptual quality in long-form speech synthesis.
</div></div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

[MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations](https://proceedings.neurips.cc/paper_files/paper/2025/hash/d6ce4d1c760694b4cd9879710f9e7cd0-Abstract-Datasets_and_Benchmarks_Track.html)

Wenxiang Guo, Changhao Pan, Zhiyuan Zhu, Xintong Hu, Yu Zhang, Li Tang, Rui Yang, **Han Wang**, et al.

**NeurIPS 2025, Datasets and Benchmarks Track**, vol. 38
</div></div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

[A Multimodal Evaluation Framework for Spatial Audio Playback Systems: From Localization to Listener Preference](https://doi.org/10.1145/3746027.3755571)

Changhao Pan, Wenxiang Guo, Yu Zhang, Zhiyuan Zhu, Zhetao Chen, **Han Wang**, Zhou Zhao.

**ACM Multimedia 2025**, pp. 7006–7015
</div></div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

[Luna-TTS Family Technical Report](https://arxiv.org/abs/2608.11593)

Feng Yin, Shuai Shi, Junjie Zheng, Kechenying Zhou, Yiqiu Wang, Chenyang He, Qiuhua Jiang, Mengxiao Bi, Yanmin Qian, Mingxin Chen, Xun Gong, Tianteng Gu, Bing Han, Peng Jiang, Chenda Li, Haiyang Sun, **Han Wang**, Wei Wang, Yi Wang, Leying Zhang, Wangyou Zhang, Chushu Zhou.

**Technical Report, 2026** · arXiv:2608.11593
</div></div>

# 🎖 Honors and Awards
- *2023–2024, 2025–2026* First-Class Scholarship, Zhejiang University
- *2024–2025* Second-Class Scholarship, Zhejiang University
- *2023–2024, 2024–2025* Basic Disciplines Top-notch Scholarship, Second Prize, Zhejiang University
- *2024–2025* Project Leader, National Student Research Training Program, China

# 📖 Education
- *2023.09 – 2027.06 (expected)* B.Sc. in Artificial Intelligence, Turing Class, Chu Kochen Honors College, Zhejiang University.<br>**GPA: 3.95 / 4.3** · **Class Rank: Top 5%**

<span class='anchor' id='-internships'></span>

# 💻 Research Experience

## Research Intern, Alibaba Group
*2026.09 – Present* · Qwen Division, Hangzhou, China

I work on continuous-latent speech generation, with an emphasis on audio autoencoders and training stability. I also investigate streaming audio tokenization and full-duplex speech language models, and contribute to large-scale text-to-speech training.

## Research Assistant, The Chinese University of Hong Kong, Shenzhen
*2026.07 – 2026.09*<br>Supervisor: **Zhizheng Wu**.

I independently led a study of dynamic-rate speech codecs, designing boundary-alignment analyses and rate-matched reconstruction experiments to test which linguistic units make useful codec boundaries.

## Research Intern, VUI Labs
*2026.01 – 2026.06* · Hangzhou, China<br>Supervisor: **[Yanmin Qian](https://scholar.google.com/citations?hl=en&user=guG9lxgAAAAJ)**.

I contributed to distributed pretraining for **Luna-TTS**, which reached **No. 1 on TTS Arena**, and developed speech tokenizers for improved reconstruction. I also prepared training data and trained neural speech codecs for **DelexWav**, which disentangles prosody from linguistic content for controllable speech generation.

## Research Assistant, Zhejiang University
*2024.04 – 2026.02* · Multimodal Speech Synthesis Laboratory<br>Supervisor: **[Zhou Zhao](https://scholar.google.com/citations?user=IIoFY90AAAAJ&hl=zh-CN&oi=ao)**.

I co-developed **CSAVocoder**, contributing to causal model implementation, streaming inference, ablations, and spatial audio evaluation, and presented the work at EMNLP 2026 in Budapest. I also designed evaluation protocols and analyzed failure modes for long-form speech generation across models and scenarios.
