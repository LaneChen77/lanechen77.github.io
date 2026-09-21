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
# About Me

I am a master's student in Statistics at Fudan University, advised by Prof. Jian Wang. I received my B.S. in Data Science from Fudan University.

My research interests include autonomous driving, vision-language models, depth estimation, and embodied AI.

My long-term vision is to build AI systems that can understand and interact with the physical world, bridging digital intelligence and physical systems to create tangible value in the real world.

# 🔥 News

- *2026.09*: &nbsp; Posted a reproducibility note for **BEV-VLM** after identifying a bug in the Max-V1 backbone implementation used in its experiments. The currently reported results should not be considered reliable until the implementation is corrected and the experiments are rerun.
- *2025.10*: &nbsp; Released [**Max-V1: Less is More**](https://arxiv.org/abs/2510.00060), a lean vision-language model for end-to-end autonomous driving.
- *2025.09*: &nbsp; Released [**BEV-VLM**](https://arxiv.org/abs/2509.25249), which studies trajectory planning through a unified BEV abstraction.

<span class='anchor' id='publications'></span>
# 📝 Publications

### [BEV-VLM: Trajectory Planning via Unified BEV Abstraction](https://arxiv.org/abs/2509.25249)

**Guancheng Chen**<sup>*</sup>, Sheng Yang<sup>*</sup>, Tong Zhan, Jian Wang<br>
*arXiv preprint arXiv:2509.25249, 2025*<br>
[[Paper](https://arxiv.org/abs/2509.25249)]

> **Reproducibility note (September 2026).** The current BEV-VLM implementation uses Max-V1 as its backbone. I have identified a code-level bug in the Max-V1 backbone implementation used by BEV-VLM, which affects the validity of the experiments. Therefore, the results currently reported in BEV-VLM should not be treated as reliable until the issue is corrected and the experiments are rerun. Regardless of where a bug occurs within an integrated system, validating every component and the final results is the responsibility of the authors. As a co-author, I take responsibility for my part in not identifying this issue before release, and I am disclosing it here so that readers do not rely on the current numbers. Any corrected claims should be based on a fixed implementation and complete experimental reruns.

### [Less is More: Lean yet Powerful Vision-Language Model for Autonomous Driving](https://arxiv.org/abs/2510.00060)

Sheng Yang, Tong Zhan, **Guancheng Chen**, Yanfeng Lu, Jian Wang<br>
*arXiv preprint arXiv:2510.00060, 2025*<br>
[[Paper](https://arxiv.org/abs/2510.00060)]

<small>* Equal contribution.</small>

# 💡 Current Research

I am currently exploring visual autoregressive (VAR) modeling for monocular depth estimation, with a focus on coarse-to-fine depth prediction.

# 📖 Education

- *2025.09 - Present*, **M.S. in Statistics**, Fudan University
- *2021.09 - 2025.06*, **B.S. in Data Science**, Fudan University
