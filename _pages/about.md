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

# 🧑 About Me

I am currently a **3rd-year** Master's student at [Tsinghua Shenzhen International Graduate School (SIGS)](https://www.sigs.tsinghua.edu.cn/), majoring in Electronic Information (Artificial Intelligence) under the supervision of [Prof. Haoqian Wang](https://www.sigs.tsinghua.edu.cn/whq/). Previously, I earned my Bachelor's Degree in Aircraft Control and Information Engineering from Beihang University in Fall 2023.

My research interests lie in computer vision and generative AI, with a particular focus on:
* **Efficient Video Generation**
* **Controllable Video Generation**
* **Low-level Vision (Image & Video Restoration)**

**I am planning to commence my PhD studies in the ECE department at the Hong Kong University of Science and Technology (HKUST) in Fall 2026, under the joint supervision of Prof. [Wenhan Luo](https://whluo.github.io/) and Prof. [Ping Tan](https://pingtan.people.ust.hk/index.html).** 

[Email](mailto:lihuaqiu2025@gmail.com) / [GitHub](https://github.com/huaqlili) / [CV]({{ site.baseurl }}/assets/lihuaqiu_cv_202506.pdf) / [WeChat]({{ site.baseurl }}/images/Wechat.png)

<br>

# 💻 Experience

- **09/2025 ~ Present**, Research Intern at TongYi Lab, ATH, Alibaba Group.
- **10/2024 ~ 07/2025**, Full-time Research Intern at Amap, Machine Learning R&D Department, Alibaba Group. Supervised by [Xiangxiang Chu](https://cxxgtxy.github.io/) and [Yong Wang](https://scholar.google.com/citations?hl=en&user=rAtlzLcAAAAJ).
- **09/2023 ~ Present**, Pursuing Master's degree in Artificial Intelligence at Tsinghua University.
- **09/2019 ~ 07/2023**, Earned Bachelor's degree in Engineering from Beihang University.

<br>

# 🏆 Honors and Awards

- **Hong Kong PhD Fellowship Scheme (HKPFS)**, Hong Kong University of Science and Technology, 2026.
- **National Scholarship**, Tsinghua University, 2024-2025.
- **Excellent Graduate** of Beijing & Beihang University, 2023.
- **Multiple Merit Scholarships**, Beihang University, 2019-2023.

<br>

# 📚 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='{{ site.baseurl }}/images/ldrps.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2507.00790" style="font-size: 22px; color: #483D8B; text-decoration: none">**LD-RPS: Zero-Shot Unified Image Restoration via Latent Diffusion Recurrent Posterior Sampling**</a><br>
<span style="font-size: 18px;">**Huaqiu Li**, Yong Wang†, Tongwen Huang, Hailang Huang, Haoqian Wang†, Xiangxiang Chu</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2507.00790)   [**Code**](https://github.com/AMAP-ML/LD-RPS)</span>

<span style="font-size: 18px;">- We propose a novel, dataset-free, and unified approach through recurrent posterior sampling utilizing a pretrained latent diffusion model. Our method incorporates a multimodal understanding model to provide **semantic** priors for the generative model under a task-blind condition.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='{{ site.baseurl }}/images/iclr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2503.14535" style="font-size: 22px; color: #483D8B; text-decoration: none">**Interpretable Unsupervised Joint Denoising and Enhancement for Real-World Low-Light Scenarios**</a><br>
<span style="font-size: 18px;">**Huaqiu Li**, Xiaowan Hu, Haoqian Wang†</span><br>
<span style="font-size: 18px;">[**Openreview**](https://openreview.net/forum?id=PVHoELf5UN&noteId=tWR79MUc4B)   [**Paper**](https://arxiv.org/abs/2503.14535)   [**Code**](https://github.com/huaqlili/unsupervised-light-enhance-ICLR2025)</span>

<span style="font-size: 18px;">- We propose an interpretable, zero-reference joint denoising and low-light enhancement framework tailored for real-world scenarios. Our method derives a training strategy based on paired sub-images with varying illumination and noise levels, grounded in physical imaging principles and Retinex theory.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='{{ site.baseurl }}/images/promptsid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2502.06432" style="font-size: 22px; color: #483D8B; text-decoration: none">**Prompt-SID: Learning Structural Representation Prompt via Latent Diffusion for Single-Image Denoising**</a><br>
<span style="font-size: 18px;">**Huaqiu Li**\*, Wang Zhang\*, Xiaowan Hu, Tao Jiang, Zikang Chen, Haoqian Wang†</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2502.06432)   [**Code**](https://github.com/huaqlili/Prompt-SID)</span>

<span style="font-size: 18px;">- In this paper, we introduce Prompt-SID, a prompt-learning-based single image denoising framework that emphasizes preserving structural details. This approach is trained in a self-supervised manner using downsampled image pairs.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='{{ site.baseurl }}/images/spatio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://ojs.aaai.org/index.php/AAAI/article/view/32242" style="font-size: 22px; color: #483D8B; text-decoration: none">**Spatiotemporal Blind-Spot Network with Calibrated Flow Alignment for Self-Supervised Video Denoising**</a><br>
<span style="font-size: 18px;">Chen, Zikang; Jiang, Tao; Hu, Xiaowan; Zhang, Wang; **Li, Huaqiu**; Wang, Haoqian†</span><br>
<span style="font-size: 18px;">[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/32242)   [**Code**](https://github.com/ZKCCZ/STBN)</span>

<span style="font-size: 18px;">- We explore the practicality of optical flow in the self-supervised setting and introduce a SpatioTemporal Blind-spot Network (STBN) for global frame feature utilization.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='{{ site.baseurl }}/images/icme.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="" style="font-size: 22px; color: #483D8B; text-decoration: none">**Measuring and Controlling the Spectral Bias in Self-Supervised Denoising**</a><br>
<span style="font-size: 18px;">Wang Zhang\*, **Huaqiu Li**\*, Tao Jiang, Zikang Chen, Haoqian Wang†</span><br>
<span style="font-size: 18px;">[**Paper**]()   [**Code**]()</span>

<span style="font-size: 18px;">- We introduce a Spectral Controlling network (SCNet) to optimize self-supervised denoising of paired noisy images. First, we propose a selection strategy to choose frequency band components for noisy images, accelerating the convergence speed of training.</span>

</div>
</div>

# 📑 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='{{ site.baseurl }}/images/mmgenbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2411.14062" style="font-size: 22px; color: #483D8B; text-decoration: none">**MMGenBench: Fully Automatically Evaluating LMMs from the Text-to-Image Generation Perspective**</a><br>
<span style="font-size: 18px;">Hailang Huang, Yong Wang, Zixuan Huang, **Huaqiu Li**, Tongwen Huang, Xiangxiang Chu, Richong Zhang†</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2411.14062)   [**Code**](https://github.com/lerogo/MMGenBench)</span>

<span style="font-size: 18px;">- We propose the MMGenBench-Pipeline, a straightforward and fully automated evaluation pipeline. This involves generating textual descriptions from input images, using these descriptions to create auxiliary images via text-to-image generative models, and then comparing the original and generated images.</span>

</div>
</div>