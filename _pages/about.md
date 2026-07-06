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

<style>
  .publication-toggle {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.35rem;
    margin: 0.4rem 0 1.1rem;
    padding: 0.45rem 0.9rem;
    border: 1px solid #d0d7de;
    border-radius: 6px;
    background: #fff;
    color: #24292f;
    font-size: 0.88rem;
    line-height: 1.2;
    cursor: pointer;
  }

  .publication-toggle:hover,
  .publication-toggle:focus {
    background: #f6f8fa;
    border-color: #afb8c1;
  }
</style>

<span class='anchor' id='about-me'></span>

I am an incoming Ph.D. student at Shanghai Jiao Tong University (SJTU), jointly trained with the Shanghai Artificial Intelligence Laboratory. My Ph.D. advisors are Jiang Wu, Weijia Li, and Conghui He. Before that, I received my Master's degree from Beihang University (BUAA), where I was supervised by Associate Professor Qian Yu.

My research interests include computer vision, 3D generation, agentic AI, and world models.

# 🔍 Research Interests
- **Computer Vision and 3D Generation**: visual generation, 3D/video generation, and multimodal visual understanding.
- **Agentic AI and World Models**: multimodal agents, planning, tool use, and world modeling.

# 🔥 News
{% comment %}
- *2026.02*: &nbsp;🎉🎉 RxnID was accepted by ECCV 2026.
- *2026.02*: &nbsp;🎉🎉 RxnCaption was accepted by CVPR 2026.
{% endcomment %}
- *2025.09*: &nbsp;🎉🎉 ViewCraft3D was accepted by NeurIPS 2025.
- *2024.12*: &nbsp;🎉🎉 TrackGo was accepted by AAAI 2025.

# 📝 Publications
> <sup>*</sup> indicate co-first author, <sup>†</sup> indicate corresponding author

## Generative AI

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/viewcraft3D.png' alt="ViewCraft3D" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ViewCraft3D: High-Fidelity and View-Consistent 3D Vector Graphics Synthesis**

**Chuang Wang<sup>*</sup>**, Haitao Zhou<sup>*</sup>, Ling Luo<sup>†</sup>, Qian Yu<sup>†</sup>

[**[Paper]**](https://arxiv.org/pdf/2505.19492)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/trackgo.png' alt="TrackGo" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TrackGo: A Flexible and Efficient Method for Controllable Video Generation**

Haitao Zhou<sup>*</sup>, **Chuang Wang<sup>*</sup>**, Rui Nie, Jinxiao Lin, Dongdong Yu, Qian Yu<sup>†</sup>, Changhu Wang<sup>†</sup>

[**[Paper]**](https://arxiv.org/pdf/2408.11475)
</div>
</div>

<button id="publication-toggle" class="publication-toggle" type="button" aria-expanded="false" aria-controls="additional-publications">
  Show previous publications
</button>

<div id="additional-publications" hidden markdown="1">

## Previous Work

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/rxncaption.png' alt="RxnCaption" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RxnCaption: Reformulating Reaction Diagram Parsing as Visual Prompt Guided Captioning**

Jiahe Song<sup>*</sup>, **Chuang Wang<sup>*</sup>**, Bowen Jiang<sup>*</sup>, Yinfan Wang, Hao Zheng, Xingjian Wei, Chengjin Liu, Junyuan Gao, Yubin Wang, Lijun Wu, Jiang Wu<sup>†</sup>, Qian Yu<sup>†</sup>, Conghui He<sup>†</sup>

[**[Paper]**](https://arxiv.org/pdf/2511.02384)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/idtvp.png' alt="Molecular Identifier Visual Prompt" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Molecular Identifier Visual Prompt and Verifiable Reinforcement Learning for Chemical Reaction Diagram Parsing**

Jiahe Song<sup>*</sup>, **Chuang Wang<sup>*</sup>**, Yinfan Wang, Hao Zheng, Rui Nie, Bowen Jiang, Xingjian Wei, Junyuan Gao, Yubin Wang, Bin Wang, Lijun Wu, Jiang Wu, Qian Yu, Conghui He

[**[Paper]**](https://arxiv.org/abs/2603.15011)
</div>
</div>

</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var toggle = document.getElementById("publication-toggle");
    var additionalPublications = document.getElementById("additional-publications");

    if (!toggle || !additionalPublications) {
      return;
    }

    toggle.addEventListener("click", function () {
      var isExpanded = toggle.getAttribute("aria-expanded") === "true";

      additionalPublications.hidden = isExpanded;
      toggle.setAttribute("aria-expanded", String(!isExpanded));
      toggle.textContent = isExpanded ? "Show previous publications" : "Hide previous publications";
    });
  });
</script>

# 🎖 Honors and Awards
- *2026.06* Outstanding Graduate of Beihang University (Master's).
- *2023.06* Outstanding Graduate of Beihang University (Bachelor's).

# 📖 Education
- *2026.09 - incoming*, Ph.D. student at Shanghai Jiao Tong University, jointly trained with Shanghai Artificial Intelligence Laboratory.
- *2023.09 - 2026.06*, M.S. student, School of Software, Beihang University.
- *2018.09 - 2023.06*, B.S. student, School of Software, Beihang University.
