---
permalink: /
title: ""
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

# 👨 About Me

I received my M.Eng. degree (2026) and B.Eng. degree (2023) from MC2 Lab at [Beihang University](https://www.buaa.edu.cn/), supervised by [Prof. Shengxi Li](https://scholar.google.com/citations?user=GNxRL-gAAAAJ&hl=zh-CN) and [Prof. Mai Xu](https://scholar.google.com/citations?user=JdhDuXAAAAAJ&hl=en). I am planning to commence my PhD studies at the Hong Kong University of Science and Technology (HKUST) in Fall 2026, under the joint supervision of Prof. [Pan Wang](https://www.tudelft.nl/en/ide/about-ide/people/wang-p) and Prof. [Yike Guo](https://facultyprofiles.hkust.edu.hk/profiles.php?profile=yike-guo-yikeguo). I am broadly interested in applied computer vision, generative AI and world models.


My research interests lie in computer vision and generative AI, with a particular focus on:
* **World Model**
* **Generative Image/Video Compression**
* **Image/Video Coding for Machines**



[Email](mailto:zifuzhang531@gmail.com) / [GitHub](https://github.com/bblgbr) / [CV]({{ site.baseurl }}/assets/ZZF_CV.pdf)

<br>

# 💻 Experience

- **12/2025 ~ Present**, Research Intern at Multimedia Lab, Taobao, Alibaba Group, supervised by [Dr. Ying Chen](https://scholar.google.com/citations?user=NpTmcKEAAAAJ&hl=en).
- **05/2025 ~ 12/2025**, Research Assistant at Tsinghua University, supervised by [Dr. Tongda Xu](https://scholar.google.com/citations?user=LO8GS7sAAAAJ&hl=en) and [Prof. Yan Wang](https://yanwang202199.github.io/).
- **09/2023 ~ 01/2026**, Earned Master's degree in School of Electronics and Information Engineering at Beihang University, supervised by [Prof. Shengxi Li](https://scholar.google.com/citations?user=GNxRL-gAAAAJ&hl=zh-CN) and [Prof. Mai Xu](https://scholar.google.com/citations?user=JdhDuXAAAAAJ&hl=en).
- **09/2019 ~ 06/2023**, Earned Bachelor's degree in School of Electronic Information Engineering at Beihang University.

<br>

# 🏆 Honors and Awards

- **China National Scholarship**, 2025.
- **BYD Inc. Scholarship**, 2025.
- **Outstanding Graduate of Beijing**, 2025.
- **Beihang Outstanding Master Dissertation Award**, 2025.
- **Multiple Merit Scholarships, Beihang University**, 2019-2025.

<br>

# 📚 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='{{ site.baseurl }}/images/icml2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2512.20901" style="font-size: 22px; color: #483D8B; text-decoration: none">**Benchmarking and Enhancing VLM for Compressed Image Understanding**</a><br>
<span style="font-size: 18px;">**Zifu Zhang**, Tongda Xu†, Siqi Li, Shengxi Li†, Yue Zhang, Mai Xu, Yan Wang†</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2512.20901)   [**Code**](https://github.com/bblgbr/CompressVLMBench)</span>

<span style="font-size: 16px;"> We present a comprehensive benchmark designed to evaluate the ability of VLMs to understand and process compressed images. Based on this, we propose a lightweight VLM adaptor that enhances VLM performance on compressed images across diverse codecs and bitrate levels.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2026</div><img src='{{ site.baseurl }}/images/tip2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2511.08915" style="font-size: 22px; color: #483D8B; text-decoration: none">**Machines Serve Human: A Novel Variable Human-machine Collaborative Compression Framework**</a><br>
<span style="font-size: 18px;">**Zifu Zhang**, Shengxi Li†, Xiancheng Sun, Mai Xu, Zhengyuan Liu, Jingyuan Xia</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2511.08915)   [**Code**](https://github.com/bblgbr/Diff-FCHM)</span>

<span style="font-size: 16px;"> We propose the first successful attempt by a novel collaborative compression method based on the machine-vision-oriented compression, named as diffusion-prior based feature compression for human and machine visions (Diff-FCHM).</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2025</div><img src='{{ site.baseurl }}/images/tip2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11202356" style="font-size: 22px; color: #483D8B; text-decoration: none">**Hierarchical Semantic Compression for Consistent Image Semantic Restoration**</a><br>
<span style="font-size: 18px;">Shengxi Li (Supervisor), **Zifu Zhang**, Mai Xu, Lai Jiang, Yufan Liu, Ce Zhu</span><br>
<span style="font-size: 18px;">[**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11202356)   [**Code**](https://github.com/bblgbr/HSC-TIP2025)</span>

<span style="font-size: 16px;"> We propose a novel hierarchical semantic compression (HSC) framework that purely operates within intrinsic semantic spaces from generative models, which is able to achieve efficient compression for consistent semantic restoration. </span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2026 Oral</div><img src='{{ site.baseurl }}/images/icassp2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://ieeexplore.ieee.org/document/11461422/" style="font-size: 22px; color: #483D8B; text-decoration: none">**FC-FORMER: Efficient Feature Coding for Machines via a Hybrid CNN-Transformer Architecture**</a><br>
<span style="font-size: 18px;">Zhengyuan Liu\*, **Zifu Zhang\***, Shengxi Li†, Tao Xu, Mai Xu, Xin Deng</span><br>
<span style="font-size: 18px;">[**Paper**](https://ieeexplore.ieee.org/document/11461422/)</span>

<span style="font-size: 16px;"> We propose in this paper a novel feature compression architecture based on a hybrid of Transformer and convolutional neural network (CNN) architectures, thus named as FC-Former that enhances the capability of feature extraction, achieving the state-of-the-art performances.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SPL 2025</div><img src='{{ site.baseurl }}/images/spl2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11059865" style="font-size: 22px; color: #483D8B; text-decoration: none">**Continuous Patch Stitching for Block-wise Image Compression**</a><br>
<span style="font-size: 18px;">**Zifu Zhang**, Shengxi Li†, Henan Liu, Mai Xu, Ce Zhu</span><br>
<span style="font-size: 18px;">[**Paper**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11059865)   [**Code**](https://github.com/bblgbr/SPL-CPS)</span>

<span style="font-size: 16px;"> We propose a novel continuous patch stitching (CPS) framework for block-wise image compression that is able to achieve seamlessly patch stitching and mathematically eliminate block artefact, thus capable of significantly reducing the required computing resources when compressing images. </span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIP 2024 Oral</div><img src='{{ site.baseurl }}/images/icip2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://ieeexplore.ieee.org/document/10647629/" style="font-size: 22px; color: #483D8B; text-decoration: none">**Hybrid Single Input and Multiple Output Method For Compressing Features Towards Machine Vision Tasks**</a><br>
<span style="font-size: 18px;">**Zifu Zhang**, Shengxi Li, Tie Liu, Mai Xu, Tao Xu, Zhenyu Guan</span><br>
<span style="font-size: 18px;">[**Paper**](https://ieeexplore.ieee.org/document/10647629/)   [**Code**](https://github.com/bblgbr/VCM-SIMO)</span>

<span style="font-size: 16px;"> This paper introduces a simple yet effective architecture called hybrid single input and multiple output (H-SIMO) for VCM, which can significantly reduce the redundancy across scales of features. </span>

</div>
</div>

<!-- # 📑 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='{{ site.baseurl }}/images/mmgenbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2411.14062" style="font-size: 22px; color: #483D8B; text-decoration: none">**MMGenBench: Fully Automatically Evaluating LMMs from the Text-to-Image Generation Perspective**</a><br>
<span style="font-size: 18px;">Hailang Huang, Yong Wang, Zixuan Huang, **Huaqiu Li**, Tongwen Huang, Xiangxiang Chu, Richong Zhang†</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2411.14062)   [**Code**](https://github.com/lerogo/MMGenBench)</span>

<span style="font-size: 18px;">- We propose the MMGenBench-Pipeline, a straightforward and fully automated evaluation pipeline. This involves generating textual descriptions from input images, using these descriptions to create auxiliary images via text-to-image generative models, and then comparing the original and generated images.</span>

</div>
</div> -->
